# Prompt Engineering Course

This README was created for the [Prompt Engineering Course](https://www.udemy.com/course/chatgpt-prompt-muhendisligi). Feel free to explore it on your own, or follow along with the course.

# Prompt Engineering Fundamentals According to ChatGPT

Prompt engineering is a critical skill when interacting with AI language models like ChatGPT. It involves crafting prompts that effectively guide the AI toward the desired output. Here are five fundamentals of prompt engineering with brief explanations:

1. **Clarity and Specificity**:
   - What you ask should be clear and specific. Vague prompts often lead to generic or irrelevant answers. Specificity narrows the model’s focus and increases relevance.

2. **Contextual Information**:
   - For complex or nuanced requests, provide the necessary background. This helps the model understand the scenario and tailor the response.

3. **Purpose and Goal Orientation**:
   - A prompt should have a clear purpose. Whether you want information, creative output, problem solving, or exploration, the prompt should be aligned with that goal.

4. **Structured Approach**:
   - Structured frameworks (such as RGC, ICE or constraint-led prompts) can significantly improve results by guiding the response systematically.

5. **Iterative Refinement**:
   - Prompting is often iterative. The model’s first response can help you refine your next prompt by clarifying, adding details, or narrowing focus.

These fundamentals are the backbone of effective prompt engineering. By applying them, you can significantly improve both output quality and your overall interaction experience.

## Best Practices in Prompt Engineering

Effective prompt engineering is key to getting the best responses from AI models. Here are common best practices with improved, real-world examples:

### 1. **Start with Clear, Concise Questions**:
   - **Practice**: Use simple language and avoid unnecessary complexity.
   - **Example**:
     - Less Effective: "I need to prepare a presentation and it includes important things—can you help?"
     - More Effective: "I’m giving a 10-minute talk tomorrow. Topic: 'Clarity in prompt engineering'. Audience: beginners. Can you propose a 6-slide outline and 2 bullet points per slide?"

### 2. **Provide Adequate Context**:
   - **Practice**: Add relevant background information.
   - **Example**:
     - Less Effective: "Create a roadmap for me."
     - More Effective: "I’m building an online course. Goal: publish the first version in 2 weeks. I can work 2 hours/day. Topics: prompt fundamentals, examples, mini assignments. Create a 14-day plan: daily goal + tasks + deliverable."

### 3. **Be Specific in Your Requests**:
   - **Practice**: Define exactly what you want.
   - **Example**:
     - Less Effective: "Give me marketing tips."
     - More Effective: "I have a habit-tracking mobile app. Target: university students. Create a 7-day Instagram content plan: 1 post idea/day + 1 reels idea/day + a short caption draft."

### 4. **Use Closed-Ended Questions for Precise Information**:
   - **Practice**: Use closed-ended prompts when you need concise, targeted output.
   - **Example**:
     - Less Effective: "Can you evaluate this text?"
     - More Effective: "The text below is a LinkedIn post. Rate it 1–10 for (clarity, value proposition, flow). Output only the scores. Text: '...'"

### 5. **Use Open-Ended Questions for Exploration**:
   - **Practice**: Use open-ended prompts when you want breadth, creativity, or options.
   - **Example**:
     - Less Effective: "Give me content ideas."
     - More Effective: "Generate 12 content ideas about common mistakes beginners make in prompt engineering. For each: title + one-sentence description + recommended format (tweet/video/blog)."

### 6. **Iteratively Refine Your Prompts**:
   - **Practice**: Use the model’s output to refine your next instruction.
   - **Example**:
     - Initial Prompt: "Help me write an email."
     - Follow-Up Prompt (after the first response): "Topic: apology for delayed delivery. Tone: short, professional, not blaming. Write 2 paragraphs + a 3-bullet 'next steps' list. 120–160 words."

### 7. **Avoid Leading or Biased Prompts**:
   - **Practice**: Avoid steering the model toward a predetermined conclusion.
   - **Example**:
     - Less Effective: "Why is remote work definitely more productive?"
     - More Effective: "Evaluate how remote work impacts productivity with pros/cons. Under what conditions does productivity increase or decrease? Give concrete examples."

### 8. **Consider the Model’s Capabilities and Limits**:
   - **Practice**: Align your request with what the model can reliably do.
   - **Example**:
     - Less Effective: "Search the internet for the latest sources and give me the definitive answer."
     - More Effective: "Based only on the text below, produce a 6-bullet summary. Do not add any information that is not in the text. Text: '...'"

### 9. **Clarify Ambiguities in the Model’s Response**:
   - **Practice**: Ask follow-up questions when the answer depends on missing details.
   - **Example**:
     - AI Response: "The strategy depends on your goal."
     - Follow-Up: "Goal: 1,000 new email signups in 30 days. Budget: $0. Channels: Instagram + YouTube. Propose a 3-phase plan (week by week)."

### 10. **Balance Detail and Brevity**:
   - **Practice**: Provide enough detail to guide, but avoid dumping everything at once.
   - **Example**:
     - Less Effective: "We’ll launch a product and there’s target audience, pricing, competitors… I’m overwhelmed—tell me something general."
     - More Effective: "New product: personal budgeting app. Target: recent graduates. Competitors: free apps. Give 3 pricing options + pros/cons for each + which one you recommend and why."

These best practices help you formulate prompts that yield more accurate, relevant, and useful outputs.

## Prompt Priming

Prompt priming is a technique where the first instruction sets context/tone/format that influences the rest of the interaction.

1. **Creative writing without priming**:
   - Prompt: "Write a story about dragons and elves."

2. **Creative writing with priming**:
   - Prompt: "Imagine a mystical world where dragons and elves live in peace. There is a legend about a lost city made of gold, guarded by a wise dragon. Write a short story about a young elf named Elara who sets out to find it."

3. **Technical explanation without priming**:
   - Prompt: "Explain machine learning."

4. **Technical explanation with priming**:
   - Prompt: "Explain machine learning as if you were a teacher in a high school classroom. Use simple analogies and avoid technical jargon."

## Practical Prompt Templates 

Instead of long lists of frameworks, here are popular templates that work well in practice (each includes an example topic/prompt).

1) **RGC (Role + Goal + Context) — (Keep this)**

Template:
```
Role: [....]
Goal: [....]
Context: [....]
Output format: [bullets / table / email / checklist]
```

Example 1 (structured):
```
Role: Career coach
Goal: Build a 30-day English speaking practice plan
Context: I have 20 minutes/day, I’m around B1, and I’m preparing for job interviews
Output format: day-by-day plan + self-evaluation criteria
```

Example 1 (same content, natural language):
```
You are a career coach. I want a 30-day English speaking practice plan.
I have 20 minutes per day; my goal is to reach B1 and prepare for job interviews.
Create a day-by-day plan and suggest ways I can evaluate myself (metrics/feedback).
```

Example 2 (structured):
```
Role: Product Manager (PM)
Goal: Propose improvements for a subscription cancellation flow
Context: Users get stuck on the cancellation screen; we want to reduce churn
Output format: 5 ideas + expected impact + risks
```

Example 2 (same content, natural language):
```
You are a Product Manager (PM). Users get stuck in our subscription cancellation flow.
We want to reduce churn. Propose 5 improvements and write expected impact + risks for each.
```

2) **Constraints + Output Format Lock**

Template:
```
Follow these rules:
- Length: max X bullets
- Tone: [formal / casual]
- Forbidden: [....]
Output only as [table / bullets / JSON].
```

Example (structured):
```
Write a LinkedIn post.
Rules: max 120 words, 3 bullets, friendly but professional, no emojis.
Output: only the post text.
Topic: "Why clarity and constraints matter in prompt engineering"
```

Example (natural language):
```
Write a short LinkedIn post about why clarity and constraints matter in prompt engineering.
Max 120 words, use 3 bullet points, friendly but professional tone, no emojis.
Output only the post text.
```

3) **ICE (Instruction + Context + Examples)**

Template:
```
Instruction: [exactly what I want]
Context: [who/why/constraints]
Example(s): [1–3 examples in the desired style/format]
Now apply: [new input]
```

Example (structured) — ICE works best when examples include an explicit output:
```
Instruction: Write a customer support reply.
Context: E-commerce; English; short and empathetic; not blaming; end with exactly 1 question.
Example(s):
- Customer: "My package hasn't moved for 5 days."
  Reply: "I’m sorry about the delay. I’ll check the latest shipping status right now. Could you share your order number?"
- Customer: "The item arrived broken—I want a refund."
  Reply: "I’m sorry it arrived damaged. Let’s start a refund quickly. Could you send a photo and your order number?"
Now apply:
- Customer: "I updated my address, but the shipment is still going to the old one."
```

Example (natural language):
```
Reply like an e-commerce customer support specialist.
Keep it short and empathetic, don’t use a blaming tone, and end with exactly 1 question.

Follow the style in these examples:
Example 1
Customer: "My package hasn't moved for 5 days."
Reply: "I’m sorry about the delay. I’ll check the latest shipping status right now. Could you share your order number?"

Example 2
Customer: "The item arrived broken—I want a refund."
Reply: "I’m sorry it arrived damaged. Let’s start a refund quickly. Could you send a photo and your order number?"

Now reply in the same style:
Customer: "I updated my address, but the shipment is still going to the old one."
```

4) **Output with Acceptance Criteria**

Template:
```
Task: [....]
Acceptance criteria:
- [....]
- [....]
Output: [format]
```

Example (structured):
```
Task: Create a lesson plan for a beginner video.
Acceptance criteria:
- Beginner-friendly
- 5 sections, 5–7 minutes each
- 1 practice question per section
Output: section title + goal + practice question
```

Example (natural language):
```
Create a beginner-friendly lesson plan for a video.
Make 5 sections (5–7 minutes each). Each section must include 1 practice question.
Output format: section title + goal + practice question.
```

5) **Critic-then-Revise (Rubric-based improvement)**

Template:
```
First draft.
Then critique using this rubric: [clarity, accuracy, usefulness]
Finally: improve and output the final version.
```

Example (natural language):
```
Write a short lesson draft on "teaching prompt writing to beginners".
Then critique it with this rubric: clarity, example quality, no unnecessary repetition.
Finally, output an improved final version.
```

6) **Clarifying Questions + Assumptions**

Template:
```
If information is missing, ask up to 3 clarifying questions.
If no answers are provided, state reasonable assumptions and proceed.
```

Example (natural language):
```
I want to make my course content more effective.
Ask up to 3 clarifying questions first. If I don’t answer, proceed with reasonable assumptions.
Then give 5 concrete improvement suggestions and explain expected impact in 1 sentence each.
```
## Zero-shot, One-shot, and Few-shot Prompting

These approaches differ by whether (and how many) examples you provide:

- **Zero-shot**: No examples; just instructions. Great for simple tasks.
- **One-shot**: One example. Very effective for “locking” a format or behavior.
- **Few-shot**: A few examples. Useful for classification, style imitation, and structured outputs.

**Example task:** Determine the sentiment of a sentence.

***Zero-shot example***
```
You are a sentiment analysis specialist.
Classify the sentiment of the sentence as one of: ["positive", "negative", "neutral"].
Output only the label (one word).

Sentence: "Today was amazing—I feel great."
```

***One-shot example (lock behavior/format)***
```
Task: Classify the sentiment of a sentence.
Labels: ["positive", "negative", "neutral"]
Output format: label + short reason (one sentence).

Example:
Sentence: "My package got delayed again—I'm so tired of this."
Output: negative — It expresses frustration and dissatisfaction.

Now do this:
Sentence: "Thanks to everyone involved—this turned out excellent."
```

***Few-shot example (teach behavior)***
```
Task: Classify the sentiment of a sentence.
Labels: ["positive", "negative", "neutral"]
Output format: label + short reason (one sentence).

Sentence: "This app keeps crashing after the last update."
Output: negative — It describes a problem and dissatisfaction.

Sentence: "It's fine; it gets the job done."
Output: neutral — It’s neither strong praise nor a clear complaint.

Sentence: "I love it—it's way better than I expected!"
Output: positive — It shows strong satisfaction and enthusiasm.

Now do this:
Sentence: "I wish it was faster, but at least it’s finished."
```

## Prompt Revisions

1. **Highlight the most critical keywords in bold**:
   - "Please write the most critical key terms in **bold** in this text…"

2. **Organize information by specific criteria**:
   - "Arrange the content chronologically and categorize it by date, place, and cost…"

3. **Generate unique and less common ideas**:
   - "Can you provide more creative and less common suggestions for…"

4. **Add relevant emojis for emphasis**:
   - "Add suitable emojis to increase expressiveness…"

5. **Simplify for a younger audience**:
   - "Can you explain this so a 5-year-old could understand…"

6. **Convert into a table with defined categories**:
   - "Please present this as a table and group it into relevant categories…"

7. **Rewrite from an expert’s perspective**:
   - "Rewrite this from the perspective of an industry expert, focusing on professional insights…"

8. **Make the tone more formal/informal**:
   - "Please rewrite this in a more formal/informal tone…"

9. **Fix grammar and replace specific terms**:
   - "Fix any grammar mistakes and replace the following terms with…"

10. **Add personality and humor**:
    - "Can you rewrite this to be more engaging and humorous…"

11. **Adopt a specific perspective/voice**:
    - "Write this from the viewpoint of [specified role/character]…"

12. **Summarize into a single tweet (280 characters)**:
    - "Summarize this to fit into a tweet (280 characters)…"

13. **Expand into a three-part summary**:
    - "Split this into a three-part summary covering the main points…"

14. **Do a comparative analysis**:
    - "Compare and contrast key elements, highlighting important differences and similarities…"

15. **Identify and list 10 key quotes/takeaways**:
    - "What are the 10 most important points or quotes from this…"

16. **Expert review with improvement suggestions**:
    - "From a professional perspective, how would you improve this…"

17. **Structure as bullet points**:
    - "Please format this as a clear bullet-point list…"

18. **Translate into another language (if applicable)**:
    - "Translate this into [language] while keeping the original meaning…"

19. **Create a visual representation / infographic**:
    - "Turn this into a visual infographic highlighting the key points…"

20. **Draft a short executive summary**:
    - "Write a concise executive summary capturing the essence of this document…"

21. **Create an FAQ list based on the content**:
    - "Create a list of frequently asked questions (FAQ) from this content…"

22. **Write a persuasive argument for/against a stance**:
    - "Formulate a convincing argument supporting or opposing the stance below…"

These revised prompts are designed to be more directive and specific, helping you get more focused and relevant outputs.

## Hallucination Management

Language models can sometimes produce information they are not sure about **as if it were true**. This matters especially for dates, numbers, citations, laws, medical/financial topics. Prompt-level guardrails help.

### 1) Chain of Verification
Ask the model to produce an answer, break it into verifiable claims, and flag uncertainty.

[Chain of Verification Prompt - Langsmith Hub](https://smith.langchain.com/hub/atilsamancioglu/chainofverification)

```
First write a short draft answer.
Then list the claims in your answer as "verifiable claims".
For each claim: (a) what information is needed to verify it, (b) if we don't have it, write "Unknown".
Finally, rewrite the answer using only the verifiable parts and clearly mark what could not be verified.
```

### 2) Step-back Prompting
Ask the model to step back and identify assumptions and missing info before answering.

[Step-back Prompting - Langsmith Hub](https://smith.langchain.com/hub/atilsamancioglu/stepbackprompting)

```
Before answering, step back:
(1) What assumptions are critical to answer this?
(2) What information may be missing?
(3) What clarifying questions should we ask to make the answer reliable?
Then provide your best answer; ask clarifying questions if needed.
```

### 3) “According to …” Prompting (Source-grounded answers)
Force the model to rely only on the provided source.

[According to ... Prompting - Langsmith Hub](https://smith.langchain.com/hub/atilsamancioglu/accordingto)

```
Answer according to the text below.
Do not add any information that is not present in the text.
If the answer is not in the text, say: "This information is not included in the provided text."
```

## Advanced Prompt Techniques for ChatGPT

Advanced techniques involve using the model’s capabilities to handle complex tasks, improve reliability, and use AI creatively in real applications:

### 1. **Prompt chaining for complex tasks**:
   - **Description**: Break a complex task into smaller sequential prompts.
   - **Example**:
     - **Task**: Research and summarize an article.
     - **Prompts**:
       1. "Search for recent articles about renewable energy developments."
       2. "Pick one article and read it."
       3. "Summarize the key points in one concise paragraph."

### 2. **Context layering**:
   - **Description**: Add layers of context in follow-up prompts.
   - **Example**:
     - **Initial Prompt**: "Explain quantum computers in simple terms."
     - **Follow-up Prompt**: "Based on that explanation, what could be future applications of quantum computing in cybersecurity?"

### 3. **Creative storytelling and scenarios**:
   - **Example**:
     - **Prompt**: "Write a story where AI becomes the primary form of government, exploring both benefits and challenges."

### 4. **Counterfactual thinking**:
   - **Example**:
     - **Prompt**: "If the internet had never been invented, how would today’s global society be different?"

### 5. **Role-play and perspectives**:
   - **Example**:
     - **Prompt**: "Write a dialogue between a climate activist and an oil company CEO debating environmental policies."

### 6. **Analogies and metaphors**:
   - **Example**:
     - **Prompt**: "Explain black holes using an analogy suitable for a high school student."

### 7. **Sequential learning prompts**:
   - **Example**:
     - **Prompt series**:
       1. "What are the basic principles of economics?"
       2. "How do these principles apply to supply and demand?"
       3. "Give a real-world example of supply and demand."

### 8. **Error detection and improvement**:
   - **Example**:
     - **Prompt**: "Here is a summary of renewable energy sources. Can you identify inaccuracies and suggest improvements?"

### 9. **Interactive, evolving storylines**:
   - **Example**:
     - **Prompt**: "Start a space-adventure story. After each paragraph, I’ll decide what the main character does next."

### 10. **Prediction prompts**:
   - **Example**:
     - **Prompt**: "Given current technology trends, what are your top three predictions for major tech advances over the next decade?"

---

## DALL·E 3 Image Generation Guide

### **Key Points (for modern DALL·E):**

1. **Clarity and focus:** Describe what you want to generate clearly (subject, setting, key objects).
2. **Style, lighting, and mood:** Provide style, palette, light source, atmosphere.
3. **Visual consistency:** Reuse stable descriptions to iterate on the same character/object.
4. **Text rendering:** Specify exact text for posters, signs, logos (DALL·E 3 can produce readable text).
5. **Transparent backgrounds:** Useful for logos, UI elements, product shots.
6. **Detail without over-constraining creativity:** Give enough guidance without being overly technical.
7. **Layout and composition:** Specify where elements sit in the scene.

---

### Prompt examples:

1. "At sunset in Neo Tokyo: pink neon signs, flying cars in the sky, and people walking across transparent bridges. A sign in the foreground clearly says 'Welcome to Neo Tokyo'."
2. "A pastel-colored unicorn character on a transparent background. Minimalist children’s book style, playful and cheerful facial expression."
3. "A family camping under a starry night sky, sitting around a campfire with warm light. A lake and mountain silhouette in the background. Realistic style."
4. "An illustration on an old book page with a gothic typeface title 'Ars Technica', ink stains, and a gold-foiled heading."
5. "High-quality 3D render of modern smart glasses with a minimalist design. Transparent background."
6. "A busy medieval market scene with vendors, colorful stalls, and lively townspeople, in a detailed realistic historical painting style."

---

### Real-world applications (updated):

| Use Case | Updated Example |
|--|--|
| **Logo design** | “A logo for a natural skincare brand on a transparent background, with a water-drop icon and handwritten text ‘Luna Botanicals’.” |
| **Product concept art** | “A futuristic laptop with a holographic UI, metallic blue palette, 3D concept art style for a tech presentation.” |
| **Marketing visual** | “An organic breakfast table on a sunny morning picnic: fresh fruit, jam, coffee. Vibrant, realistic, positive mood.” |
| **Website banner** | “A travel platform banner: a family flying a kite on a peaceful beach. High resolution, wide banner composition.” |
| **Real estate visualization** | “3D visualization of a sustainable housing project with solar panels, shared gardens, and modern facades.” |
| **Fashion inspiration** | “Star-themed haute couture dress: midnight-blue fabric, sparkling stones, dramatic cape trailing behind.” |
| **Packaging design** | “Premium skincare serum packaging: clean white box with soft purple tones, lavender and aloe imagery.” |
| **Corporate infographic** | “A minimal infographic showing steps of a new onboarding process with simple icons and numbered sections.” |
| **Event brochure** | “Tech-themed poster: ‘AI Summit 2025’ with holographic elements and modern typography.” |
| **Restaurant menu visual** | “Vintage menu design for Ottoman cuisine, hand-drawn style with copper plates and rich food illustrations.” |

---

### Extra tips

- For **repeatable characters**, use stable descriptions like `a girl with red curly hair wearing a yellow coat`.
- For **the same character in a different pose**, add a continuation like `the same girl, now sitting by the window reading a book`.
- If you need text, be explicit: `"A sign saying 'Open for Magic'"`.
- For transparency, include: `"on a transparent background"`.
- Include the target medium (poster, Instagram, logo, product label) so the model composes accordingly.

---

## Case Studies in Prompt Engineering

Here are some case studies and real-world examples showing the impact of effective prompting:

### 1. **Customer Service Chatbot Optimization**:
   - **Scenario**: A company uses a chatbot to handle customer support inquiries.
   - **Problem**: The chatbot struggled with ambiguous questions and produced irrelevant answers.
   - **Solution**: Prompts were redesigned to be more specific, ask clarifying questions, and guide users to provide key details.
   - **Outcome**: Resolution quality improved; customer satisfaction rose; the need for human escalation decreased.

### 2. **Content Creation for Social Media**:
   - **Scenario**: A digital marketing agency uses AI to generate social posts.
   - **Problem**: Early outputs were generic and lacked brand voice.
   - **Solution**: Prompt priming was used to specify brand tone, style, and key messages.
   - **Outcome**: Content aligned better with each brand’s voice and engagement increased.

### 3. **Educational Tool for Learning Programming**:
   - **Scenario**: An education platform uses AI to teach programming.
   - **Problem**: Explanations were too technical for beginners.
   - **Solution**: Prompts asked the model to explain concepts “as if to a beginner” and to use real-world analogies.
   - **Outcome**: Learners reported better understanding and a more enjoyable learning experience.

### 4. **Data Analysis in Research**:
   - **Scenario**: Researchers use AI to analyze large datasets.
   - **Problem**: The model returned too much raw data without insight.
   - **Solution**: Prompts were narrowed to request specific analyses, trends, and summaries.
   - **Outcome**: More concise interpretations helped speed up research work.

### 5. **Interactive Storytelling in Games**:
   - **Scenario**: A game studio integrates AI for dynamic storytelling.
   - **Problem**: Stories were inconsistent and didn’t adapt well to player choices.
   - **Solution**: Developers used iterative prompts that evolved based on player decisions.
   - **Outcome**: Players praised the responsive narrative and engagement increased.

### 6. **Healthcare Information**:
   - **Scenario**: A healthcare organization uses AI to inform patients.
   - **Challenge**: Initial answers were too technical and confusing.
   - **Solution**: Prompts requested plain-language explanations without heavy jargon.
   - **Outcome**: Patients understood better and reported higher satisfaction.

### 7. **Legal Document Summarization**:
   - **Scenario**: A law firm summarizes long legal documents with AI.
   - **Challenge**: Summaries were either too long or missed key points.
   - **Solution**: Structured prompts requested key issues, implications, and actionable items.
   - **Outcome**: Summaries became more useful for faster decision-making.

### 8. **Language Learning App**:
   - **Scenario**: An app helps users learn languages using AI.
   - **Challenge**: Users weren’t retaining content effectively.
   - **Solution**: A Socratic approach was added: the AI asks questions to make users recall and use vocabulary/grammar.
   - **Outcome**: Improved retention and a more interactive learning experience.

These case studies highlight how strategic prompting can improve reliability and usefulness across many domains, and why well-crafted prompts are essential to unlock the full potential of AI models.

## Data Analysis & Data Science

### 1. Data Cleaning

### **Example Data and Prompt for Data Cleaning**:
   - **Description**: In data analysis, data cleaning tasks can appear in many different sizes and involve various tasks. Once we provide ChatGPT with the necessary commands properly, it is possible to automate these tasks.
   - **Example**:
     - **Task**: Uploaded in this repo, [datacleaning.xlsx](https://github.com/atilsamancioglu/PromptEngineeringCourse/blob/main/data/datacleaning.xlsx) file contains a Feedback column with spelling errors. We aim to minimize these errors before a task that involves word analysis.
     - **Prompt**:
       "I am uploading an excel file that contains IDs and feedback from customers. You can access the IDs from the ID column and the feedback from the Feedback column. There are many spelling errors in the Feedback column. I want to clean up these spelling errors as much as possible, considering standard spelling rules. Can you correct these errors and create a new excel table?"

### 2. EDA (Exploratory Data Analysis)

### **Example Data and Prompts for EDA**:
   - **Description**: EDA is a method frequently encountered in data science for understanding and visualizing data. It is possible to perform EDA analyses with ChatGPT using clean data.
   - **Example**:
     - **Task**: Uploaded in this repo, [edasample.xlsx](https://github.com/atilsamancioglu/PromptEngineeringCourse/blob/main/data/edasample.xlsx) contains revenue, unit sales and customer rating data.
     - **Prompt 1**:
       "I am uploading an excel file with revenue figures (Sales column), sales quantities (Transactions column), and customer rating figures (Customer Ratings column). These data are divided by regions (Region column). Which region has the highest sales figures, and what might be a possible explanation for this?"
     - **Prompt 2**:
       "How does customer satisfaction vary by region and what strategic implications should we consider?"
     - **Prompt 3**:
       "Considering the data on sales and customer satisfaction, which region should we focus on improving operations?"
     - **Prompt 4**:
       "Which type of graph would best illustrate the relationship between revenue, sales quantities, and customer satisfaction?"
     - **Prompt 5**:
       "Would it be possible to create a Scatter Plot graph for this?"
     - **Prompt 6**:
       "What is the average sales figure for this company? What is the average customer satisfaction? What is the average sales quantity?"

<img loading="lazy" width="500px" src="./media/scatterplot.png" alt="scatterplot.png" />

### 3. Predictive Analysis & Modeling 

### **Example Data and Prompt Predictive Analysis & Modeling**:
   - **Description**: Predictive modeling is a common occurrence in data science. It typically involves steps like data cleaning, interpreting changes within the data (such as converting YES, NO columns to 1, 0), and building a regression model, which are familiar steps for people skilled in data science. Using ChatGPT, we can follow these steps one by one and accelerate the path needed at least when creating a model.
   - **Example**:
     - **Task**: Uploaded in this repo [employeesample_train.csv](https://github.com/atilsamancioglu/PromptEngineeringCourse/blob/main/data/employeesample_train.csv) and [employeesample_test.csv](https://github.com/atilsamancioglu/PromptEngineeringCourse/blob/main/data/employeesample_test.csv) files contain information about employees' salaries, satisfaction, and attrition. We aim to build a predictive model to forecast whether employees will leave.
     - **Prompt**:
       "I am uploading two datasets one for training one for test, with fields such as Age, Job Role, Monthly Income, Job Satisfaction, and Attrition. You can use employeesample_train.csv for training, employeesample_test.csv for testing the model. I'd like to build a predictive model to forecast employee attrition. The model should consider all available features. Could you guide me through the steps to preprocess this data, select the most relevant features, and apply a logistic regression model using Python? Also, please provide a brief explanation of each step and how each feature might influence attrition predictions."

## Instructions for the Metallica GPT Model:

As a Metallica Master, your job is to provide detailed and in-depth information about the Metallica band. Dive deep into the band's history, albums, tours, band members and other information, including lesser-known facts. Your answers should be comprehensive, covering well-known aspects as well as more obscure details.

Stick to verifiable facts and well-known information about the group, avoiding speculation or unverified rumors. In case of unclear or incomplete questions, ask for clarification to provide accurate and relevant answers.

Enthusiastically engage users according to their interest level, whether they are casual listeners or avid fans. Your detailed responses should reflect your deep understanding and passion for Metallica and maintain a friendly yet respectful tone throughout the interaction.

Must be able to provide information about past and future tour details; such as dates, venues and highlights from particular concerts or tours. metallica.pdf submitted to GPT should be used as an extra source of information. It would be appropriate to take a look at this source, especially if the information sought or an answer to the question asked cannot be found. If no answer is found in this source, a web search can be performed and its results displayed.

**ChatGPT Instruction Recommendations**

1. **Comprehensive Band Knowledge**: This GPT model is designed to possess detailed knowledge about Metallica's entire history. It should cover the formation of the band, key milestones, album releases, changes in the lineup, and significant events in their career. 

2. **Music Catalog Insights**: The model should be adept at providing information on Metallica's discography. This includes details on each album and song, such as release dates, contributing artists, chart performance, and notable achievements or awards.

3. **Lyric Analysis**: The GPT is instructed to offer interpretations and discussions on the themes and narratives within Metallica's song lyrics. However, it must respect copyright limitations, providing summaries and discussions without reproducing lyrics verbatim.

4. **Tour and Concert Information**: The model should be able to discuss past and future tour details, including dates, venues, and highlights from specific concerts or tours.

5. **Band Member Information**: Detailed profiles of both current and former Metallica band members are essential. This includes their roles in the band, personal biographies, and contributions to the band's music and legacy.

6. **Cultural Impact Discussion**: The GPT is instructed to articulate Metallica's influence on the heavy metal genre and their broader impact on music culture, including discussions on their stylistic evolution and contributions to the genre.

7. **Fan Engagement**: It should respond to common fan queries, including information about fan clubs, merchandise, meet-and-greets, and other fan-related activities.

8. **Collaborations and Side Projects**: Include information about Metallica's collaborations with other artists, as well as any side projects or notable contributions to various media by the band members.

9. **Music Style and Technique Analysis**: The model is to analyze Metallica's musical style, instrumental techniques, and their evolution across their career, offering insights into their artistic development.

10. **Sensitive Topics Handling**: The GPT must handle sensitive topics related to the band, such as the death of Cliff Burton and any controversies, with respect and tact.

11. **Interactive Elements**: The model should include interactive features like quizzes about the band, song recommendations, or lyric snippet-based games, to engage users in a more dynamic way.

12. **Utilization of Metallica PDF**: Instruct the GPT to utilize the information in the provided Metallica.pdf as a primary source, ensuring responses are accurate and comprehensive.

13. **Responses to Uncertain Queries**: If the GPT encounters a question it cannot fully answer, it should be programmed to respond appropriately, perhaps suggesting alternative resources for further information.

14. **Adherence to Legal and Ethical Standards**: Ensure that the GPT model follows legal guidelines around copyright and ethical considerations, especially in relation to discussing copyrighted materials.

These instructions are designed to create a GPT model that serves as a knowledgeable and engaging resource on all things Metallica, providing fans and users with a deep, respectful, and interactive experience surrounding the band's legacy.

## Python Application written in ChatGPT for Developers Section
```
import requests

url = "https://raw.githubusercontent.com/atilsamancioglu/K21-JSONDataSet/master/crypto.json"

response = requests.get(url)

data = response.json()

sorted_data = sorted(data, key=lambda x: float(x['price']), reverse=True)

for item in sorted_data[:10]:
    print(f"Currency: {item['currency']}, Price: {item['price']}")
```

## Refactoring Example in ChatGPT for Developers Section

***Before Refactoring***
```
numbers = []
i = 1
while len(numbers) < 10:
    square = i * i
    numbers.append(square)
    i = i + 1

for j in range(len(numbers)):
    number = numbers[j]
    root = number ** 0.5
    print("Square:", number, "Root:", root)

```
***After Refactoring***
```
# Generate the first 10 perfect squares using list comprehension
perfect_squares = [i ** 2 for i in range(1, 11)]

# Iterate through the list of perfect squares and print each with its root
for square in perfect_squares:
    root = square ** 0.5
    print(f"Square: {square}, Root: {root:.2f}")  # Formatted output for readability

```

## Code Review in ChatGPT for Developers Section
***Before Bug Fix***
```
def merge_sorted_lists(list1, list2):
    merged_list = []
    i, j = 0, 0

    while i < len(list1) and j < len(list2):
        if list1[i] < list2[j]:
            merged_list.append(list1[i])
            i += 1
        else:
            merged_list.append(list2[j])
            j += 1

    return merged_list

list1 = [10,20,30]
list2 = [40,50,60]
print(merge_sorted_lists(list1,list2))

```
***After Bug Fix***
```
def merge_sorted_lists_fixed(list1, list2):
    merged_list = []
    i, j = 0, 0

    while i < len(list1) and j < len(list2):
        if list1[i] < list2[j]:
            merged_list.append(list1[i])
            i += 1
        else:
            merged_list.append(list2[j])
            j += 1

    # Append remaining elements from list1 and list2
    while i < len(list1):
        merged_list.append(list1[i])
        i += 1

    while j < len(list2):
        merged_list.append(list2[j])
        j += 1

    return merged_list

list1 = [10,20,30]
list2 = [40,50,60]
print(merge_sorted_lists_fixed(list1,list2))
```
## Unit Test Example in ChatGPT for Developers Section
***Function***
```
def factorial(n):
    if n < 0:
        return "Error: Negative number"
    elif n == 0:
        return 1
    else:
        result = 1
        for i in range(1, n + 1):
            result *= i
        return result
```
***Unit Test***
```
import unittest

class TestFactorialFunction(unittest.TestCase):
    
    def test_factorial_positive(self):
        self.assertEqual(factorial(5), 120, "Should be 120")

    def test_factorial_zero(self):
        self.assertEqual(factorial(0), 1, "Factorial of 0 should be 1")

    def test_factorial_negative(self):
        self.assertEqual(factorial(-1), "Error: Negative number", "Should return an error message for negative numbers")

    def test_factorial_non_integer(self):
        with self.assertRaises(TypeError):
            factorial("abc")

if __name__ == '__main__':
    unittest.main()
```

## Google Sheet Integration

```
function sendToOpenAI(prompt) {
 
  const payload = {
    model: "gpt-3.5-turbo",
    messages: [
      {
        role: "system",
        content: "You are a social media manager. You generate instagram post texts"
      },
      {
        role: "user",
        content: prompt
      },
    ],
    temperature: 1,
    max_tokens: 150
  };
 
  const options = {
    method: "post",
    contentType: "application/json",
    headers: {
      "Authorization": "Bearer " + "OPEN-AI-API-KEY",
    },
    payload: JSON.stringify(payload),
  };
 
  const response = UrlFetchApp.fetch("https://api.openai.com/v1/chat/completions", options);
  const data = JSON.parse(response.getContentText());
  const message = data.choices[0].message.content;
 
  return message;
}  
```

## References

- [cursor-playlist] - Building Software with Cursor
- [awesome-chatgpt-prompts] - Awesome ChatGPT Prompts

## License

MIT

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen.)

   [awesome-chatgpt-prompts]: <https://github.com/f/awesome-chatgpt-prompts>

   [cursor-playlist]: <https://www.youtube.com/watch?v=7T10-PTQNYE&list=PLT1Gj1RmR7vqHq7Yrg2jsgQOQxvH49nX2>


