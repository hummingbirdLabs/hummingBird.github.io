---
title: "China AI Roundup: May 2026 – DeepSeek Cuts Prices, Qwen 3.7 Launches, Embodied AI Explodes"
date: 2026-05-29T10:00:00+08:00
draft: false
author: "Hummingbird Labs"

description: "May 2026 China AI developments recap: DeepSeek V4 Pro permanently drops to 25% of original price, R1 model cuts hallucinations by 50%; Alibaba Cloud Summit launches Qwen 3.7 series and in-house Zhenwu M890 AI chip; embodied AI market exceeds 1 trillion yuan, humanoid robots enter commercial use."

tags: ["DeepSeek", "Qwen", "Tongyi Qianwen", "Embodied AI", "Humanoid Robots", "AI Chips", "LLMs", "China AI"]
keywords: ["DeepSeek V4 Pro price cut", "DeepSeek R1 upgrade", "Qwen 3.7 launch", "Tongyi Qianwen", "Embodied AI", "Humanoid Robots", "AI Chips", "Zhenwu M890"]

---

## China AI Roundup: May 2026

In May 2026, China's AI scene can be summed up in three words: **price cuts, upgrades, and explosions**.

### I. DeepSeek: Permanent Price Cut + R1 Upgrade

**1. V4 Pro permanently down to 25%**

DeepSeek officially announced on May 23 that after the limited-time discount ends on May 31, the V4 Pro API price will be **permanently locked at 1/4 of the original price**. Specifically: 0.025 yuan per million input tokens (cache hit), 3 yuan per million input tokens (cache miss), and 6 yuan per million output tokens – setting a new global low for LLM pricing.

Back on April 26, DeepSeek had already cut all API input (cache hit) prices to 1/10 of the launch price. Together, these moves make V4 Pro's API cost roughly 1/30 that of GPT-5.5 and Claude Opus 4.7. The value proposition is insane.

**2. R1 just got updated to 0528 version**

Just in the past couple days (May 28-29), DeepSeek quietly pushed a small update to R1. The new version's accuracy jumped from 70% to 87.5% on the AIME 2025 test, and most importantly, **hallucination rates dropped by 45-50%**, making it way more reliable for tasks like editing, summarization, and reading comprehension. The trade-off? Single-task processing time is now 30-60 minutes – it's definitely thinking deeper.

**3. Pushing for 50-70 billion yuan funding, CATL and JD in talks**

Bloomberg reports that DeepSeek is working on a 70 billion yuan (≈$10 billion) funding round, with CATL, JD.com, and NetEase all in discussions. If it goes through, the valuation could exceed 350 billion yuan – easily the largest single funding round in Chinese AI history. Founder Liang Wenfeng has said the money will mainly go to R&D, with short-term monetization not a priority.

**4. Other bits and pieces**

- V4.1 expected in June, with improved MCP protocol support and multimodal capabilities
- May 24 saw major service instability as DAU broke 200 million
- Spotted hiring Agent Harness experts, might be building a Claude Code competitor for desktop

### II. Tongyi Qianwen: Qwen 3.7 is here + in-house chip

**1. Qwen 3.7 series officially launched**

At the Alibaba Cloud Summit on May 20, Tongyi Qianwen dropped their Qwen 3.7 flagship model series:

- **Qwen 3.7-Max-Preview**: Trillion-parameter MoE architecture, Agentic Coding capability (72.3% on SWE-bench Verified) ranks first in China, top 3 globally
- **Qwen 3.7-Plus-Preview**: 35B dense architecture, already open-sourced under Apache 2.0

The biggest highlight is their **All-field Thinking mode**, which for the first time unifies text+image+code reasoning chains – previously GPT-5.5 and Claude only supported text thinking chains. API cost is also down to 1/25 that of GPT-5.5.

**2. Pingtouge releases in-house Zhenwu M890 chip**

The same day, Alibaba's Pingtouge released the Zhenwu M890 in-house AI chip, completing their full-stack "chip+model+platform" offering with Qwen 3.7-Max and Qianwen Cloud Platform. Against the backdrop of US-China chip competition, this is way more significant than just performance numbers.

### III. Embodied AI: Finally moving from labs to mass production

**1. Market breaks 1 trillion yuan, 60k+ humanoid robots**

China's embodied AI market is expected to exceed 1 trillion yuan in 2026, with humanoid robot shipments projected to surpass 60,000 units – over 80% of global volume.

- **Zhiyuan Robotics**: The 10,000th Expedition A3 rolled off the line in early May, taking only 15 months to go from 1,000 to 10,000 units, with production efficiency hitting 30 minutes per unit
- **Unitree Robotics**: Their G1 humanoid robot actually boarded a Southwest Airlines flight as a paying passenger. Batteries had to be removed due to exceeding limits, delaying the flight by 62 minutes, but it still marks a milestone for humanoid robots in public transportation

**2. Beijing Humanoid releases world's first unified embodied AI model**

On May 16, the Beijing Humanoid Robot Innovation Center released Pelican-Unify 1.0, the world's first embodied AI model trained with a "grand unified" approach, achieving a "understanding-reasoning-imagination-action" closed loop. It scored 66.03 in the World Arena global evaluation, ranking first.

**3. Hangzhou hosts embodied robot scenario competition**

On May 15-16, Hangzhou held an international embodied robot scenario competition with over 200 teams. The interesting part? All challenges came from real business pain points at companies like Ant Group and Greentown Group, covering 14 scenarios. And no remote controls allowed – robots had to perceive, judge, and execute entirely on their own.

### IV. AI Hardware: Chips shifting from cloud to edge, compute infrastructure still accelerating

**1. ByteDance bumps AI capex to 200 billion yuan**

On May 11, ByteDance raised its 2026 AI capital expenditure plan from 160 billion yuan to over 200 billion yuan – a 25%+ increase – with most going to domestic AI chips.

**2. NVIDIA releases Blackwell Ultra**

At GTC on May 21, Jensen Huang dropped the new Blackwell Ultra data center GPU, with 2.3x the AI training performance of H100 at FP8 precision, optimized specifically for trillion-parameter models. Of course, actually getting your hands on one is another story.

**3. Edge AI chips explode**

Global edge AI chip shipments are up 78% YoY, with mid-to-low end AI chips for IoT and edge devices seeing over 110% YoY growth. Consumer hardware like AI headphones, AI glasses, and AI toys are also taking off – China's consumer AI hardware market is expected to exceed 1.27 trillion yuan in 2026.

**4. "Tao's Law" released**

On May 25, the semiconductor industry released "Tao's Law", proposing "time shrinking" as a replacement for traditional "geometric shrinking", using techniques like logic folding to continuously improve performance. If this works out, domestic AI chips will have an upgrade path that doesn't depend on EUV.

### Summary

To wrap up May 2026: DeepSeek keeps growing its user base with extreme value, Alibaba is building a full-stack offering with Qwen 3.7 and Zhenwu M890, and embodied AI is finally moving from proof-of-concept to scaled commercialization. Compute infrastructure investment is still going wild, and edge AI hardware is blossoming everywhere.

AI is moving from "cloud toy" to "productivity tool", and this trend was especially obvious in May.

### A Brief About Me
I've worked at NetEase Games, Baidu, Tencent (8 years), and Meituan (nearly 7 years), leading large-scale R&D projects and managing teams of 100+ engineers.

Currently, I'm pursuing entrepreneurship in the AI field.

Why? The world runs on uncertainty — staying in corporate roles too long breeds addiction to certainty. Starting an AI venture is like setting sail into uncharted waters.

Feel free to reach out: mailto:HummingbirdLabs@outlook.com.
