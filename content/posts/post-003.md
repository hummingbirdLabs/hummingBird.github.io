---
title: "Using Qwen 3.6 Plus: Great but a Bit Expensive"
date: 2026-05-22T08:22:00+08:00
draft: false
author: "Hummingbird Labs"

description: "Hands-on cost analysis of Qwen 3.6 Plus for large-scale C# development: why 876K tokens for 1.7 RMB looks cheap but 30 RMB per engineering task adds up fast, and how a dual-model strategy with DeepSeek cuts the bill."

tags: ["Qwen", "DeepSeek", "AI Coding", "Cost Analysis", "C#", "LLM"]
keywords: ["Qwen 3.6 Plus cost", "Qwen vs DeepSeek programming", "AI coding expense", "LLM for C# development", "Alibaba Cloud Qwen billing"]

cover:
  image: /images/3-01.jpg
  alt: "Alibaba Cloud console showing Qwen 3.6 Plus token usage and billing details"
  caption: "Qwen 3.6 Plus billing — looks cheap per line, but large tasks consume credits fast"
  relative: false
---

# I Think Qwen 3.6 Plus Has Strong Coding Capabilities, But My Costs Are Higher Than Expected
I compared two approaches:
1、Using Qwen 3.6 Plus to write large-scale C# programs, then having DeepSeek v4 Pro conduct code reviews;
2、Using DeepSeek v4 Pro to write large-scale C# programs, then having Qwen 3.6 Plus conduct code reviews.

I prefer the second approach for these reasons:
1、DeepSeek v4 Pro supports a context length of up to 1 million tokens. For large projects, this helps maintain clear logical connections between modules. Additionally, DeepSeek v4 Pro is currently more affordable (until May 31, 2026, it’s offered at 25% of the regular price—see screenshots in my previous blog).
2、Qwen 3.6 Plus delivers higher code quality but at a higher cost. Using it only for code reviews helps reduce overall expenses.

Below is a partial cost breakdown from my usage of Qwen 3.6 Plus. It might look cheap at first glance: one entry shows 876K tokens costing 1.7 RMB (≈ $0.24). But in practice, completing a single large engineering task often costs 30 RMB (≈ $4.00). The credits I top up on Alibaba Cloud deplete much faster with Qwen than with DeepSeek.

![图1](/images/3-01.jpg)


Another important note: Alibaba grants new users 1 million free tokens for many models, as shown below.

But is 1 million tokens truly generous? From my hands-on coding experience:
1 million tokens only cover 1–3 large programming tasks or several code reviews.
For heavy AI-assisted coding users, 1 million tokens feel like a 100ml beer—barely a sip.
![图1](/images/3-02.jpg)

So, if an article boasts about "burning 100 million tokens," it likely reflects limited real-world AI coding experience.

To wrap up, I’d like to acknowledge:
1、ByteDance’s TRAE IDE for its innovation;
2、DeepSeek v4 Pro for its generous long-context support and current affordability (I’ll share updated billing data in June);
3、Qwen 3.6 Plus for its strong coding capabilities and responsive API.

In upcoming blogs, I’ll detail how to leverage AI coding within TRAE.

# A Brief About Me
I’ve worked at NetEase Games, Baidu, Tencent (8 years), and Meituan (nearly 7 years), leading large-scale R&D projects and managing teams of 100+ engineers.

 Now, I’m building an AI startup. 
 
 Why? The world runs on uncertainty—staying in corporate roles too long breeds addiction to certainty. Starting an AI venture is like setting sail into uncharted waters.

Feel free to reach out: mailto:HummingbirdLabs@outlook.com.



