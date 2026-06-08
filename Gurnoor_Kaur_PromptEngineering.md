# Prompt Engineering Portfolio

**Name:** Gurnoor Kaur

**Date:** June 8, 2026

**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation
### Goal: Explain blockchain to a 10-year-old.

**Version 1 Prompt**
Explain blockchain to a 10-year-old.

**Version 2 Prompt**
Explain blockchain to a 10-year-old in very simple words. Explain it in a way that can be understood after reading it once.

**Version 3 Prompt**
Explain blockchain to a 10-year-old in very simple words using a simple real-life example and analogy. Explain it in such a way that if required they can further explain it to someone else too.

### Final Output
Imagine a classroom with 30 students.

One day, the teacher puts a big chart on the wall to keep track of sticker trades.

Whenever a student gives stickers to another student, the teacher writes it on the chart:

Aarav gave Mia 2 stickers.
Mia gave Ben 1 sticker.

Everyone in the class can see the chart.

Now suppose Aarav tries to cheat and says:

"I never gave Mia 2 stickers!"

The whole class can look at the chart and say:

"Yes, you did. It's written right there."

Because everyone can see the same chart, it is very hard to lie or secretly change the records.

How this is like a blockchain
The chart = the blockchain.
The records of sticker trades = the information stored in the blockchain.
The students checking the chart = computers checking that everything is correct.
Why people use blockchain

People use it when they want records that are:

Easy for everyone to check.
Hard to cheat.
Not controlled by just one person.
A super-short explanation a 10-year-old can tell someone else

"A blockchain is like a big shared classroom chart where every trade is written down. Everyone can see it, so nobody can secretly change the records or cheat."

If they remember just that one sentence, they have understood the main idea of blockchain.


## 1.1 Scenario B: Professional Email
### Goal: Politely decline a job offer while maintaining interest in the company.

**Version 1 Prompt**
Write an email declining a job offer while maintaining interest in the company.

**Version 2 Prompt**
Write a professional email politely declining a job offer while thanking the company for the opportunity and maintaining interest in the company.

**Version 3 Prompt**
You are a professional career advisor. Write a polite and professional email declining a job offer. Express gratitude for the opportunity, show you are still interested in the company even if you are declining and briefly mention choosing another opportunity, and maintain a positive relationship for future opportunities.

### Final Output
You can customize the placeholders before sending:

Dear [Hiring Manager's Name],

Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time and effort that you and the team invested throughout the interview process, and I am grateful for the opportunity to learn more about the company and its work.

After careful consideration, I have decided to decline the offer, as I have chosen to pursue another opportunity that is a better fit for my current career goals and circumstances. This was not an easy decision, given the positive impression [Company Name] made on me during the recruitment process.

I want to express my genuine appreciation for your confidence in my abilities and for the warm and professional experience I had with everyone on the team. I remain highly interested in [Company Name] and have great respect for the organization's mission, culture, and accomplishments.

I hope to stay in touch and would welcome the opportunity to reconnect in the future should our paths cross again. Thank you once again for your consideration and generosity throughout this process.

Wishing you and the team continued success.

Kind regards,

[Your Name]

This version strikes a professional balance: it clearly declines the offer, expresses gratitude, mentions accepting another opportunity without unnecessary detail, and leaves the door open for future opportunities.



## 1.1 Scenario C: Creative Content
### Goal: Create a marketing tagline for an eco-friendly water bottle brand.

**Version 1 Prompt**
Create a marketing tagline for an eco-friendly water bottle brand.

**Version 2 Prompt**
Create a marketing tagline for an eco-friendly water bottle brand whose target audience is environmentally conscious youth.

**Version 3 Prompt**
You are a professional marketing copywriter. Create five short, memorable, and modern taglines for an eco-friendly water bottle brand targeting environmentally conscious youth. The taglines should promote sustainability without sounding preachy.

### Final Output
Here are five short, modern, and memorable taglines designed for environmentally conscious youth:

Sip Green. Live Clean.
Refill the Future.
Hydrate with Impact.
Less Waste. More Adventure.
Good Vibes. Better Planet.

These taglines keep the focus on sustainability while staying upbeat, relatable, and non-preachy.


## 1.2 Iteration Documentation

### Scenario A
| Version | What Changed | Why This Improved the Output |
|----------|----------|----------|
| V1 | Basic prompt requesting an explanation. | Established a baseline response. |
| V2 | Added requirement for simple language and easy understanding. | Made the explanation easier for a child to understand. |
| V3 | Added a real-life example and analogy. | Produced a clearer and more engaging explanation. |



### Scenario B
| Version | What Changed | Why This Improved the Output |
|----------|----------|----------|
| V1 | Requested an email declining a job offer while maintaining interest in the company. | Established the basic objective and desired outcome. |
| V2 | Added professionalism, politeness, and gratitude toward the company. | Improved the tone and made the email more respectful and professional. |
| V3 | Added role assignment (professional career advisor), gratitude, explanation of choosing another opportunity, and future relationship focus. | Produced a more polished, realistic, and relationship-building response aligned with professional communication standards. |

### Scenaio C
| Version | What Changed | Why This Improved the Output |
|----------|----------|----------|
| V1 | Requested a marketing tagline for an eco-friendly water bottle brand. | Established a baseline response and general branding direction. |
| V2 | Added a specific target audience: environmentally conscious youth. | Made the tagline more relevant and appealing to the intended audience. |
| V3 | Added role assignment (professional marketing copywriter), requested five taglines, and specified a modern, memorable, and non-preachy style. | Produced more creative, targeted, and market-ready taglines that better aligned with the brand's goals and audience. |


## 1.3 Role and Context Analysis
Role assignment and context setting significantly improved the quality of the outputs. In Scenario B, assigning the role of a professional career advisor helped generate a more polished and professional email with an appropriate tone. In Scenario C, assigning the role of a professional marketing copywriter resulted in more creative and audience-focused taglines. Providing context, such as the target audience and desired communication style, reduced ambiguity and helped the model generate responses that were more relevant, effective, and aligned with the intended goals.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation
**Low**
Write the opening 2-3 sentences of a short story about a mysterious door that suddenly appears in a school hallway. Be precise, factual, and consistent.

*Output*
At 8:05 a.m. on Monday, students arriving for first period noticed a wooden door in the east hallway of Westbrook Middle School. The door stood between two classroom entrances where no door had existed the previous day. By lunchtime, no teacher or maintenance worker could explain how it had appeared.

**Medium**
Write the opening 2-3 sentences of a short story about a mysterious door that suddenly appears in a school hallway.

*Output*
When Maya arrived at school on Tuesday morning, she stopped in the middle of the hallway. A tall blue door stood between two lockers where there had only been a blank wall the day before. No one knew where it had come from, and no one had seen it appear.

**High**
Write the opening 2-3 sentences of a short story about a mysterious door that suddenly appears in a school hallway. Be highly creative, imaginative, and explore unusual ideas.

*Output*
On the first day it appeared, the door was busy pretending to be a patch of sunlight. By lunchtime, it had given up the disguise and settled into the hallway between the science lab and the trophy case, humming softly in a language that sounded like forgotten dreams. The brass handle was warm to the touch, as if someone on the other side had just let go.


## 2.2 Analysis & Recommendations
Low temperature is useful when accuracy and consistency are important, such as writing technical documentation or answering factual questions. Another use case is professional communication, where clear and predictable responses are preferred. High temperature is useful for creative writing and brainstorming because it generates more imaginative and unique ideas. Another use case is marketing and advertising, where originality helps attract attention. For this task, the high temperature setting worked best because it created the most engaging and imaginative story opening while still maintaining coherence.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Without Chain-of-Thought
What is the average speed of a train that travels 120 km in 2 hours, stops for 30 minutes, and then travels another 90 km in 1.5 hours? Give only the final answer.
*Output*
52.5 km/h

### With Chain-of-Thought
What is the average speed of a train that travels 120 km in 2 hours, stops for 30 minutes, and then travels another 90 km in 1.5 hours? Show all calculations and explain your reasoning.
*Output*
To find the average speed, use the formula:

Average Speed=
Total Time
Total Distance
	​

Step 1: Calculate the total distance
First part: 120 km
Second part: 90 km
Total Distance=120+90=210 km
Step 2: Calculate the total time
Travel time for first part: 2 hours
Stop time: 30 minutes = 0.5 hours
Travel time for second part: 1.5 hours
Total Time=2+0.5+1.5=4 hours
Step 3: Calculate the average speed
Average Speed=
4
210
	​

=52.5 km/h
Final Answer  52.5 km/h

*Comparison*
The outputs differed in the level of detail provided. The first prompt returned only the final answer, while the second prompt showed the calculations and reasoning used to reach the answer. Chain-of-thought prompting helps with complex reasoning because it breaks a problem into smaller steps, making the process easier to follow and verify. One limitation I observed is that chain-of-thought responses are longer and can sometimes include unnecessary details for simple problems.

## 3.2 Few-Shot Prompting

*Zero-Shot Attempt*

*Prompt*
Classify each of the following reviews as Positive, Negative, or Neutral.

1. The product arrived damaged and customer service was unhelpful.
2. Works as expected, nothing special but does the job.
3. Absolutely love this! Best purchase I've made all year!
4. The quality is okay but slightly overpriced for what you get.
5. Terrible experience, would not recommend to anyone.

*Output*
1. **Negative** — The product arrived damaged and customer service was unhelpful.
2. **Neutral** — Works as expected, nothing special but does the job.
3. **Positive** — Absolutely love this! Best purchase I've made all year!
4. **Neutral** — The quality is okay but slightly overpriced for what you get.
5. **Negative** — Terrible experience, would not recommend to anyone.


*Few-Shot Attempt*
*Prompt*
Classify customer reviews as Positive, Negative, or Neutral.

Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Now classify these reviews:

1. The product arrived damaged and customer service was unhelpful.
2. Works as expected, nothing special but does the job.
3. Absolutely love this! Best purchase I've made all year!
4. The quality is okay but slightly overpriced for what you get.
5. Terrible experience, would not recommend to anyone.

*Output*
1. **Negative** — The product arrived damaged and customer service was unhelpful.
2. **Neutral** — Works as expected, nothing special but does the job.
3. **Positive** — Absolutely love this! Best purchase I've made all year!
4. **Neutral** — The quality is okay but slightly overpriced for what you get.
5. **Negative** — Terrible experience, would not recommend to anyone.

*Table*
| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|-----------|-----------------|----------------|--------------|-----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

*Analysis*
Few-shot prompting is most useful when tasks are complex or require a specific output format. The examples help the model understand the expected pattern and improve consistency. In this case, both zero-shot and few-shot prompting produced the same results because the reviews were straightforward and easy to classify.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

## 4.2 Testing for Bias

## 4.3 Limitations & Responsible Use
