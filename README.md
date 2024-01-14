# Prompt Engineering Course
## Atıl Samancıoğlu

This readme is created for [Prompt Engineering Course](https://udemy.com), feel free to browse it by yourself or along with the course.

# Prompt Engineering Fundamentals According to ChatGPT

1. **Be Specific**: This point is crucial. Being specific in your prompts helps to narrow down the scope and increases the accuracy of the output. You might consider adding examples to illustrate how specificity can change the response.

2. **Work in Steps**: This is an effective strategy, especially for complex tasks. It can be helpful to explain that breaking down a task into smaller, manageable parts can make it easier for the AI to understand and process the request efficiently. Including examples of how to break down a complex task could be beneficial.

3. **Iterate and Improve**: This is a key aspect of working with AI models. You could expand on this by suggesting ways to analyze and refine the outputs. Mentioning how to use follow-up questions or how to rephrase prompts for clarity and better results can be useful.

4. **Context Matters**: Emphasize the importance of providing necessary background information in prompts. This could include explaining the context in which a task is set or why certain information is relevant.

5. **Use Clear and Concise Language**: Encourage the use of straightforward language to avoid misunderstandings. Complex sentence structures or ambiguous terms can lead to less accurate responses.

6. **Feedback Loop**: Mention the importance of providing feedback to the AI, as it can help in adjusting the responses for future prompts.

7. **Examples**: Providing real-life examples for each fundamental can significantly enhance understanding. This might include both effective and ineffective prompt examples to show the do's and don'ts.

## Prompt Priming

Prompt priming is a technique used in interacting with AI language models like ChatGPT, where the initial input or "prompt" is designed to "prime" the model in a specific way. This priming sets the context or tone for the interaction, influencing how the AI responds. The aim is to guide the AI towards a particular style, format, or type of content in its responses. Here are two examples:

1. **Without Creative Writing Priming**:
   - Prompt: "Write a story about dragons and elves."
   - This prompt is much vaguer, lacking specific details about the setting, characters, and plot. As a result, the AI might produce a generic fantasy story, but it won't necessarily align with the richly detailed and specific scenario of a mystical world, a lost city of gold, and the journey of a character named Elara.

2. **Creative Writing Priming**:
   - Prompt: "Imagine a mystical world where dragons and elves coexist peacefully. In this world, there's a legend about a lost city made of gold, guarded by a wise old dragon. Write a short story about a young elf named Elara, who embarks on a quest to find this city."
   - This prompt primes ChatGPT to generate a creative story in a fantasy setting. It sets the scene, introduces characters, and suggests a plotline, guiding the AI to produce a narrative in a specific genre.
  
3. **Without Technical Explanation Priming**:
   - Prompt: "Explain machine learning."
   - This prompt is straightforward and lacks the specific instruction to tailor the explanation for high school students. The AI might provide a correct but potentially more technical or less engaging explanation, which might not be as suitable or accessible for a high school audience.   

4. **Technical Explanation Priming**:
   - Prompt: "Explain the concept of machine learning as if you are a teacher addressing a class of high school students. Use simple analogies and avoid technical jargon."
   - This prompt primes the model to provide an explanation of a complex topic (machine learning) in a simplified manner, suitable for high school students. It instructs the AI to use analogies and simple language, tailoring the response to the understanding level of the audience.

These examples illustrate how crucial prompt priming can be in guiding the AI to generate responses that are more closely aligned with the user’s specific needs and expectations.

## General Prompt Frameworks
General frameworks like the RGC (Role, Goals, Context) and others offer a structured approach to prompt crafting, ensuring that the prompts are well-rounded and effective. Let's delve into a few of these frameworks with examples:

1. **RGC Framework (Role, Goals, Context)**:
   - **Role**: Define who or what the AI is supposed to be.
   - **Goals**: Specify what you want to achieve with the prompt.
   - **Context**: Provide any necessary background information.
   - **Example**: "You are a travel advisor. I'm planning a trip to Japan for two weeks in April. My goals are to experience traditional Japanese culture and visit cherry blossom sites. What itinerary would you suggest?"
   - **Explanation**: This prompt clearly defines the AI's role (travel advisor), the goal (planning a culturally rich trip to Japan), and the context (two-week trip in April).

2. **Constraint-Led Framework**:
   - **Constraints**: Explicitly state any limitations or boundaries for the AI's response.
   - **Example**: "Write a poem about the ocean, but use only four-line stanzas and avoid using the words 'sea', 'water', or 'blue'."
   - **Explanation**: This prompt sets specific constraints (format of the poem and word limitations), guiding the AI to be more creative within these boundaries.

3. **Socratic Framework**:
   - **Goal**: To lead the AI through a series of questions and answers for deeper understanding.
   - **Example**: "Why is biodiversity important for ecosystems? Can you explain this by giving an example of a rainforest ecosystem?"
   - **Explanation**: This prompt uses the Socratic method, asking questions to encourage the AI to explore and explain the concept of biodiversity in depth.

4. **Open-Ended Exploration Framework**:
   - **Goal**: To encourage broad, imaginative, or speculative responses.
   - **Example**: "What might be some unexpected consequences of colonizing Mars?"
   - **Explanation**: This prompt invites open-ended speculation, allowing the AI to explore a wide range of possibilities without specific constraints.

5. **Skill Demonstration Framework**:
   - **Goal**: To prompt the AI to demonstrate a particular skill or capability.
   - **Example**: "As a chess instructor, provide an analysis of the famous game between Bobby Fischer and Boris Spassky in 1972, focusing on key moves and strategies."
   - **Explanation**: This prompt sets the AI in a specific role (chess instructor) and asks it to demonstrate its ability to analyze a historical chess game, focusing on detailed aspects of the game.

6. **Hypothetical Scenario Framework**:
   - **Goal**: To explore responses to hypothetical or imaginary situations.
   - **Example**: "Imagine if the internet was completely shut down for a month worldwide. How might this affect global communication and business?"
   - **Explanation**: This prompt poses a hypothetical scenario, encouraging the AI to think through and explain the possible ramifications of a significant global event.

Each of these frameworks serves a unique purpose, shaping the AI's responses to be more focused, detailed, and aligned with the user's intent. By carefully selecting and applying these frameworks, users can effectively steer the conversation and extract more meaningful and relevant information from the AI.

## Focused Prompt Frameworks

Focused Prompt Frameworks are structured approaches to crafting prompts that guide AI language models like ChatGPT towards generating more accurate, relevant, and useful responses. Each framework is designed with a specific goal or context in mind, shaping how the prompt is formulated. Here are some common frameworks with examples:

1. **Information Retrieval Framework**:
   - **Goal**: To extract specific information or facts.
   - **Example**: "What are the key differences between Python and JavaScript in terms of syntax and use-cases?"
   - **Explanation**: This prompt is designed to elicit clear, factual information about Python and JavaScript. It's specific and straightforward, focusing on 'differences', 'syntax', and 'use-cases'.

2. **Creative Generation Framework**:
   - **Goal**: To generate original, creative content.
   - **Example**: "Create a short story set in a futuristic city where technology controls nature, focusing on a protagonist who rebels against this system."
   - **Explanation**: This prompt encourages the AI to create a narrative with specific elements: a futuristic setting, a theme of technology versus nature, and a rebellious protagonist.

3. **Problem-Solving Framework**:
   - **Goal**: To find solutions or suggest strategies for a stated problem.
   - **Example**: "I'm struggling to increase engagement on my educational YouTube channel. What are some effective strategies to boost viewer interaction and retention?"
   - **Explanation**: The prompt clearly defines a problem (low engagement on an educational YouTube channel) and asks for specific solutions (strategies for boosting interaction and retention).

4. **Learning and Explanation Framework**:
   - **Goal**: To explain concepts or teach material in an understandable way.
   - **Example**: "Explain the concept of gravitational pull to a 10-year-old without using complex physics terms."
   - **Explanation**: This prompt primes the AI to break down the scientific concept of gravity into simple, age-appropriate language.

5. **Opinion and Analysis Framework**:
   - **Goal**: To generate viewpoints, critiques, or analyses on a given topic.
   - **Example**: "Analyze the impact of social media on modern communication, focusing on both its benefits and drawbacks."
   - **Explanation**: The prompt asks for a balanced analysis of a contemporary issue, prompting the AI to consider and articulate both positive and negative aspects.

6. **Instructional or How-To Framework**:
   - **Goal**: To provide step-by-step guidance or instructions.
   - **Example**: "Describe the steps involved in baking a chocolate cake for someone who has never baked before."
   - **Explanation**: This prompt is structured to elicit a detailed, beginner-friendly guide to baking a chocolate cake, focusing on clear, step-by-step instructions.

7. **Comparative Analysis Framework**:
   - **Goal**: To compare and contrast different entities or concepts.
   - **Example**: "Compare the economic policies of Keynesianism and Monetarism, highlighting their main principles and impacts on modern economies."
   - **Explanation**: This prompt is structured to elicit a detailed comparison, focusing on specific aspects like principles and impacts, of two economic theories.

8. **Historical Perspective Framework**:
   - **Goal**: To provide historical context or analyze events from a historical viewpoint.
   - **Example**: "Discuss the causes and consequences of the Industrial Revolution in Europe."
   - **Explanation**: This prompt asks for an historical analysis, focusing on both the causes and the outcomes of a major historical event.

9. **Scenario Simulation Framework**:
   - **Goal**: To explore hypothetical situations or potential future scenarios.
   - **Example**: "Imagine a scenario where renewable energy has completely replaced fossil fuels by 2050. How would this affect global economies and the environment?"
   - **Explanation**: This prompt is designed to simulate a future scenario and explore its potential impacts on various aspects of society.

10. **Personal Advice Framework**:
   - **Goal**: To provide personalized suggestions or guidance based on a specific situation.
   - **Example**: "I'm a college student majoring in computer science and feeling overwhelmed. How can I effectively manage my time and reduce stress?"
   - **Explanation**: This prompt seeks tailored advice for a specific personal situation, requiring the AI to consider the individual's circumstances.

11. **Concept Exploration Framework**:
   - **Goal**: To delve deeply into a concept or theory, exploring its nuances and implications.
   - **Example**: "Explore the concept of artificial intelligence ethics, discussing its importance and the challenges faced in implementing ethical AI."
   - **Explanation**: This prompt is aimed at a thorough exploration of a complex concept, encouraging a detailed discussion of various facets and issues.

12. **Interactive Storytelling Framework**:
   - **Goal**: To create a narrative that involves the user's input at different stages.
   - **Example**: "Start a mystery story set in an abandoned mansion. I'll tell you what choices the main character makes at key points."
   - **Explanation**: This prompt sets up an interactive storytelling experience, where the user's responses influence the direction of the story.

Each of these frameworks serves a unique purpose, and the effectiveness of the response greatly depends on how well the prompt is aligned with the chosen framework. By carefully constructing prompts according to these frameworks, you can significantly influence the quality and relevance of the AI's output.


## References

- [awesome-chatgpt-prompts] - Awesome ChatGPT Prompts


## Development

Want to contribute? Great!

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

## License

MIT

[![Academy Club](https://academyclub.co/wp-content/uploads/2021/04/academy-siyahAsset-16.png)](https://academyclub.co/)

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen.)

   [awesome-chatgpt-prompts]: <https://github.com/f/awesome-chatgpt-prompts>

