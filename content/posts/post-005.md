---
title: "More on TRAE China Version: Free Models Are Great But Slow"
date: 2026-05-22T21:16:00+08:00
draft: false
slug: "trae-free-model-speed"
author: "Hummingbird Labs"

description: "A detailed performance comparison of TRAE China's free LLMs vs paid models: DeepSeek V4 Pro with think mode takes 50 minutes for large tasks, while free Qwen3.6 Plus is significantly faster with shorter queue times. Real data from actual coding projects, plus thoughts on DeepSeek's mission to democratize AI."

tags: ["TRAE", "DeepSeek", "Free LLM", "AI Coding", "Qwen", "Model Performance", "LLM Speed Comparison", "Chinese LLM", "TRAE China Review"]
keywords: ["TRAE free model speed", "DeepSeek V4 Pro slow", "Qwen3.6 Plus vs DeepSeek", "TRAE China free LLM performance", "free AI coding model comparison", "DeepSeek think mode", "LLM queue time TRAE"]

cover:
  image: /images/5-01.jpg
  alt: "TRAE IDE showing the maximum thinking attempts reached prompt for free DeepSeek V4 Pro model"
  caption: "Free model limitation: maximum thinking attempts reached — requires manual 'continue' to proceed"
  relative: false

---

# TRAE China Version: Real Data on Free Model Speed

Let me start with the conclusion: if you use the free models in TRAE China's version, they will be slower than custom paid models (even when comparing the same model).

The free models are mainly slower in 3 aspects:

1. When processing large tasks, free models may display a prompt: "Model has reached the maximum number of thinking attempts. Please type 'continue' to get more results." When this happens, you need to manually type "continue" to proceed. As shown in Figure 1.
![Figure 1](/images/5-01.jpg)

2. Calling free models requires queuing; this was already mentioned in the previous blog. As shown in Figure 2.
![Figure 2](/images/5-02.jpg)
Additionally, during task processing, there's a chance you'll need to queue again.

3. The DeepSeek V4 Pro model has think mode enabled by default, with a thinking depth of around 200, which makes it slower when processing large tasks. To illustrate this point, I recorded the execution time from my own project.

The specific execution time for a task was: begin 11:34 / end 12:24.
As shown in Figure 3.

![Figure 3](/images/5-03.jpg)

But here's what I found: the free Qwen3.6 Plus model is significantly faster than the paid DeepSeek V4 Pro model when handling large tasks — and I mean much faster. Moreover, the free Qwen3.6 Plus model has shorter queue times.

# Those Are the Real Data and Facts. Now Here's My Opinion: DeepSeek Is a Great Company, and Its Pricing and Services Truly Benefit the Public

I can understand that DeepSeek is still in development, which is why there are some limitations.

But the technology and services they provide are deeply imbued with a sense of human mission; based on this sense of mission and responsibility, this company is contributing to increasing the average intelligence of humanity.

This sense of mission and responsibility, in my personal view, stems from the founder's simple beliefs and character. In short, it's not about money — it's about serving the people.

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



