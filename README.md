# Prompt Engineering Portfolio
Name:Srikar Muppala

Date:03-jun-2026

LLM Used:Gemini

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation
Goal: Explain a complex technical concept (e.g., "blockchain", "neural networks", "recursion") to a 10-year-old

Initial Prompt: Explain "Recursion" to a 10-year-old.

Refined Prompt (V2): You are an award-winning science teacher for middle schoolers. Explain recursion. Use a clear analogy but ensure the tone is engaging and slightly more educational than the previous version

Refined Prompt (V3):You are an expert computer science tutor. Explain recursion to a 10-year-old. Use the 'Russian Nesting Dolls' analogy, but explicitly include a 'Check for Understanding' question at the end to make it interactive. Use simple, non-technical language.

Final Output: Hello! I am so excited to help you understand one of the coolest "secret weapons" that computer programmers use. It's called Recursion.Imagine you have a big set of Russian Nesting Dolls (the ones where you open a wooden doll, and there is a smaller one inside, and another one inside that).Recursion is just like opening those dolls! Here is how it works:The Step: You follow the same simple rule every time: Open the doll you are holding.
The Repeat: After you open a doll, you find a new, smaller doll inside. So, you do the exact same thing again—you open that one too!The Base Case (The "Stop" Sign): You can’t keep opening dolls forever. Eventually, you reach the tiniest doll in the middle—the one that doesn’t open. In programming, we call this the Base Case. It’s the special rule that tells the computer, "Stop! You're done now!"So, whenever a programmer uses recursion, they are just telling the computer: "Keep doing this same task over and over again, but make it a little smaller each time, and stop when you reach the very end.

### 1.1 Scenario B: Professional Email

Goal: 
Initial Prompt: Write an email declining a job offer but say I still like the company.

Refined Prompt (V2): You are a professional career coach. Rewrite the email I wrote to decline a job offer. Make it warmer and more appreciative of the time the team invested in my interview process. Include a specific sentence inviting the hiring manager to connect on LinkedIn so we can maintain a long-term professional relationship

Refined Prompt (V3):You are a senior-level executive. Refine the email further to be concise, highly professional, and gracious. Your goal is to leave the door open for future collaboration because the industry is small. Avoid sounding apologetic; instead, focus on the 'mutual fit' aspect. Ensure the tone is empathetic but firm in the decision. Structure the email as follows: 1) Thank them for the offer, 2) State the decision clearly but briefly, 3) Mention one specific thing you admire about their team/culture, 4) Suggest keeping in touch for future opportunities.
Final Output: 
Subject: Job Offer: [Job Title] - [Your Name]

Dear [Hiring Manager Name],
Thank you for the offer to join [Company Name] as [Job Title]. I truly appreciate the time and effort you and your team invested in the interview process.
After careful consideration, I have decided to move forward with a different opportunity that currently aligns more closely with my long-term career objectives. While I will not be joining your team at this time, I want to express how much I admire [Company Name]’s [mention one specific aspect, e.g., innovative approach to data architecture / commitment to community impact].
It was a pleasure getting to know the team, and I hold [Company Name] in high regard. Given the interconnected nature of our industry, I would welcome the opportunity to stay in touch and look forward to the possibility of our paths crossing in the future.
I wish you and the team continued success.
Best regards,
[Your Name]

### 1.1 Scenario C: Creative Content

Goal: Generate a creative marketing tagline for a new eco-friendly water bottle brand
Initial Prompt:Give me some taglines for an eco-friendly water bottle.

Refined Prompt (V2):"You are a world-class brand strategist for a sustainable lifestyle brand. Provide 5 taglines that focus specifically on the 'premium quality' and 'durability' of an eco-friendly water bottle. Your target audience is 'busy urban professionals' who care about both aesthetics and the environment. Avoid generic phrases like 'save the planet'.

Refined Prompt (V3):"You are a top-tier creative copywriter. Your goal is to write 5 taglines for an eco-friendly water bottle that feel minimalist, witty, and aspirational. Use the following constraints:Each tagline must be under 7 words.Use a 'Problem-Solution' structure (e.g., mention a pain point of plastic, then the benefit of your bottle).Tone should be confident and modern.Present the output in a clean bulleted list

Final Output: 
Ditch plastic. Drink infinitely better.
Single-use is over. Forever is here.
Plastic waste ends. Hydration begins.
Trash the bottle. Keep the water.
Less plastic. More legendary hydration.


### 1.2 Iteration Documentation
# Iteration Documentation

## Scenario A: Technical Explanation

**Goal:** Explain a complex technical concept ("Recursion") to a 10-year-old.

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain "Recursion" to a 10-year-old. | Initial prompt. | Produced a simple explanation but lacked engagement, analogy, and interaction. |
| V2 | You are an award-winning science teacher for middle schoolers. Explain recursion. Use a clear analogy but ensure the tone is engaging and slightly more educational than the previous version. | Added role prompting, educational tone, and analogy requirement. | Improved clarity and engagement by making the explanation more relatable and structured. |
| V3 | You are an expert computer science tutor. Explain recursion to a 10-year-old. Use the 'Russian Nesting Dolls' analogy, but explicitly include a 'Check for Understanding' question at the end to make it interactive. Use simple, non-technical language. | Added a specific analogy, audience focus, simple language requirement, and an interactive element. | Generated a highly engaging explanation with a concrete visual example and improved learning through interaction. |
---

## Scenario B: Professional Email

**Goal:** Write an email declining a job offer while maintaining a positive relationship with the company.

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer but say I still like the company. | Initial prompt. | Produced a functional email but lacked professionalism and networking intent. |
| V2 | You are a professional career coach. Rewrite the email I wrote to decline a job offer. Make it warmer and more appreciative of the time the team invested in my interview process. Include a specific sentence inviting the hiring manager to connect on LinkedIn so we can maintain a long-term professional relationship. | Added appreciation, networking, and relationship-building elements. | Resulted in a more thoughtful and professional email. |
| V3 | You are a senior-level executive. Refine the email further to be concise, highly professional, and gracious. Your goal is to leave the door open for future collaboration because the industry is small. Avoid sounding apologetic; instead, focus on the 'mutual fit' aspect. Ensure the tone is empathetic but firm in the decision. Structure the email as follows: 1) Thank them for the offer, 2) State the decision clearly but briefly, 3) Mention one specific thing you admire about their team/culture, 4) Suggest keeping in touch for future opportunities. | Added executive perspective, structure, tone guidance, and future collaboration focus. | Produced a polished, concise, and relationship-focused professional email. |

---
## Scenario C: Creative Content

**Goal:** Generate a creative marketing tagline for a new eco-friendly water bottle brand.

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Give me some taglines for an eco-friendly water bottle. | Initial prompt. | Generated generic taglines with limited brand differentiation. |
| V2 | You are a world-class brand strategist for a sustainable lifestyle brand. Provide 5 taglines that focus specifically on the premium quality and durability of an eco-friendly water bottle. Your target audience is busy urban professionals who care about both aesthetics and the environment. Avoid generic phrases like "save the planet". | Added audience, positioning, and messaging constraints. | Produced more targeted and premium-oriented taglines. |
| V3 | You are a top-tier creative copywriter. Your goal is to write 5 taglines for an eco-friendly water bottle that feel minimalist, witty, and aspirational. Use the following constraints: Each tagline must be under 7 words. Use a Problem-Solution structure. Tone should be confident and modern. Present the output in a clean bulleted list. | Added creative style, word limits, structure, tone, and formatting requirements. | Generated concise, memorable, and brand-ready taglines with stronger marketing appeal. |

### 1.3 Role and Context Analysis

Role assignment - First, role assignment acted as a persona filter; by instructing the model to act as an "award-winning science teacher," "senior executive," or "top-tier copywriter," the model adjusted its vocabulary, sentence structure, and professional tone to match the expectations of those specific experts. Without these roles, the model defaults to a generic assistant style that is often too broad or overly casual for professional and technical tasks.

Context setting - Second, context setting provided the necessary constraints to move from general information to actionable solutions. Providing context such as the target audience (e.g., "urban professionals") or the specific strategic goal (e.g., "leaving the door open for future collaboration") forced the model to prioritize information that was tailored to a specific outcome. Instead of receiving a generic list of ideas, the inclusion of context allowed the model to filter out irrelevant information and focus on producing results that were immediately useful for the intended audience.



#Part 2: Temperature & Parameter Control (20 points)

## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

**Prompt used:** "Write a product description for a new high-performance laptop designed for professional video editors." (With temperature-specific modifiers added)

**Low Temperature Output (Deterministic):**
Product Specification: ProEdit Studio X1
The ProEdit Studio X1 is a high-performance mobile workstation engineered specifically for professional-grade video editing, color grading, and motion graphics workflows.
Technical Specifications
Processor: 16-core CPU (8 Performance-cores, 8 Efficiency-cores) with a maximum turbo frequency of 5.4 GHz.
Memory: 64GB LPDDR5X RAM, unified architecture with 400 GB/s memory bandwidth to facilitate real-time playback of high-bitrate footage.
Graphics: Dedicated GPU with 16GB GDDR6 VRAM, optimized for hardware-accelerated encoding/decoding (H.264, HEVC, ProRes) and 3D rendering.
Display: 16.2-inch Liquid Retina XDR display; 3456 x 2234 native resolution; 1,600 nits peak brightness (HDR content); 1,000,000:1 contrast ratio; 120Hz ProMotion adaptive refresh rate.
Storage: 2TB NVMe SSD with sequential read speeds up to 7,400 MB/s.
Connectivity: 3x Thunderbolt 4 (USB-C) ports, 1x HDMI 2.1 port, SDXC card slot (UHS-II), Wi-Fi 7, and Bluetooth 5.4.
Thermal Management: Dual-fan cooling system designed to handle sustained loads of 100W+ TDP.

**Medium Temperature Output (Balanced):**
Meet the StudioFlow Pro: Where Precision Meets Power
The StudioFlow Pro is engineered for those who demand absolute reliability in the edit suite. Built to handle complex, multi-layered timelines and intensive rendering, this is the workstation that keeps up with your vision.
Key Features:
- Unrivaled Processing: Effortlessly handles 8K raw files and high-bitrate color grading.
- Color-Accurate Display: 16.2-inch XDR display for absolute color fidelity and deep contrast.
- Blazing Workflow Speed: Integrated high-speed SSD and advanced unified memory reduce export times.
- Pro-Grade Connectivity: Comprehensive port selection ensures your peripherals are always ready.
- Cool Under Pressure: Advanced thermal architecture ensures consistent, sustained performance.
The StudioFlow Pro isn’t just a laptop—it’s an extension of your creative workflow.

**High Temperature Output (Creative):**
Introducing the Zenith Obsidian: The Canvas That Never Sleeps
The edit suite is no longer a room; it’s a state of mind. When inspiration strikes at 3:00 AM, you need a partner that breathes life into your pixels and turns raw footage into visceral emotion.
Crafted for the Visionaries: Forged from aerospace-grade brushed titanium, it carries the silent, brooding elegance of an artisan’s tool.
See the Unseen: Our Infinite-Depth OLED display doesn't just show color; it recreates reality.
The Heart of a Titan: Powered by a Neural-Sync architecture that predicts your next cut, it laughs at 12K RAW files.
A Legacy in the Making: We designed the Obsidian for the high-stakes deadlines and the quiet moments of breakthrough. It’s for the editors who refuse to settle. The Zenith Obsidian. Where your vision finds its voice.

| Temperature Setting | Description | Key Differences Observed |
| :--- | :--- | :--- |
| **Low** | Deterministic | Highly structured; focuses strictly on hardware specs and technical metrics; clinical tone. |
| **Medium** | Balanced | Professional and persuasive; balances specs with functional workflow benefits. |
| **High** | Creative | Uses dramatic, evocative language; focuses on the "artistic experience" rather than hardware. |

### 2.2 Analysis & Recommendations

I would use a low temperature for tasks requiring high accuracy and consistency, such as coding or summarizing technical documentation, where factual errors are unacceptable. Conversely, I would use a high temperature for creative endeavors like brainstorming marketing campaigns or drafting fictional narratives where originality and "out-of-the-box" thinking are prioritized. For this product description task, the medium temperature worked best; it successfully bridged the gap between necessary technical clarity and the persuasive, engaging language required for a sales-driven description. The low temperature was perhaps too dry for marketing, while the high temperature occasionally drifted into over-the-top marketing hyperbole that lacked grounding in technical reality. Therefore, the balanced approach provided the most professional and effective end result.








