---
title: "Deepseek V4 Pro Price Drop Again on May 23, 2026"
date: 2026-05-24T09:36:00+08:00
draft: false
slug: "deepseek-v4-pro-price-drop"
author: "Hummingbird Labs"

description: "Deepseek V4 Pro pricing reduced to 25% of original price. Exploring AI model cost trends, WPF development challenges with LLMs, and why detailed debug logging is essential for AI-assisted coding."

tags: ["Deepseek", "AI Pricing", "LLM", "AI Coding Assistant", "WPF Development", "Debug Logging", "AI Software Development", "Large Language Models", "AI Model Comparison", "Developer Tools"]
keywords: ["Deepseek V4 Pro price drop", "Deepseek API pricing 2026", "AI model cost comparison", "LLM for WPF development", "AI coding assistant debug logging", "Deepseek vs Qwen vs Claude"]

cover:
  image: /images/6-01.jpg
  alt: "Deepseek V4 Pro pricing page showing the 75% discount and reduced cache hit prices"
  caption: "Deepseek V4 Pro permanently reduced to 25% of original price"
  relative: false

---

## Worried about Deepseek returning to full price in June 2026, but unexpectedly it dropped again yesterday

Here's the information from Deepseek's official website:
 For all models, the input cache hit price has been reduced to 1/10 of the launch price. This price adjustment takes effect from 2026/4/26 12:15 UTC.

The deepseek-v4-pro model API pricing will be officially adjusted to 1/4 of the original price after the 75% discount promotion ends on 2026/05/31 15:59 UTC.
![Figure 1](/images/6-01.jpg)

This means: Deepseek V4 Pro will permanently stay at 25% of the original price.

DeepSeek is so generous, I must support them by adding funds. So I happily recharged another 700 RMB (about $100 USD) to DeepSeek. Let's see how long this $100 credit will last.
![Figure 1](/images/6-02.jpg)


## Model capabilities still need improvement. Fixing certain UI interaction bugs isn't necessarily faster than human developers.

I've found that on Windows WPF UI, all models (deepseek-v4-pro, Qwen3.6 Plus, Claude Sonnet 4.6, etc.) don't perform very well. They easily produce compilation errors, runtime errors, and various UI data passing anomalies.

Is it because the Windows tech stack has fewer training materials for models, plus the numerous and complex library versions, leading to poor model performance?

My current solution is: add detailed local logs in debug mode to provide AI with more runtime information.

### Static code + runtime logs = complete program information.

Simply letting the LLM review code is not enough. Because the LLM can only judge program behavior based on static code. There are many hidden assumptions here. When AI reviews only a portion of code, it assumes other modules are working correctly.

If you let AI review all code in a project, the context becomes too long, leading to AI hallucinations (I mentioned this in a previous blog).


So I strongly recommend: always add detailed local logs in debug mode to provide AI with more runtime information.

### About Me

I've worked at NetEase Games, Baidu, Tencent (8 years), and Meituan (nearly 7 years), leading large R&D projects and managing teams of over 100 engineers.

Now I build software as an independent developer.

Why? Because the world is full of uncertainty—staying at one company too long can make you addicted to certainty. Building on your own is like sailing into uncharted waters.

I believe good software should give people a sense of security and control. That's the thread connecting everything I make:

- **[PhotoRestore Pro](https://hummingbirdlabs.github.io/LegalPhotoRestorePro/introduction_en.html)** — AI photo restoration that runs 100% offline on Windows. Your photos never leave your device. No cloud, no account, no compromise on privacy. Built for legal professionals, but anyone with old family photos will find it useful.

- **[AstroSky](https://hummingbirdlabs.github.io/Legal/AstroSky/introduction_en.html)** — Think of it as "Snapseed for astronomy." Turn raw FITS data into stunning celestial images. Fully offline, GPU-accelerated, with a Beauty/Science dual mode that serves both casual stargazers and researchers.

- **[fastool.io](https://www.fastool.io/en)** — A collection of browser-based science tools. Right now it's focused on astronomy: solar path tracking, moon phase analysis, sidereal time calculation, telescope FOV planning—all running in your browser with zero data upload.

Whether I'm gazing at the cosmos or refining a line of code, the goal is the same: build tools that put people in control of their own data.

Get in touch: [HummingbirdLabs@outlook.com](mailto:HummingbirdLabs@outlook.com).



