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


### 1.3 Role and Context Analysis

Role assignment - First, role assignment acted as a persona filter; by instructing the model to act as an "award-winning science teacher," "senior executive," or "top-tier copywriter," the model adjusted its vocabulary, sentence structure, and professional tone to match the expectations of those specific experts. Without these roles, the model defaults to a generic assistant style that is often too broad or overly casual for professional and technical tasks.

Context setting - Second, context setting provided the necessary constraints to move from general information to actionable solutions. Providing context such as the target audience (e.g., "urban professionals") or the specific strategic goal (e.g., "leaving the door open for future collaboration") forced the model to prioritize information that was tailored to a specific outcome. Instead of receiving a generic list of ideas, the inclusion of context allowed the model to filter out irrelevant information and focus on producing results that were immediately useful for the intended audience.







