# Codefi's Generative AI in Software Development Workshop

## PREVIEW

### Why Learn Generative AI?

Generative AI is a powerful tool that can be used to create new, _unique_ content in a variety of formats, including text, code, images, audio, and video.

In this workshop, you will learn how to use generative AI to create code snippets, scripts, test cases, and applications that can help you become a more efficient and effective software developer.

**Here are some other reasons why learning generative AI is important**:

- Generative AI is on the minds of every leader in every organization, businesses, or governments, and with interest comes opportunity.

- Organizations are looking for people who understand the technology and most importantly, have the skills to apply it.

- Unlike many of the previous trending technologies, generative AI touches almost every role in every profession.

- Generative AI skills are expected to become important, not just for computer scientists, for everybody, which is why they will be essential as word processing, spreadsheets, even basic business literacy.

- The generative AI market is estimated to reach $1.3 Trillion by 2032.

### What You Will Learn in This Workshop

1. Identify real-world generative AI uses and describe popular generative AI models and tools for text, code, image, audio, and video
2. Explain generative AI prompt engineering concepts, examples, and common tools and learn techniques needed to create effective, impactful prompts
3. Learn about tools and techniques to generate code snippets, scripts, test cases, and applications using generative AI models

## PART 1: Introduction to Generative AI (1hr)

[Introduction to Generative AI](https://www.youtube.com/watch?v=cZaNf2rA30k)

### VOCABULARY (Generative AI)

- **Generative AI**: A type of artificial intelligence that generates new data instances that resemble the training data. It can mimic human creativity and generate new content, such as text, images, audio, and video.

  - Business can leverate generative AI to become more productive & profitable.
  - Individuals can leverate generative AI to increase productivity, add tangible value to their work, save money/time, and maximize their brand value.
  - _Examples_: Chatbots, virtual assistants, and content creation tools.

- **Discriminative AI**: A type of artificial intelligence that predicts the probability of a label given input data. It is used for classification and regression tasks.

  - Use advanced algorithms to differentiate between different classes of data, classify data, identify patterns, and draw insights.
  - _Examples_: Email spam filters, image recognition, and sentiment analysis.

- **Difference between Generative AI and Discriminative AI**: Generative AI generates new data instances, while discriminative AI predicts the probability of a label given input data.

- **Deep Learning**: A subset of machine learning that uses artificial neural networks to model complex patterns in large datasets.

  - **Artificial Neural Networks**: A computational model inspired by the human brain that consists of interconnected nodes (neurons) organized in layers.
  - **Neurons**: Basic units of computation in a neural network that receive input, apply an activation function, and produce an output.
  - _Examples_: Convolutional Neural Networks (CNNs) for image recognition and Recurrent Neural Networks (RNNs) for sequence generation.

- **Generative AI Models**: Models that generate new data instances, such as text, images, audio, and video. They can be used for creative tasks, data augmentation, and content generation.

  - **Generative Adversarial Networks (GANs)**: A type of generative AI model that consists of two neural networks, a generator and a discriminator, that compete against each other to generate realistic data instances.
  - **Variational Autoencoders (VAEs)**: A type of generative AI model that learns a low-dimensional representation of data and generates new data instances by sampling from this representation.
  - **Transformers**: A type of generative AI model that uses self-attention mechanisms to process sequences of data and generate new sequences.
  - **Diffusion Models**: A type of generative AI model that models the data generation process as a diffusion process and generates new data instances by iteratively applying noise.
  - **Foundational Models**: A type of generative AI model that serves as the basis for other models and provides pre-trained representations for downstream tasks.

- **Large Language Models (LLMs)**: A type of generative AI model that uses deep learning to generate human-like text based on a given prompt.

  - **Generative Pre-trained Transformer (GPT)**: A type of LLM developed by OpenAI that generates text based on a given prompt.

- **Applications of Generative AI**: Generative AI has diverse applications across various sectors, including natural language processing, computer vision, speech recognition, and content generation.

  - **Text Generation**: Generating human-like text for chatbots, virtual assistants, and content creation tools. (ChatGPT / Bard)
  - **Image Generation**: Creating realistic images for design, art, and entertainment applications. (DALL-E 2 / Midjourney)
  - **Audio Generation**: Generating speech, music, and sound effects for media and entertainment. (Jukebox / Lyrebird)
  - **Video Generation**: Creating videos, animations, and visual effects for film and television. (Synthesia / RunwayML)
  - **Code Generation**: Automatically generating code snippets, scripts, and applications for software development along with debugging. (Copilot / AlphaCode)
  - **Data Augmentation**: Enhancing datasets for machine learning models by generating synthetic data instances. (Augmentor / imgaug)

- **Adaptive learning**: A personalized learning approach that adjusts the pace, content, and delivery of educational materials based on individual learner needs and preferences.

- **Sentiment analysis**: The process of determining the emotional tone or sentiment expressed in text or speech, often used to analyze public opinion or customer feedback.

- **NLP (Natural Language Processing)**: A subfield of AI that focuses on the interaction between computers and human language. NLP techniques are used to process, understand, and generate human language.

- **Multimodal Models**: Models that can process and generate content in multiple modalities, such as text, images, and audio. They combine different AI techniques to generate more diverse and rich content.

### EXERCISES (Generative AI)

#### Exercise 1A: Text Generation for the Desired Context

- _In this exercise, you will prompt a generative AI chatbot to generate a desired text output and review the generative AI model's text generation capability._

1. **Step 1**: Open up the [ChatGPT](https://chat.openai.com/) tool

- Name the chat
- Choose the model
- Give the prompt instructions
- Type your message

2. **Step 2**: Convert generated text into different text formats

- Continue in the same message window from the last step
- Enter an additional prompt to change the text format (poem to story)
- Play around with different text formats

4. **Step 3**: View responses from different prompts from differnt LLMs
   - [ChatGPT](https://chat.openai.com/)
   - [Bard (Now Gemini)](https://gemini.google.com/)
   - [Claude](https://claude.ai/)
   - [Meta AI](https://www.meta.ai/)

- `Tell me a fun fact about space.`
- `Explain how a bicycle works.`
- `What are three famous poems written by William Wordsworth?`
- `Create a marketing campaign for a retail fashion brand.`
- `Help me draft a job description for the role of Instructional Designer.`
- `What is python programming?`
- ...

#### Exercise 1B: More Tools for Text Generation - ChatGPT, Jasper, Rytr, Copy.ai, and Writesonic

##### _[ChatGPT](https://chatgpt.com/)_: Use ChatGPT to generate a conversation or provide customer support responses.

1. **Step 1**: Sign up for an account on ChatGPT.
2. **Step 2**: Navigate to the chat interface.
3. **Step 3**: Start a new chat session.
4. **Step 4**: Use the following sample prompt to generate a conversation or support response:

   **Sample Prompt**:

   - `Hi ChatGPT, I need help with resetting my password for my online account. Can you guide me through the steps?`
   - `Generate a conversation between a customer and a support agent about a delayed order delivery.`
   - `Provide a response to a customer inquiry about product availability and pricing.`
   - `You have a recipe that shows 500 grams of flour, but your kitchen scale measures in ounces. You need to convert the weight of flour from grams to ounces. Convert 500 grams to ounces and provide the result based on the appropriate conversion factor.`

##### _[Jasper](https://www.jasper.ai/)_: Use Jasper to generate a marketing email.

1. **Step 1**: Sign up for an account on Jasper.
2. **Step 2**: Navigate to the "Templates" section.
3. **Step 3**: Select the "Email" template.
4. **Step 4**: Use the following sample prompt to generate a marketing email:

   **Sample Prompt**:

   - `Write a promotional email for a new fitness app that helps users track their workouts and nutrition.`

##### _[Rytr](https://rytr.me/)_: Use Rytr to generate blog post content.

1. **Step 1**: Sign up for an account on Rytr.
2. **Step 2**: Navigate to the "Create" section.
3. **Step 3**: Select the "Blog Post" option.
4. **Step 4**: Use the following sample prompt to generate blog content:

   **Sample Prompt**:

   - `Write a blog post on the benefits of adopting a plant-based diet for beginners.`

##### _[Copy.ai](https://www.copy.ai/)_: Use Copy.ai to generate product descriptions.

1. **Step 1**: Sign up for an account on Copy.ai.
2. **Step 2**: Navigate to the "Product Descriptions" section.
3. **Step 3**: Start a new project.
4. **Step 4**: Use the following sample prompt to generate product descriptions:

   **Sample Prompt**:

   - `Create a product description for a new eco-friendly water bottle that keeps beverages cold for 24 hours.`

##### _[Writesonic](https://writesonic.com/)_: Use Writesonic to generate social media posts.

1. **Step 1**: Sign up for an account on Writesonic.
2. **Step 2**: Navigate to the "Social Media" section.
3. **Step 3**: Select the type of social media post you want to create (e.g., Facebook, Twitter).
4. **Step 4**: Use the following sample prompt to generate social media content:

   **Sample Prompt**:

   - `Write a LinkedIn post announcing the launch of a new skincare line, highlighting its natural ingredients and benefits.`

#### Exercise 1C: Tools for Image Generation - Freepik, DALL-E 2, Stable Diffusion, Fotor, and Midjourney

##### _[Freepik](https://www.freepik.com/)_: Use Freepik to download and customize vector graphics.

1. **Step 1**: Sign up for an account on Freepik.
2. **Step 2**: Use the search bar to find vector graphics by entering keywords like "solar system vector" or "organic soap packaging."
3. **Step 3**: Select an appropriate vector graphic from the search results.
4. **Step 4**: Download the vector graphic and use a tool like Adobe Illustrator or another vector graphic editor to customize it as needed.

   **Sample Prompts**:

   - `Search for 'solar system vector' and customize it to include accurate depictions of the sun and the planets with a cinematic style.`
   - `Search for 'organic soap packaging vector' and customize it to create a colorful and skin-friendly design.`

##### _[DALL-E 2](https://www.openai.com/dall-e-2)_: Use DALL-E 2 to generate unique images from textual descriptions.

1. **Step 1**: Sign up for an account on DALL-E 2.
2. **Step 2**: Navigate to the image generation section.
3. **Step 3**: Enter a descriptive prompt for the image you want to generate.
4. **Step 4**: Review the generated images and select the one that best fits your needs.

   **Sample Prompts**:

   - `Create a futuristic city skyline at sunset with flying cars and neon lights.`
   - `Generate an image of a cozy, rustic kitchen with fresh bread on the counter and sunlight streaming through the window.`
   - `Design a fantasy landscape with a crystal-clear lake, towering mountains, and a magical castle in the background.`

##### _[Stable Diffusion 3](https://stability.ai/stable-diffusion)_: Use Stable Diffusion to create high-quality images from textual prompts.

1. **Step 1**: Sign up for an account on Stable Diffusion.
2. **Step 2**: Navigate to the image generation interface.
3. **Step 3**: Enter a detailed prompt for the image you want to create.
4. **Step 4**: Choose from the generated images and refine the prompt if necessary to get the desired output.

   **Sample Prompts**:

   - `Generate a high-quality image of a serene beach at dawn with gentle waves and palm trees.`
   - `Create a detailed illustration of a bustling medieval marketplace with vendors and shoppers.`
   - `Produce an image of an astronaut floating in space with Earth in the background, capturing the vastness of the universe.`

##### _[Fotor](https://www.fotor.com/)_: Use Fotor to create and edit images with AI tools.

1. **Step 1**: Sign up for an account on Fotor.
2. **Step 2**: Navigate to the AI Image Generator section.
3. **Step 3**: Enter a descriptive prompt or upload an existing image to enhance.
4. **Step 4**: Use the editing tools to customize the image to your liking.

   **Sample Prompts**:

   - `Create an artistic representation of a bustling urban street at night with colorful storefronts and streetlights.`
   - `Design packaging ideas for an eco-friendly skincare line, emphasizing natural ingredients and sustainability.`
   - `Enhance an image of a serene mountain landscape with vibrant fall foliage and a clear blue sky.`

##### _[Midjourney](https://www.midjourney.com/)_: Use Midjourney to generate artistic and imaginative images from textual descriptions.

1. **Step 1**: Sign up for an account on Midjourney and join the Discord server.
2. **Step 2**: Navigate to a channel where you can generate images (e.g., #newbies).
3. **Step 3**: Enter a detailed prompt using the `/imagine` command.
4. **Step 4**: Review the generated images and select the one that best matches your vision.

   **Sample Prompts**:

   - `/imagine Generate an image of a mystical forest with glowing plants and magical creatures.`
   - `/imagine Create a steampunk-inspired airship soaring above a Victorian-era city.`
   - `/imagine Design a futuristic sports car with sleek lines and a metallic finish, set against a modern cityscape.`

Sure! Here’s the detailed outline for using different AI audio and video generation tools, including steps and sample prompts tailored to each platform’s strengths.

#### Exercise 1D: Tools for Audio and Video Generation - Synthesia, Suno, Descript

##### _[Synthesia](https://www.synthesia.io/)_: Use Synthesia to generate AI-powered video content.

1. **Step 1**: Sign up for an account on Synthesia.
2. **Step 2**: Navigate to the video creation section.
3. **Step 3**: Choose an AI presenter and a template for your video.
4. **Step 4**: Enter your script or use a sample script to generate the video.

   **Sample Prompts**:

   - `Create a video introduction for a new online course on digital marketing, explaining the course content and learning outcomes.`
   - `Generate a video tutorial on how to set up a professional LinkedIn profile.`
   - `Produce a corporate training video on workplace safety guidelines.`

##### _[Suno](https://www.suno.ai/)_: Use Suno to generate realistic AI voiceovers and audio content.

1. **Step 1**: Sign up for an account on Suno.
2. **Step 2**: Navigate to the audio generation section.
3. **Step 3**: Enter your script or select a pre-written script.
4. **Step 4**: Choose a voice profile and generate the audio content.

   **Sample Prompts**:

   - `Create a song about the importance of mental health awareness, with a soothing and uplifting tone.`
   - `Create a heavy metal jazz fusion track for a fictional band called "Cyber Dragons."`

##### _[Descript](https://www.descript.com/)_: Use Descript to create and edit audio and video content.

1. **Step 1**: Sign up for an account on Descript.
2. **Step 2**: Upload your audio or video files to the platform.
3. **Step 3**: Use the transcription and editing tools to refine your content.
4. **Step 4**: Export the final edited version of your audio or video.

#### Exercise 1E: Tools for Code Generation - ChatGPT, GitHub Copilot, TabNine, (and Devin)

##### _[ChatGPT](https://chatgpt.com/)_: Use ChatGPT to generate code snippets, help with debugging, write documentation, and translate code into different programming languages.

**Sample Prompts**: Use the following prompts to generate code snippets, debug code, write documentation, or translate code:

- `Generate a Python code snippet that calculates the factorial of a given number.`
- `Help debug a JavaScript function that is not returning the expected output.`
- `Write documentation for a REST API endpoint that retrieves user data from a database.`
- `Translate a Java code snippet into Python for cross-platform compatibility.`

##### _[GitHub Copilot](https://copilot.github.com/)_: Use GitHub Copilot to assist with code completion, suggest code snippets, and provide context-aware code suggestions.

- This is paid software, so you may need to sign up for a subscription to access the full features. Watch a video tutorial on how to use GitHub Copilot effectively.

##### _[TabNine](https://www.tabnine.com/)_: Use TabNine to generate code completions, suggest code snippets, and provide intelligent code suggestions.

- **Step 1**: Sign up for an account on TabNine.
- **Step 2**: Install the TabNine plugin for your preferred code editor or IDE.
- **Step 3**: Start coding and use TabNine to generate code completions and suggestions.
- **Step 4**: Use the following sample prompts to test TabNine's code generation capabilities:

  - `Generate a code snippet that sorts an array of integers in ascending order using the bubble sort algorithm.`
  - `Suggest a Python function that calculates the Fibonacci sequence up to a specified number of terms.`
  - `Provide code completions for a JavaScript function that checks if a string is a palindrome.`

##### _[Devin](https://preview.devin.ai/)_: Use Devin to generate code snippets, assist with debugging, and provide code suggestions for various programming languages.

- Play around with it. Developers have a love hate relationship with it.

#### Exercise 1F: Discover Ways to Utilize Generative AI in Different Industries

1. What is generative AI and how does it differ from other types of AI?

2. Name three domains or industries where generative AI has significant applications.

3. How does generative AI benefit the IT and DevOps field? Provide at least two examples.

4. Explain how generative AI is used in the entertainment industry. Give two specific examples.

5. In what ways can generative AI transform the field of education? Provide three examples.

6. How does generative AI contribute to risk assessment and fraud detection in the banking and finance sector? Give two examples.

7. Describe two applications of generative AI in the field of medicine and healthcare.

8. How can generative AI automate tasks and streamline processes in human resources? Provide two examples.

9. What is the potential impact of generative AI on the future of work? Explain briefly.

10. Give an example of a knowledge-based work activity that could be automated using generative AI.

### QUIZ (Generative AI)

#### Question 1:

Gerative AI models can _?????_ the training data to create unique content.

1.  Draw conclusions from
2.  Differentiate between
3.  Learn from
4.  Identify patterns and classify

#### Question 2:

What does generative AI do differently than discriminative AI?

1.  Mimics the human ability to classify data
2.  Mimics the human ability to analyze data
3.  Mimics the human ability to predict data
4.  Mimics the human ability to create data

#### Question 3:

What type of generative AI capability does a large language model primarily exhibit?

1.  Text generation
2.  Audio generation
3.  Data augmentation
4.  Image generation

#### Question 4:

Using a generative AI tool, Emily wants to create an image of a zebra-striped cat with a purple hat. Identify the best prompt for this task.

1.  List cat breeds that look like zebras or have stripes.
2.  Find a zebra-striped cat that wears a purple hat.
3.  Draw an image of a zebra-striped cat with a purple hat.
4.  What’s the difference between a zebra and a cat?

#### Question 5:

Tiana is designing a game and decides to create one avatar with specific personality traits. What type of generative AI capability is Tiana using?

1.  Ability to generate dynamic films
2.  Ability to augment data
3.  Ability to synthesize images
4.  Ability to create virtual worlds

#### Question 6:

A metaverse platform with generative AI capabilities will allow you to access _?????,_ which is not possible with other generative AI tools.

1.  Synthetic images
2.  Clear and contextually relevant text
3.  Virtual avatars
4.  Augmented data sets

#### Question 7:

What input data does VideoGPT best respond to?

1.  Text prompts
2.  Video prompts
3.  AI-generated code
4.  Image prompts

#### Question 8

**What is the impact of generative AI on medical treatments?**

1. Hospital policy implementation
2. Medically literate chatbots
3. Increased development costs
4. Quicker sentiment analysis

#### Question 9

**How does generative AI empower the human resource function?**

1. Auto-detecting risky behavior
2. Creating job requisitions
3. Increasing the depth of datasets
4. Structuring custom loans

#### Question 10

**Which of the following generative AI tools is best for researching the latest news or information on any topic?**

1. ChatGPT
2. Bard
3. Jasper
4. Writesonic

#### Question 11

**Selina is struggling to put together a presentation. She asks ChatGPT, “Can you create slides on the last remaining wildflowers in the rainforest?”**

1. ChatGPT will start to translate your request into another language.
2. ChatGPT will provide a step-by-step guide on saving the rainforest.
3. ChatGPT will respond with some basic information on forest flowers.
4. ChatGPT will suggest the title, content, and visuals for slides.

#### Question 12

**Which code generation is based on the pre-trained language model OpenAI Codex tool and can help Elizabeth generate solution-based code?**

1. PolyCoder
2. GitHub Copilot
3. ChatGPT
4. Amazon CodeWhisperer

#### Question 13

**Bob wants to convert a painting into a photograph. Which generative AI capability will help him do this best?**

1. Outpainting
2. Style transfer
3. Image fusion
4. Inpainting

#### Question 14

**If you want precise control over style for manipulating specific features like a pose or facial expression, which tool here can help you do that best?**

1. DALL-E
2. Freepik
3. Stable Diffusion
4. StyleGAN

## PART 2: Introduction to Prompt Engineering (1hr)

### VOCABULARY (Prompt Engineering)

- **Prompt**: A set of instructions or questions given to an AI model to generate a response or output.

- **Prompt Engineering**: The process of designing and optimizing prompts to improve the quality and relevance of AI-generated content.

- **Instruction**: Distinct guidelines given to the model regarding the task to be executed.

- **Context**: Establishes the circumstances that form the setting of the instruction and provides a framework for generating relevant content.

- **Input data**: Any piece of information provided as part of the prompt, which can be used as a reference for the generative model.

- **Output indicator**: Offers benchmarks for assessing the attributes of the output generated by the model, such as tone, style, length, etc.

- **Iterative Process**: A repetitive process of refining and improving prompts through multiple cycles of testing, analysis, and refinement.

- **Nuanced Responses**: Responses generated by generative AI models that have a context and depth, making them more effective and meaningful for specific tasks.

- **Model Constraints**: The limitations and weaknesses of a generative AI model, which can be understood by studying the responses to different prompts.

- **Model Security**: The measures taken to ensure the safe utilization of generative AI models and prevent the generation of harmful or misleading content.

- **Four Best Practices for Prompt Engineering**:

  - **Clarity**: Ensuring that prompts are clear, concise, and unambiguous to guide the model effectively.
  - **Context**: Providing relevant background information and context to help the model generate accurate and meaningful responses.
  - **Precision**: Being specific and detailed in the instructions to guide the model towards generating accurate and relevant content.
  - **Role Play**: Adopting different perspectives or personas to generate responses aligned with specific contexts or scenarios.

- **Prompt Engineering Tools**:

  - **IBM Watsonx.ai**: A platform of integrated tools that allows users to train, tune, deploy, and manage foundation models easily. It includes the Prompt Lab tool for experimenting with prompts based on different foundation models and building prompts based on specific needs.
  - **Spellbook**: An integrated development environment (IDE) by Scale AI that enables users to build applications based on a language model (LLM) and experiment with prompts for various use cases such as text generation, text extraction, classification, question answering, auto completion, and summarization.
  - **Dust**: A prompt engineering tool that provides a web user interface for writing prompts and chaining them together. It offers a custom coding language and standard blocks for processing the outputs provided by LLMs. Dust also supports API integration to integrate other models and services.
  - **PromptPerfect**: A tool used to optimize prompts for different LLMs or text-to-image models. It supports common text models such as GPT, Claude, StableLM, and Llama, as well as image models such as DALL-E and Stable Diffusion. PromptPerfect provides features for writing, optimizing, and refining prompts to achieve desired outputs.
  - **PromptBase**: A marketplace for prompts that supports popular generative AI tools and models, including Midjourney, ChatGPT, DALL-E, Stable Diffusion, and Llama. Users can buy prompts specific to their requirements and specific to a model or tool. PromptBase also allows users to upload and sell their own prompts on the platform.
  - **GitHub Repositories**: A collection of repositories on GitHub that provide resources, tools, and libraries for prompt engineering and working with generative AI models. These repositories include code samples, tutorials, and documentation to help users experiment with prompts and enhance the capabilities of AI models.
  - **OpenAI Playground**: An interactive platform by OpenAI that allows users to experiment with prompts and generate responses using different models. It provides a user-friendly interface for writing prompts, selecting models, and viewing the generated outputs. OpenAI Playground supports various models, including GPT-3, DALL-E, and CLIP.

- **Zero-shot Prompt**: A prompt that allows an AI model to generate a response for a task it has not been explicitly trained on.

- **Few-shot Prompt**: A prompt that enables an AI model to generate a response for a task with limited training examples.

- **Interview Pattern**: A prompt engineering approach that involves simulating a conversation or interview-style interaction with the AI model. Useful for gathering specific information and personalizing responses where the AI acts as an expert asking relevant questions.

- **Chain-of-Thought**: A prompt engineering approach that builds on the previous response generated by the AI model to create a coherent chain of prompts and responses. Useful for complex problem-solving tasks where a step-by-step reasoning process is required.

- **Tree-of-Thought**: A prompt engineering approach that branches out the prompts and responses into a tree-like structure to explore different paths of conversation. Useful for complex and multi-faceted topics where multiple perspectives are required.

- **Task specification**: A technique where text prompts explicitly specify the objective to the LLM, increasing the accuracy of responses.

- **Domain expertise**: The use of domain-specific terminology in text prompts to improve the accuracy and precision of LLM-generated content in specialized fields.

- **Bias mitigation**: A technique where text prompts provide explicit instructions to LLMs to generate neutral responses, addressing potential biases in the model's output.

- **Framing**: A technique where text prompts guide LLMs to generate responses within required boundaries, ensuring the output aligns with specific requirements or constraints.

- **User feedback loop**: A technique where users provide feedback to text prompts, allowing for iterative refinement of the prompts based on the LLM's generated response.

- **Prompt Hacks**: Techniques or strategies that involve manipulating the prompts or inputs provided to a generative AI model, such as a large language model (LLM) or an image generation model, to produce desired or specific outputs. These hacks include carefully crafting the prompts to influence the model's behavior and generate outputs that align with the user's intentions. They improve the performance of LLMs by:

  - Improving the quality and accuracy of LLM outputs: By carefully crafting the prompt, you can guide the LLM toward the desired output and reduce the likelihood of errors.
  - Enabling LLMs to perform new and innovative tasks: By combining prompts with other inputs, such as images or code, you can enable LLMs to perform tasks that they would not be able to perform otherwise.
  - Making LLMs more accessible and user-friendly: Using prompt hacks can make it easier for people to use LLMs easily and effectively.

- **Style Modifiers**: Descriptors used to influence the artistic style or visual attributes of images produced by generative AI models. They can modify various visual elements like color, contrast, texture, shape, and size to generate aesthetically appealing and visually pleasing output.

- **Quality Boosters**: Terms used in an image prompt to enhance the visual appeal and improve the overall fidelity and sharpness of the output. They can include terms like high resolution, sharp focus, complimentary colors, and others to enhance specific features of the image.

- **Repetition**: A technique that involves emphasizing a particular visual element within an image prompt to create a sense of familiarity for the generative AI model. It helps in generating multiple images with subtle differences, resulting in a diverse set of potential outputs.

- **Weighted Terms**: Words or phrases that can have a powerful emotional or psychological impact. They can be given positive or negative weights to emphasize or de-emphasize certain emotions in the image prompt.

- **Fix Deformed Generations**: A technique used to modify any deformities or anomalies in the generated images. It involves using good negative prompts to mitigate issues like distortion, pixelation, or other image quality problems.

### EXERCISES (Prompt Engineering)

#### Exercise 2A: Go Over Good Prompt Examples

##### Prompt 1

`Write a detailed report analyzing the impact of social media on mental health among teenagers in the United States. Include statistical data on the prevalence of mental health issues, examples of harmful social media practices, and recommendations for promoting positive mental health.`

**Instructions**: Write a detailed report

**Context**: Impact of social media on mental health among teenagers in the United States

**Input Data**: Statistical data on the prevalence of mental health issues, examples of harmful social media practices

**Output Data**: Recommendations for promoting positive mental health

##### Prompt 2

`Develop a machine learning model to predict customer churn for a telecommunications company. Use historical customer data including demographics, usage patterns, and customer service interactions as input. The output should be a binary classification indicating whether a customer is likely to churn or not.`

**Instructions**: Develop a machine learning model

**Context**: Predicting customer churn for a telecommunications company

**Input Data**: Historical customer data including demographics, usage patterns, and customer service interactions

**Output Data**: Binary classification indicating likelihood of customer churn

##### Prompt 3

`Create an interactive web application that recommends personalized workout routines based on user preferences and fitness goals. The application should take input from the user regarding their fitness level, preferred workout types, and time availability. The output should be a customized workout plan with exercises, sets, and repetitions.`

**Instructions**: Create an interactive web application

**Context**: Recommending personalized workout routines

**Input Data**: User preferences, fitness level, preferred workout types, time availability

**Output Data**: Customized workout plan with exercises, sets, and repetitions

##### Prompt 4

`Design a natural language processing (NLP) model to perform sentiment analysis on customer reviews for a product. The model should take customer reviews as input and classify them into positive, negative, or neutral sentiments. The output should be the sentiment classification for each review.`

**Instructions**: Design a natural language processing (NLP) model

**Context**: Sentiment analysis on customer reviews for a product

**Input Data**: Customer reviews

**Output Data**: Sentiment classification (positive, negative, or neutral) for each review

#### Exercise 2B: Exploring Prompt Engineering w/ ChatGPT

##### Step 1: Log into ChatGPT

1. **Log into ChatGPT**: Head over to [ChatGPT](https://platform.openai.com/docs/guides/chat) and log in to your account.
2. **Set Up Your Workspace**: Create a new chat and name it "Prompt Engineering Exercise."

##### Step 2: Understand Your Task

1. **Identify the Task**: For this exercise, we will create a series of prompts to generate a short article on "The Impact of Generative AI on Modern Businesses."

##### Step 3: Design Initial Prompts

1. **Draft an Initial Prompt**: Start with a basic prompt to generate an introduction.
   - **Prompt**: "Write an introduction for an article on the impact of generative AI on modern businesses."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.

##### Step 4: Enhance Prompt Clarity

1. **Add Context for Clarity**: Make the prompt more specific to improve the coherence of the response.
   - **Prompt**: "Write an engaging introduction for an article discussing how generative AI is transforming various industries and its potential impact on business operations."
   - **Action**: Enter the refined prompt in the ChatGPT message field and click Start Chat to observe the response.

##### Step 5: Experiment with Prompt Formats

1. **Question Format**: Generate content by asking a question.
   - **Prompt**: "How is generative AI transforming modern businesses?"
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.
2. **Statement Format**: Generate content with a direct statement.
   - **Prompt**: "Discuss the ways generative AI is transforming modern businesses."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.
3. **Instruction Format**: Give a clear instruction to generate content.
   - **Prompt**: "List five ways generative AI is transforming modern businesses."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.

##### Step 6: Control Output Length

1. **Specify Length Constraints**: Create a prompt to generate content within specific length constraints.
   - **Prompt**: "Write a short paragraph (100 words) on the benefits of generative AI for modern businesses."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.

##### Step 7: Combine Prompts for Cohesion

1. **Integrate Responses**: Combine the generated responses from previous prompts to form a cohesive section of the article.
   - **Action**: Review the generated content and piece together an introduction and a list of benefits for the article on "The Impact of Generative AI on Modern Businesses."

##### Step 8: Finalize the Article

1. **Create a Conclusion**: Draft a prompt to generate a conclusion for the article.

   - **Prompt**: "Write a conclusion summarizing the key points on how generative AI is impacting modern businesses and its future potential."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.

2. **Review and Edit**: Combine all sections to form the final article and make any necessary edits for coherence and flow.

#### Exercise 2C: Naive Prompting and Persona Pattern

By now, you should have a clear understanding of the opportunity and value the new wave of conversational AI offers us. You have also learned how prompts that we provide can be adjusted or optimized to produce desired responses when conversing with an AI model.

In this lab, we'll take the so-called standard or naive approach. We'll query the AI in the simplest way possible, like most people would. The result will be alright, but we'll see how a simple adjustment can radically improve the results later in the lab. We'll tackle more complex approaches in future labs that produce even better results.

##### Step 1: Log into ChatGPT

1. **Log into ChatGPT**: Head over to [ChatGPT](https://platform.openai.com/docs/guides/chat) and log in to your account.
2. **Set Up Your Workspace**: Create a new chat and name it "Naive Prompting and Persona Pattern Exercise."

##### Step 2: The Naive Approach

1. **Identify the Task**: For this exercise, we will explore how generative AI can assist in creating a fitness plan.
2. **Draft a Naive Prompt**: Start with a simple, generic prompt to generate fitness advice.
   - **Prompt**: "What is the best way to get fit?"
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.
3. **Review the Response**: Note that the response will be generic and broad, providing basic advice on fitness.

##### Step 3: Enhance with a Persona

1. **Refine the Prompt with a Persona**: To get more detailed and specific advice, ask the AI to act as a fitness expert.
   - **Prompt**: "Acting as a fitness expert, tell me the best way to get fit."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.
2. **Review the Response**: Notice the improvement in specificity and detail compared to the naive approach.

##### Step 4: Adding Context and Specific Instructions

1. **Define the Persona and Instructions**: Enhance the persona by adding context and specific instructions in the Prompt Instructions field.
   - **Prompt Instructions**: "You will act as a fitness expert who is current with the latest research data and provide very detailed step-by-step instructions in reply to my queries."
   - **Action**: Add this in the Prompt Instructions field.
2. **Draft a Specific Query**: Now, create a specific query for the AI to respond to.
   - **Prompt**: "Create a gym workout program to lose weight and build strength for an out-of-shape beginner."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.
3. **Review the Response**: Note the detailed and structured fitness plan provided by the AI.

##### Step 5: Using a Famous Persona

1. **Introduce a Famous Persona**: To get responses with a specific style or tone, ask the AI to channel a famous person.
   - **Prompt**: "Acting as marketing expert Seth Godin, give me a list of 10 article titles to promote my new book about dog training."
   - **Action**: Enter the prompt in the ChatGPT message field and click Start Chat to observe the response.
2. **Review the Response**: Compare the creative and engaging titles generated by the AI with the previous generic ones.

##### Step 6: Experiment with Different Personas

1. **Draft a Query with Dual Personas**: Ask the AI to provide responses from two different personas to compare perspectives.
   - **Prompt**: "You'll act as a liberal political expert and as a conservative political expert and provide two answers for each question I ask."
   - **Action**: Enter this prompt and then ask a specific question.
   - **Example Question**: "Which policies should be implemented to address inflation?"
   - **Action**: Enter the question in the ChatGPT message field and click Start Chat to observe the responses.
2. **Review and Compare the Responses**: Note the differences in perspectives and how the persona influences the response.

#### Exercise 2D: Interview Pattern Approach

In this part, we'll explore how the Interview Pattern can significantly enhance the quality and specificity of AI-generated responses. We'll combine it with the Persona Pattern to get even richer, more detailed, and personalized results. We'll apply this to a practical project: creating a personalized travel itinerary. Follow the steps below to see the difference in outcomes using the Interview Pattern approach.

##### Step 1: Initial Naive Prompt

1. Log in to ChatGPT.
2. In the prompt input box, enter the following naive prompt:

   ```
   Suggest a travel itinerary for my next vacation.
   ```

3. Observe the response. Note how the suggestion is likely to be generic because the AI doesn't have specific information about your preferences or details about the vacation.

##### Step 2: Applying the Persona Pattern

1. Start a new chat to clear any previous instructions.
2. In the prompt input box, enter the following:

   ```
   Acting as a travel expert, suggest a travel itinerary for my next vacation.
   ```

3. Observe the response. The results should be more detailed and expert-driven but still somewhat generic because the AI lacks specific personal information.

##### Step 3: Introducing the Interview Pattern

1. Start a new chat to reset any previous settings.
2. In the Prompt Instructions field, enter:

   ```
   You will act as a travel expert who is current with the latest travel trends and provide very detailed step-by-step instructions in reply to my queries. You will interview me, asking me all the relevant questions necessary for you to generate the best possible answer to my queries.
   ```

3. In the prompt input box, enter:

   ```
   Suggest a travel itinerary for my next vacation.
   ```

4. Observe the response. The AI should ask a series of questions to gather specific information about your travel preferences, budget, interests, and other relevant details.

5. Answer the questions the AI asks. Provide detailed responses to help the AI generate a personalized travel itinerary.

##### Step 4: Analyzing the Results

1. Review the travel itinerary provided by the AI after it has gathered all necessary information.
2. Compare this itinerary with the one generated from the naive and persona approaches. Note the differences in specificity and personalization.

##### Step 5: Experimenting with Variations

1. To further refine the approach, start a new chat and adjust the Prompt Instructions slightly. For example:

   ```
   You will act as a travel expert and ask me a series of questions, one by one, to gather all the information you need to give a proper response.
   ```

2. Repeat the prompt:

   ```
   Suggest a travel itinerary for my next vacation.
   ```

3. Observe how slight variations in instructions might lead to different follow-up questions or improvements in the final itinerary.

##### Step 6: Expanding the Project

1. Apply the same process to a new goal. Start a new chat and enter the following Prompt Instructions:

   ```
   You will act as a culinary expert who is current with the latest cooking trends and provide very detailed step-by-step instructions in reply to my queries. You will interview me, asking me all the relevant questions necessary for you to generate the best possible answer to my queries.
   ```

2. In the prompt input box, enter:

   ```
   Give me a recipe for dinner tonight.
   ```

3. Answer the AI’s questions about your dietary preferences, ingredients you have on hand, cooking skills, etc.

4. Review the recipe provided and compare it to a naive approach where you simply asked for a dinner recipe without any interview.

#### Exercise 2E: Chain-of-Thought Approach

The Chain-of-Thought (CoT) methodology significantly enhances the cognitive performance of AI models by breaking down complex tasks into more manageable steps. By adopting this prompting strategy, AI models can demonstrate heightened cognitive abilities and offer a deeper understanding of their reasoning processes.

This approach involves teaching the model to reason about a problem through a series of related questions and solutions. We will walk through an example project to illustrate the CoT approach effectively.

##### Step 1: Understanding the Problem and Standard Approach

1. **Log into ChatGPT**: Begin by logging into ChatGPT and starting a new chat.

2. **Pose a Standard/Naive Prompt**:

   - Enter the following problem to see how the AI responds without additional guidance:

     ```
     An Italian menu has 5 items priced as follows:
     - Prosciutto $9.99
     - Pecorino $12.99
     - Calamari $13.99
     - Bruschetta $4.99
     - Carpaccio $14.99
     Assuming each food is equally filling, spend $30 for a group of people by maximizing satiety.
     ```

3. **Analyze the Response**:
   - Observe how the AI attempts to solve the problem. In most cases, the reasoning might be incorrect or overly complex, leading to an ineffective solution.

##### Step 2: Implementing the Chain-of-Thought Approach

1. **Start a New Chat**: Reset the chat to ensure a fresh start without previous context influencing the AI.

2. **Set Prompt Instructions**:

   - Enter the following prompt instructions to guide the AI’s reasoning process:

     ```
     You will be given a question and an answer that demonstrates the reasoning process. Use this as a guide to answer a related question.
     ```

3. **Provide the Chain-of-Thought Example**:

   - Enter the following question and its solution to illustrate the reasoning process:

     ```
     Q: An Italian menu has 5 items priced as follows:
     - Prosciutto $9.99
     - Pecorino $12.99
     - Calamari $13.99
     - Bruschetta $4.99
     - Carpaccio $14.99
     Assuming each food is equally filling, spend $30 for a group of people by maximizing satiety.
     A: Since each food is equally filling, maximizing our budget will require us to favor items that have a low cost-per-satiety ratio. The ratio of each food, sorted by lowest to highest, is as follows:
     - Bruschetta: $4.99
     - Prosciutto: $9.99
     - Pecorino: $12.99
     - Calamari: $13.99
     - Carpaccio: $14.99
     If we are allowed to have multiple orders of the same item, the simplest answer is doing an integer division of our $30 by the item with the lowest cost per satiety ratio, which is Bruschetta. So we get $30 div $4.99 (the cost of Bruschetta) which is 6. So the answer is an order of 6 Bruschette.
     ```

4. **Pose a Related Question**:

   - Now, ask a similar question to see if the AI can apply the same reasoning:

     ```
     Q: A store sells 4 types of aquarium fish at the following prices:
     - Guppies: $3.99
     - Goldfish: $1.99
     - Betta: $5.99
     - Angelfish: $8.99
     Spend $20 to maximize the total amount of fish.
     ```

5. **Evaluate the AI’s Response**:
   - Check if the AI applies the CoT reasoning correctly to solve the new problem.

##### Step 3: Enhancing Reasoning with Zero-Shot CoT

1. **Zero-Shot CoT Prompting**:

   - Introduce phrases to improve reasoning without prior examples:

     ```
     Let's think step by step.
     ```

2. **Pose a New Question**:

   - Ask the following question to test Zero-Shot CoT:

     ```
     A store sells three box types:
     - Small, 10L, $1.99
     - Medium, 22L, $4.99
     - Large, 38L, $5.99
     Spend $20 and maximize volume.
     ```

3. **Analyze the AI’s Response**:

   - Observe how the AI uses step-by-step reasoning to arrive at the solution.

4. **Provide Feedback and Iterate**:
   - If the AI’s response is incomplete or incorrect, give feedback such as “You have money left over. Spend it.” and “Give me the entire answer.”
   - Iterate until the AI provides a comprehensive and accurate response.

##### Step 4: Applying Chain-of-Thought to Broader Topics

1. **Set Prompt Instructions for a Broad Topic**:

   - Use the following instructions to guide the AI in exploring a complex topic:

     ```
     Consider and include the following elements in your answer:
     - Historical Space Missions
     - Moon landing and Human Achievement
     - Moon landing and impact on the Cold War
     - Satellite technology and its impact on humanity
     - Mars colonization possibilities
     - Search for extraterrestrial life
     - Space tourism prospects
     - Space debris and environmental impact
     - International Space Station collaboration
     - Advancements in rocket technology
     - Interstellar travel challenges
     - Private companies and Billionaires involvement controversy
     Let us think step by step.
     ```

2. **Pose the Broad Question**:

   - Ask the AI:

     ```
     What is space exploration?
     ```

3. **Evaluate the Comprehensive Response**:
   - Analyze how the AI integrates the various elements into a cohesive and thorough answer.

#### Exercise 2F: Tree-of-Thought Approach

The Tree-of-Thought (ToT) approach to prompt engineering enhances the reasoning capabilities of Language Learning Models (LLMs) by simulating a branching thought process. This approach mimics the way humans solve complex problems: by exploring different possibilities, evaluating intermediate steps, and backtracking when necessary. This method allows for more comprehensive and accurate problem-solving compared to traditional Chain-of-Thought (CoT) prompting.

##### Step 1: Understanding the Tree-of-Thought Approach

1. **Introduction to Tree-of-Thought (ToT) Prompting**:

   - Begin by explaining the concept of ToT prompting and how it builds on the CoT approach. Emphasize the limitations of CoT, such as its inability to try different clues, make changes to decisions, or backtrack.
   - Provide context from Yao et al.'s research (arXiv:2305.10601), highlighting the significant improvement in performance using ToT prompting. For instance, in the Game of 24, GPT-4 with CoT prompting solved only 4% of tasks, while the ToT approach achieved a success rate of 74%.

2. **Illustrative Example**:
   - Use a simple example to demonstrate the ToT approach. For instance, consider a problem where Bob moves a ball through various locations:
     - **Problem Statement**: Bob is in the living room. He walks to the kitchen, carrying a cup. He puts a ball in the cup and carries the cup to the bedroom. He turns the cup upside down, then walks to the garden. He puts the cup down in the garden, then walks to the garage. Where is the ball?
   - Compare the response of a naive model with that of a ToT-prompted model. Highlight how ToT prompting encourages the model to evaluate intermediate steps and backtrack if necessary to find the correct answer.

##### Step 2: Implementing Tree-of-Thought Prompting

1. **Prompt Design**:

   - Explain how to design prompts for ToT prompting. Start with a clear problem statement and add instructions for simulating multiple experts or thought processes.
   - Example Prompt Instructions: "Imagine three different experts are answering this question. All experts will write down 1 step of their thinking, then share it with the group. Then all experts will go on to the next step, etc. If any expert realizes they're wrong at any point, then they leave. The question is..."

2. **Applying ToT to Practical Scenarios**:
   - Demonstrate the application of ToT prompting to a practical scenario, such as creating a marketing plan for an online shoe store.
   - **Initial Prompt**: Define a marketing plan for my online store, which sells shoes.
   - **ToT Prompt Instructions**: "Imagine three different experts are answering this question. All experts will write down 1 step of their thinking, then share it with the group. Then all experts will go on to the next step, etc. If any expert realizes they're wrong at any point then they leave."
   - **Expert Responses**:
     - **Expert 1**: Step 1 - Market Research and Target Audience Identification.
     - **Expert 2**: Step 2 - Unique Selling Proposition (USP) and Product Selection.
     - **Expert 3**: Step 3 - Website Development and User Experience.
     - Continue this process until a comprehensive marketing plan is developed.

##### Step 3: Analyzing and Refining the Approach

1. **Evaluating Responses**:

   - Discuss how to evaluate the responses generated by the ToT prompting approach. Emphasize the importance of scrutinizing the reasoning behind each step and how it contributes to the final solution.
   - Provide examples of how intermediate thoughts and backtracking improve the accuracy and quality of responses.

2. **Enhancing the Prompts**:
   - Encourage experimentation with different variations of ToT prompts. Suggest trying prompts that incorporate additional roles or experts, or those that require more detailed step-by-step reasoning.
   - Example Variation: "Simulate three brilliant, logical experts collaboratively answering a question. Each one verbosely explains their thought process in real-time, considering the prior explanations of others and openly acknowledging mistakes. At each step, whenever possible, each expert refines and builds upon the thoughts of others, acknowledging their contributions. They continue until there is a definitive answer to the question. The question is..."

##### Step 4: Applying ToT to Broader Contexts

1. **Exploring Different Domains**:

   - Demonstrate the versatility of the ToT approach by applying it to various domains such as problem-solving, decision-making, and creative brainstorming.
   - Example Scenario: Developing a comprehensive strategy for a new product launch, addressing different aspects like market research, product development, marketing, and sales.

2. **Iterative Learning and Improvement**:
   - Highlight the importance of continuous learning and refinement of the ToT approach. Encourage the use of feedback and performance analysis to improve the prompting strategy.
   - Discuss how integrating real data and specific business context can enhance the effectiveness of the ToT prompting approach.

### QUIZ (Prompt Engineering)

#### Question 1

**A prompt is any input or **\_\_\_\_** that helps generative AI models produce relevant and logical responses.**

1. Trigger
2. Stimulus
3. Signal
4. Series of instructions

#### Question 2

**What is the primary purpose of refining prompts through the process of prompt engineering?**

1. To encourage prompt diversity
2. To challenge generative AI models
3. To ensure prompts align with specific goals and expectations
4. To make prompts longer and more complex

#### Question 3

**How does the streamline mode in PromptPerfect contribute to prompt optimization?**

1. By accessing prebuilt prompts as examples
2. By refining prompts step-by-step until satisfied with the output
3. By experimenting with the autocomplete feature
4. By selecting a relevant model for prompt optimization

#### Question 4

**Raechel wants to apply the process of prompt engineering to create an effective prompt for generating creative ideas for the marketing campaign of a new eco-friendly home cleaning product. Identify the best prompt for this task.**

1. Generate three creative and detailed ideas for a digital marketing campaign to promote a new eco-friendly home cleaning product. Consider the target audience, product strengths, marketing channels, and unique propositions for selling the product.
2. List the benefits of the new eco-friendly home cleaning product through campaigns organized by the company so that more and more people will be attracted to this product.
3. Give information about the price of an eco-friendly home cleaning product. This will help the customers compare the price of this product with other products available in the market and decide which one to buy.
4. Generate ideas to sell a new product in the digital market through marketing campaigns and creative ideas.

#### Question 5

**How does incorporating the persona pattern dimension enhance prompt effectiveness? Select the best option.**

1. By introducing a sense of character-driven context and perspective
2. By focusing solely on generic content without historical or fictional references
3. By increasing the number of words in the prompt
4. By including a series of questions through multiple prompts

#### Question 6

**What is the key benefit of incorporating examples within the prompt?**

1. It adds to the complexity of the prompt.
2. It helps the model understand the desired purpose.
3. It reduces the need for context.
4. It makes the prompt more concise.

#### Question 7

**Monica is a writer looking to improve her storytelling by using a large language model (LLM) for creative writing prompts. Which feature of a prompt engineering tool would be most beneficial for her to achieve this goal?**

1. Suggesting different prompt formats (like questions, dialogues, or scenarios) tailored to the preferred storytelling style (such as mystery, romance, or sci-fi)
2. Offering a library of pre-defined story beginnings designed for particular genres and themes.
3. Providing feedback for prompts based on a given input.
4. Iteratively refining prompts by adjusting them based on the initial outputs of the LLM’s story

#### Question 8

**Which of the following techniques helps text prompts guide LLMs to generate responses within specific boundaries, ensuring that the output aligns with the desired requirements?**

1. Framing
2. Bias mitigation
3. Domain expertise
4. Task specification

#### Question 9

**Which of the following prompt engineering approaches involves breaking down complex tasks into easier ones through a sequence of simpler prompts to guide the model toward the intended outcome?**

1. Chain-of-Thought
2. Cognitive building
3. Tree-of-Thoughts
4. Interview pattern

#### Question 10

**How does the interview pattern approach enhance the interaction with generative AI models?**

1. By focusing on a conventional prompting approach
2. By providing a single static prompt to the model
3. By hierarchically structuring a prompt or query
4. By promoting a back-and-forth exchange of information with the model

#### Question 11

**Imagine you are planning a business trip, and you want to use the interview pattern approach to prompt an AI model to assist you in planning your itinerary. What would be the benefit of this approach in comparison to a traditional static prompt?**

1. The model will provide a single predetermined itinerary
2. The model will ask for your preferences and adjust the itinerary accordingly
3. The model will generate a random travel plan.
4. The model will minimize the need for any user interaction

#### Question 12

**Jennifer wants to request some useful information about a complex medical condition using a large language model. Which among the following techniques should she employ on the text prompt to ensure that the generated content is relevant, accurate, and precise for this specialized field?**

1. Task specification
2. Framing
3. Domain expertise
4. Bias mitigation

#### Question 13

**Imagine you are a content developer working with LLMs, and you must ensure that the responses generated are indiscriminatory and neutral. Which among the following techniques would you employ with your text prompts to instruct the model appropriately?**

1. Few-shot prompting
2. Bias mitigation
3. Zero-shot prompting
4. Contextual guidance

#### Question 14

**Imagine you are using the Chain-of-Thought approach to teach a generative AI model how to solve a mathematical problem. What is the key component of a prompt in this approach?**

1. A prompt consists of a question and a correct answer for context.
2. A prompt includes only a question without an answer.
3. A prompt includes a list of formulae to solve the question.
4. A prompt includes a series of related questions without the correct answer.

### Part 3: Generative AI in Software Development (1hr)

### VOCABULARY (Generative AI in Software Development)

- **Natural Language Processing (NLP)**: Using computational techniques to analyze, understand, and generate human language.

- **Linguistics**: The scientific study of language and its structure, including morphology (word structure), syntax (sentence structure), and semantics (meaning).

- **Sentiment Analysis**: The process of determining the sentiment or emotion expressed in a piece of text.

- **Named Entity Recognition (NER)**: Identifying and classifying named entities (e.g., names of persons, organizations, locations) in text to predefined categories.

- **Text Classification**: The task of assigning predefined categories or labels to pieces of text.

- **Machine Translation**: Using NLP techniques to enable computers to understand and generate human languages for translation purposes.

- **Chatbots**: Computer programs that simulate human conversation, using NLP techniques to understand user queries and generate appropriate responses.

- **Conversational Agents**: Advanced chatbots that can engage in more complex conversations, using NLP techniques to understand context, handle ambiguity, and provide personalized interactions.

- **Tokenization**: The process of dividing text into similar units called tokens, which can be words, sentences, or characters.

- **Stemming**: A technique that reduces words to their base or root form, helping in standardizing words and reducing vocabulary size.

### EXERCISES (Generative AI in Software Development)

#### Exercise 3A: Popular Tools of Generative AI for Software Development

##### Step 1: Setting Up a Simple Project with ChatGPT

1. **Login to ChatGPT**

   - Visit [OpenAI ChatGPT](https://chat.openai.com/) and log in using your credentials. Familiarize yourself with the interface and explore how ChatGPT can be used for generating text.

1. **Define the Project Goal**

   - For this exercise, we will develop a simple weather forecasting app using generative AI tools to assist with various stages of development. The project goal is to create a user-friendly app that fetches weather data and displays it in a readable format.

1. **Using ChatGPT for Project Planning**
   - Prompt ChatGPT to outline a basic plan for your weather forecasting app. For example:
     - **Prompt**: "ChatGPT, can you help me outline a basic project plan for a weather forecasting app?"
     - **Expected Output**: A detailed project plan with steps like setting up the project environment, fetching weather data from an API, processing the data, and displaying it to users.

##### Step 2: Writing Code with GitHub Copilot

1. **Set Up Your Development Environment**

   - Install Visual Studio Code and the GitHub Copilot extension. Ensure your development environment is ready for writing Python code.

2. **Generate Initial Code Snippets**
   - Use GitHub Copilot to generate code snippets for fetching weather data from a public API (e.g., OpenWeatherMap).
     - **Example Task**: Write a function to fetch weather data.
     - **Prompt**: "GitHub Copilot, generate a Python function to fetch weather data from OpenWeatherMap API."
     - **Expected Output**: A function in Python that uses the requests library to fetch weather data from the API.

##### Step 3: Enhancing the App with GPT-4

1. **Improve Code Quality**

   - Use GPT-4 to review and enhance the code quality. Prompt GPT-4 to suggest improvements for better performance and readability.
     - **Prompt**: "GPT-4, can you review this Python function and suggest improvements for better performance?"
     - **Expected Output**: Refined code with suggestions for optimization and best practices.

2. **Add Error Handling**
   - Ask GPT-4 to help add robust error handling to the weather data fetching function.
     - **Prompt**: "GPT-4, how can I add error handling to this weather fetching function?"
     - **Expected Output**: Modified code with try-except blocks and proper error messages.

##### Step 4: Utilizing Watsonx.ai for Data Analysis

1. **Analyze Weather Data**

   - Use Watsonx.ai for analyzing and processing the fetched weather data. Implement functions to calculate averages, detect trends, or identify anomalies in the weather data.
     - **Prompt**: "Watsonx.ai, analyze this weather data and provide insights on temperature trends over a week."
     - **Expected Output**: Analysis of weather data showing temperature trends, averages, and anomalies.

2. **Integrate Analysis Results**
   - Integrate the analysis results into the weather app, displaying the insights to users in a clear and concise manner.
     - **Prompt**: "Watsonx.ai, provide code snippets to display temperature trends and anomalies in the weather app."
     - **Expected Output**: Code snippets for displaying analysis results in a user-friendly format.

##### Step 5: Testing and Refining with Bard/Gemini

1. **Test the App Functionality**

   - Use Bard to test the overall functionality of the weather forecasting app. Ask Bard to simulate user interactions and identify any issues.
     - **Prompt**: "Bard, test the functionality of this weather forecasting app and identify any potential issues."
     - **Expected Output**: Feedback on the app's functionality, identifying any bugs or user experience issues.

2. **Refine the User Interface**
   - Ask Bard for suggestions on improving the app's user interface and user experience.
     - **Prompt**: "Bard, how can I improve the user interface of my weather forecasting app for better user experience?"
     - **Expected Output**: Suggestions for UI/UX improvements, including layout changes, color schemes, and usability enhancements.

#### Exercise 3B: Tokenization in Generative AI

##### Step 1: Understanding Tokens

1. **Define Tokens and Token Limits**

   - **What are Tokens?** Tokens are fragments or segments of words used by AI models to process and generate text. They do not necessarily align with word boundaries and can include trailing spaces or sub-words.
   - **Token Limits:** For example, models like GPT-3.5-turbo have a token limit of 4097 tokens, shared between the input (prompt) and the output (completion). Understanding these limits is crucial for optimizing your prompts.

2. **Exploring Tokens**
   - **Token Conversion:** Understand how tokens are created and used. The AI model converts text input into tokens, processes them, and then generates an output by converting predicted tokens back into text.
   - **Example:** The word "red" can be tokenized differently based on context, such as " red" (with a leading space) or as part of a longer word.

##### Step 2: Token Tools and Counting Tokens

1. **Identify Token Tools**

   - **Interactive Tokenizer Tool:** Use the OpenAI interactive tokenizer tool to calculate the number of tokens in a given text and observe how it is broken down.
   - **Programmatic Tokenization:** For developers, Tiktoken is a fast BPE tokenizer designed for OpenAI models. Other libraries include the transformers package for Python and the gpt-3-encoder package for Node.js.

2. **Count Tokens**

   - **Steps to Count Tokens:**

     1. Identify the API endpoint you plan to call.
     2. Review the API documentation for request and response structures.
     3. Check if the API requires token-based authentication and obtain an access token if needed.
     4. Count tokens for each API call, including the access token in the request header.
     5. Track your token usage to stay within any usage limits or quotas.

   - **Example:**
     - For a GET request to `https://api.example.com/users/{userId}` with parameters `userId=123` and `includeAddress=true`:
       - The request method 'GET' counts as 1 token.
       - The query parameter 'includeAddress' and its value 'true' count as 2 tokens.
       - Total: 3 tokens.

##### Step 3: OpenAI Guidelines for Token Count

1. **Token Estimation:**

   - 1 token ≈ 4 characters in English
   - 1 token ≈ ¾ words
   - 100 tokens ≈ 75 words
   - 1-2 sentences ≈ 30 tokens
   - 1 paragraph ≈ 100 tokens
   - 1,500 words ≈ 2048 tokens

2. **Example Calculation:**
   - **Input Prompt:** "Can you provide a brief overview of the benefits of exercise?" (9 words)
     - Number of tokens ≈ 9 / 0.75 ≈ 12 tokens
   - **Output Generation:** Assuming 500 words
     - Number of tokens ≈ 500 / 0.75 ≈ 667 tokens

##### Step 4: Estimating AI Costs

1. **Calculating Costs:**

   - **Example:** For an input prompt of 12 tokens and an output of 667 tokens using GPT-3.5-turbo:
     - Cost for input: \( \frac{12}{1000} \times \$0.001 = \$0.000012 \)
     - Cost for output: \( \frac{667}{1000} \times \$0.002 = \$0.001334 \)
     - Total cost: \$0.000012 + \$0.001334 = \$0.001346

2. **Scaling Costs:**
   - **Example:** For 1000 API calls per day:
     - Daily cost: 1000 \times \$0.001346 = \$1.346
     - Monthly cost: \$1.346 \times 30 ≈ \$40.38

##### Step 5: Current Pricing of AI Models

1. **Pricing Chart:**
   - **GPT-4 Turbo:**
     - Input: \$0.01 / 1K tokens
     - Output: \$0.03 / 1K tokens
   - **GPT-4:**
     - Input: \$0.03 / 1K tokens
     - Output: \$0.06 / 1K tokens
   - **GPT-3.5-Turbo:**
     - Input: \$0.001 / 1K tokens
     - Output: \$0.002 / 1K tokens
   - **Code Interpreter:**
     - \$0.03 / session
   - **DALL·E 3:**
     - Standard: \$0.040 / image (1024×1024)
     - HD: \$0.080 / image (1024×1024)

#### Exercise 3C: OpenAI Account Setup and API Key Generation

##### Step 1: Set Up an OpenAI Account

1. **Launch the OpenAI Sign-Up Page**

   - Visit the OpenAI sign-up page by navigating to the OpenAI website. Look for the "Sign Up" option to begin the registration process.

2. **Enter Your Email Address**

   - Provide your email address in the designated field and click "Continue." You also have the option to use your Google, Microsoft, or Apple ID credentials for a quicker login.

3. **Create a Password**

   - Follow the prompts to create a strong, secure password for your new OpenAI account. After entering your password, click "Continue."

4. **Verify Your Email Address**

   - Open your email inbox and look for a verification email from OpenAI. Click the verification link in the email to confirm your registration.

5. **Complete Your Profile**

   - Fill in your personal details, including your first name, last name, and date of birth in MM/DD/YYYY format. Review the terms and conditions, then click "Agree."

6. **Access the OpenAI Dashboard**
   - Once your account setup is complete, you will be directed to the OpenAI landing page. Here, you can explore various features and tools provided by OpenAI.

##### Step 2: Generate an OpenAI/ChatGPT API Key

1. **Log In to OpenAI**

   - Access the OpenAI login page and enter your credentials to sign in to your account. Use the link provided to go directly to the API key generation page.

2. **Verify Your Phone Number**

   - To enhance account security, OpenAI requires phone number verification. Select "Verify your phone number" and choose your preferred method (SMS or WhatsApp) to receive the verification code.

3. **Enter the Verification Code**

   - Once you receive the verification code on your phone, enter it in the provided field on the OpenAI website to complete the verification process.

4. **Create a New Secret Key**

   - Navigate to the API key management section by selecting the key icon or accessing it through the provided link. Click "Create new Secret Key."

5. **Name Your API Key**

   - Assign a meaningful name to your new API key for easy identification. This could be related to the specific project or application you intend to use it for.

6. **Generate and Store Your API Key**
   - Click "Create secret Key" to generate your API key. Once the key is generated, copy it and store it securely. This is important because you will not be able to view the key again after this step. Click "Done" to finalize the process.

##### Step 3: Troubleshooting and Best Practices

1. **Handling Issues with API Key Generation**

   - If you encounter any problems while generating your API key, consider using a new email address to register a fresh OpenAI account. Repeat the steps above to generate a new API key.

2. **Securing Your API Key**
   - Ensure that your API key is stored securely. Avoid sharing it publicly or in unsecured environments. Use environment variables or secure key management services to handle API keys in your applications.

#### Exericse 3D: Utilizing OpenAI API for Generative AI Projects

##### Step 1: Accessing the OpenAI API Documentation

1. **Navigate to the OpenAI API Documentation**

   - Visit the OpenAI website and access the API documentation section. Here, you will find detailed information on how to use the API, including endpoints, request formats, and response structures.
   - Explore the various API endpoints available for different OpenAI models, such as GPT-3, GPT-4, and DALL·E.

2. **Review the API Reference**

   - Familiarize yourself with the API reference guide, which provides detailed descriptions of each endpoint, required parameters, and example requests and responses. This information will help you understand how to interact with the OpenAI API effectively.
   - Pay attention to the authentication methods, rate limits, and usage guidelines specified in the API documentation.

##### Step 2: Making API Calls with OpenAI

1. **Select the Appropriate Endpoint**

   - Choose the API endpoint that corresponds to the OpenAI model you want to interact with. For example, if you are using GPT-3 for text generation, select the appropriate endpoint for text completion tasks.
   - Review the input parameters required for the selected endpoint, such as the model ID, prompt text, and completion settings.
   - Ensure that you have the necessary permissions and access rights to use the selected endpoint.

2. **Construct the API Request**

   - Use your preferred programming language or API client to construct the API request. Include the required parameters in the request body or query string, following the format specified in the API documentation.
   - Add your API key to the request headers for authentication and authorization purposes. This key will validate your access to the OpenAI API.
   - Review the request structure and ensure that all required parameters are included and correctly formatted.

3. **Send the API Request**
   - Once you have constructed the API request, send it to the OpenAI API endpoint using your chosen method (e.g., HTTP client, SDK, or programming library).
   - Monitor the response from the API to verify that the request was successful. Check for any error messages or status codes that may indicate issues with the request.

#### Exercise 3E: Building a Basic Chatbot using ChatGPT

##### Step 1: Set Up Your Project

In this step, we will set up a Node.js project using the Express.js framework. Node.js allows us to run JavaScript on the server side, while Express.js simplifies the development of web applications.

1. **Open a terminal in VSCode:**

   - Click on "Terminal" in the top menu.
   - Select "New Terminal" from the dropdown.

2. **Create a new directory for your project and initialize it:**

   - Run the following commands in the terminal:
     ```bash
     mkdir software-dev-chatbot
     cd software-dev-chatbot
     npm init -y
     ```

3. **Install Express and OpenAI dependencies:**

   - Run the following command to install the necessary packages:
     ```bash
     npm install express openai
     ```

4. **Create a `public` directory:**
   - Run the following command to create a directory for static files:
     ```bash
     mkdir public
     ```

##### Step 2: Create the User Interface

Next, we will create an HTML file to serve as the user interface for our chatbot. This interface will include a text input for user queries, a submit button, and a section to display the chatbot's responses.

1. **Create an `index.html` file:**

   - Right-click on the `public` folder in VSCode.
   - Select "New File" and name it `index.html`.
   - Insert the following code into `index.html`:
     ```html
     <!DOCTYPE html>
     <html lang="en">
       <head>
         <meta charset="UTF-8" />
         <meta
           name="viewport"
           content="width=device-width, initial-scale=1.0"
         />
         <link rel="stylesheet" href="style.css" />
         <title>Software Dev Chatbot</title>
       </head>
       <body>
         <div class="main-container">
           <div class="chat-container">
             <div class="header">
               <img src="chat.png" alt="Logo" class="logo" />
               <h2 class="name">Chat Window</h2>
             </div>
             <div class="chat-log" id="chat-log"></div>
             <div class="input-container">
               <input
                 type="text"
                 id="user-input"
                 placeholder="Ask me anything..."
               />
               <button onclick="sendMessage()">Send</button>
             </div>
           </div>
         </div>
         <script src="main.js"></script>
       </body>
     </html>
     ```

2. **Create a `style.css` file:**
   - Right-click on the `public` folder in VSCode.
   - Select "New File" and name it `style.css`.
   - Insert the following code into `style.css`:
     ```css
     .chat-container {
       max-width: 600px;
       margin: 20px auto;
       border-radius: 10px;
       box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
       overflow: hidden;
       display: flex;
       flex-direction: column;
       justify-content: space-between;
       height: 80vh;
       position: relative;
       background: linear-gradient(to bottom, #1e5799, #2989d8);
     }
     .logo {
       width: auto;
       height: 50px;
       margin-left: 10px;
       margin-top: 10px;
       margin-bottom: 10px;
       border-radius: 50px;
     }
     .name {
       font-size: 20px;
       font-weight: bold;
       margin: 10px;
       color: #fff;
       margin-left: 10px;
       margin-right: 10px;
     }
     .chat-window {
       flex-grow: 1;
       display: flex;
       flex-direction: column;
       align-items: flex-end;
       padding: 20px;
       background-color: #fff;
       overflow-y: auto;
     }
     .input-container {
       display: flex;
       align-items: center;
       padding: 20px;
       background-color: #fff;
     }
     input[type='text'] {
       width: 100%;
       padding: 10px;
       border: none;
       border-radius: 5px;
       outline: none;
       font-size: 16px;
       box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
     }
     .chat-log {
       height: 400px;
       padding: 20px;
       overflow-y: auto;
       background-color: rgba(255, 255, 255, 0.8);
     }
     /* Added space between user prompts */
     .chat-log p {
       margin: 10px 0;
     }
     .input-container input[type='text'] {
       flex: 1;
       height: 40px;
       padding: 5px 10px;
       border: 1px solid #ccc;
       border-radius: 5px;
       font-size: 16px;
       outline: none;
     }
     .input-container button {
       margin-left: 10px;
       padding: 8px 16px;
       border: none;
       border-radius: 5px;
       background-color: #4caf50;
       color: #fff;
       font-size: 16px;
       cursor: pointer;
     }
     .input-container button:hover {
       background-color: #45a049;
     }
     html,
     body {
       margin: 0;
       padding: 0;
       font-family: Arial, sans-serif;
     }
     ```

##### Step 3: Create a JavaScript File for Chatbot Functionality

Now, we will create a JavaScript file to handle user input, make API requests, and display the chatbot's responses.

1. **Create a `main.js` file:**

   - Right-click on the `public` folder in VSCode.
   - Select "New File" and name it `main.js`.
   - Insert the following code into `main.js`:

     ```javascript
     const chatLog = document.getElementById('chat-log');
     const userInput = document.getElementById('user-input');

     function sendMessage() {
       const message = userInput.value;
       // Display user's message
       displayMessage('user', message);
       // Call OpenAI API to get chatbot's response
       getChatbotResponse(message);
       // Clear user input
       userInput.value = '';
     }

     function displayMessage(sender, message) {
       const messageElement = document.createElement('div');
       messageElement.classList.add('message', sender);
       // Wrap the message in a <p> tag
       const messageParagraph = document.createElement('p');
       messageParagraph.innerText = message;
       // Append the <p> tag to the message element
       messageElement.appendChild(messageParagraph);
       chatLog.appendChild(messageElement);
     }

     function getChatbotResponse(userMessage) {
       // Make a request to your server with the user's message
       fetch('/getChatbotResponse', {
         method: 'POST',
         headers: {
           'Content-Type': 'application/json',
         },
         body: JSON.stringify({ userMessage }),
       })
         .then((response) => response.json())
         .then((data) => {
           // Display chatbot's response
           displayMessage('chatbot', data.chatbotResponse);
         })
         .catch((error) => console.error('Error:', error));
     }
     ```

##### Step 4: Create an Express Server and Integrate OpenAI API

In this step, we will set up an Express.js server to manage API requests and integrate with the OpenAI API.

1. **Create a `server.js` file:**

   - Create a new file named `server.js` in the root directory of your project (`software-dev-chatbot`).
   - Insert the following code into `server.js`:

     ```javascript
     process.env['NODE_TLS_REJECT_UNAUTHORIZED'] = 0;
     const express = require('express');
     const path = require('path');
     const { OpenAIAPI } = require('./openai');
     const app = express();
     const port = process.env.PORT || 3000;

     app.use(express.static(path.join(__dirname, 'public')));
     app.use(express.json());

     app.get('/', (req, res) => {
       res.sendFile(path.join(__dirname, 'public', 'index.html'));
     });

     app.post('/getChatbotResponse', async (req, res) => {
       const userMessage = req.body.userMessage;
       // Use OpenAI API to generate a response
       const chatbotResponse = await OpenAIAPI.generateResponse(userMessage);
       // Send the response back to the client
       res.json({ chatbotResponse });
     });

     app.listen(port, () => {
       console.log(`Server is running on port ${port}`);
     });
     ```

##### Step 5: Create OpenAI API Module

We will now create a module to handle the communication with the OpenAI API.

1. **Create an `openai.js` file:**

   - Create a new file named `openai.js` in the root directory of your project (`software-dev-chatbot`).
   - Insert the following code into `openai.js`:

     ```javascript
     class OpenAIAPI {
       static async generateResponse(userMessage, conversationHistory = []) {
         const apiKey = process.env.OPENAI_API_KEY;
         const endpoint =
           'https://api.openai.com/v1/engines/davinci-codex/completions';

         const requestData = {
           prompt: `User: ${userMessage}\nChatbot:`,
           max_tokens: 150,
           temperature: 0.7,
           top_p: 1.0,
           frequency_penalty: 0.0,
           presence_penalty: 0.6,
           stop: ['User:', 'Chatbot:'],
         };

         try {
           const response = await fetch(endpoint, {
             method: 'POST',
             headers: {
               'Content-Type': 'application/json',
               Authorization: `Bearer ${apiKey}`,
             },
             body: JSON.stringify(requestData),
           });

           if (!response.ok) {
             throw new Error(`Error: ${response.statusText}`);
           }

           const data = await response.json();
           return data.choices[0].text.trim();
         } catch (error) {
           console.error('Error fetching data from OpenAI:', error);
           return 'Sorry, I am having trouble responding at the moment. Please try again later.';
         }
       }
     }

     module.exports = { OpenAIAPI };
     ```

##### Step 6: Set Up Environment Variables

We will set up environment variables to securely store our OpenAI API key.

1. **Create a `.env` file:**

   - Create a new file named `.env` in the root directory of your project (`software-dev-chatbot`).
   - Insert the following line into `.env` (replace `YOUR_OPENAI_API_KEY` with your actual OpenAI API key):
     ```env
     OPENAI_API_KEY=YOUR_OPENAI_API_KEY
     ```

2. **Install `dotenv` package:**

   - Run the following command in the terminal to install the `dotenv` package:
     ```bash
     npm install dotenv
     ```

3. **Load environment variables in `server.js`:**
   - Add the following line at the beginning of `server.js` to load environment variables:
     ```javascript
     require('dotenv').config();
     ```

##### Step 7: Run Your Chatbot

1. **Start the server:**

   - Run the following command in the terminal to start your Express server:
     ```bash
     node server.js
     ```

2. **Access the chatbot:**
   - Open a web browser and navigate to `http://localhost:3000`.
   - Interact with your chatbot by typing questions in the text input and clicking the "Send" button.

## REVIEW

### Summary

- **Generative AI** refers to AI models that can generate new content, such as text, images, audio, and video, based on the input provided to them.
- **Generative AI models** like GPT-3, DALL·E, and Sona have been developed by OpenAI to perform various generative tasks.
- **Prompt engineering** is the process of crafting effective prompts to guide generative AI models in producing desired outputs.
- **Tokenization** is the process of dividing text into smaller units called tokens, which are used by AI models for processing and generating text.
- **APIs** like the OpenAI API allow developers to interact with generative AI models and integrate them into their applications.
- **Conversational AI / Chatbots** combines NLP techniques with generative AI to create advanced chatbots capable of engaging in complex conversations.
- **Generative AI in software development** can be used for tasks like code generation, documentation, and chatbot development.

### Homework

1. Explore different generative AI models and tools for text, image, audio, video, and code generation.
2. Experiment with generating text using generative AI models and observe the output for different prompts.
3. Research the applications of generative AI in various sectors and industries and identify potential use cases for your work or projects.
