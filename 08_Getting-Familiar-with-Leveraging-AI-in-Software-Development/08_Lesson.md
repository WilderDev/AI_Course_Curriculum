# Getting Familiar with Leveraging AI in Software Development

## PREVIEW

### Content

- [Lab: Building a Basic Chatbot using ChatGPT](https://author-ide.skills.network/render?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJtZF9pbnN0cnVjdGlvbnNfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lCTVNraWxsc05ldHdvcmstQUkwMjc0RU4tU2tpbGxzTmV0d29yay9sYWJzJTJGTTElMkZCdWlsZGluZ19hX0Jhc2ljX0NoYXRib3RfdXNpbmdfQ2hhdEdQVC5tZCIsInRvb2xfdHlwZSI6InRoZWlhIiwiYWRtaW4iOmZhbHNlLCJpYXQiOjE3MTE0NTkyMTJ9.pghwmaqJ8J96kwI4zycWGRiqURah2E7avqbmoIMZ0EE)
- [Video: Leveraging AI for Technical Help and Best Practices on Design Patterns and Architecture](https://d3c33hcgiwev3.cloudfront.net/9gLrtU0dSaKjijlD6TxsEg.processed/full/720p/index.mp4?Expires=1718496000&Signature=cZxAATBVS-9wkK1mEMoWWZWoorRw6Oc8g7SsieJXZjkdaqrxMfxMeMGacoFyvHGiZyQl1bPFAujkrmx-KeVKUsNlmXzap4dDt7EO1UC5R4alZFeb-uscANX9dEogtM7M8lsdtJLV2eRStyo2MAow6sbx1GnnRe656JpLAGnrnws_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
- [Video: AI for Coding and Development](https://d3c33hcgiwev3.cloudfront.net/yfNNesezRrCp-ysHyRLWrw.processed/full/720p/index.mp4?Expires=1718496000&Signature=Usv8-ItuXK2epQS4PUJDx-R6596atHzRpQxzbzkGxjYbtC0cAKiToTRkbl74wsEt-Q2vBKjQqSWC1dUv0XA3EW6ZVs~YdxwzNQqKI~Tpe97F~yaEssZH-Cyq6BjvcxlMN6QB6NDU5Ed0C7T4jijUG2t2IHhLw-G6voscx7pRA74_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
- [Lab: Generative Database Design with ChatGPT](https://author-ide.skills.network/render?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJtZF9pbnN0cnVjdGlvbnNfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lCTVNraWxsc05ldHdvcmstQUkwMjc0RU4tU2tpbGxzTmV0d29yay9sYWJzJTJGTW9kdWxlMSUyRkxhYjMlM0FHZW5lcmF0ZV9UYWJsZV9EZXNpZ25fd2l0aF9DaGF0R1BULm1kIiwidG9vbF90eXBlIjoiYWktY2xhc3Nyb29tIiwiYWRtaW4iOmZhbHNlLCJpYXQiOjE3MTE0NTkyMTR9.BJHemBGAVs42bSZwqSdGwVEWay4CYJzTA2wrQ73N8Os)
- [Lab: Getting a Solution to a Given Coding Problem]()

### What you'll learn

In this module, you will learn about the tools and models that can be used to generate code snippets, scripts, and programs. You will explore by building a basic Chatbot with ChatGPT. You will also learn how to use generative AI for design patterns, architecture, database design and getting a solution for coding problems with ChatGPT.

### Terminology & Concepts

Quantum computing: A field of computing that utilizes quantum mechanics principles to perform complex computations. It has the potential to revolutionize fields like cryptography, optimization, and simulations.

Extended Reality (XR): An umbrella term that encompasses virtual reality (VR), augmented reality (AR), and mixed reality (MR). XR technologies are expanding beyond gaming and entertainment, finding applications in training simulations and customer experiences.

## LESSON

### Part 1: Building a Basic Chatbot using ChatGPT

#### Step 1: Set Up Your Project

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

#### Step 2: Create the User Interface

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

#### Step 3: Create a JavaScript File for Chatbot Functionality

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

#### Step 4: Create an Express Server and Integrate OpenAI API

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

#### Step 5: Create OpenAI API Module

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

#### Step 6: Set Up Environment Variables

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

#### Step 7: Run Your Chatbot

1. **Start the server:**

   - Run the following command in the terminal to start your Express server:
     ```bash
     node server.js
     ```

2. **Access the chatbot:**
   - Open a web browser and navigate to `http://localhost:3000`.
   - Interact with your chatbot by typing questions in the text input and clicking the "Send" button.

### Part 2: Leveraging AI for Technical Help and Best Practices on Design Patterns and Architecture

- **Ask your new chatbot the following prompts**:

  - "Can you explain the Singleton design pattern?"
  - "What are the benefits of using the Factory pattern?"
  - "How does the Observer pattern work?"
  - "What is a microservices architecture?"

- **See if you can optimize your code by using the Factory pattern for creating instances of classes.**

### Part 3: Generative Database Design with ChatGPT

In this part, we'll explore how to leverage ChatGPT to assist in designing a robust and efficient database. By using AI, you can gain insights and guidance to optimize your database structure. Follow the steps below to learn how to interact with ChatGPT for generative database design, focusing on creating a comprehensive customer database.

#### Step 1: Initial Naive Prompt

1. **Log in to ChatGPT**:

   - Open your ChatGPT application or website and log in to your account.

2. **Enter the following naive prompt**:

   ```
   Help me design a database for a company to manage customer information.
   ```

3. **Observe the response**:
   - Note how the response is likely to be generic because the AI does not have specific details about your requirements or the database structure you envision.

#### Step 2: Refining the Prompt with Specific Requirements

1. **Start a new chat** to clear any previous instructions.
2. **Enter the following refined prompt**:

   ```
   I need to design a database for a company to manage customer information. The database should include tables for customers, locations, and purchases. Each table should have relevant fields. Can you provide a detailed design?
   ```

3. **Observe the response**:
   - The AI should provide a more detailed and structured response, outlining the key tables and fields.

#### Step 3: Asking for Table Structure

1. **Start a new chat to reset any previous settings**.
2. **In the prompt input box, enter**:

   ```
   Could you provide the structure of a database table for the company's customers, including fields like name, email, and location in a clear table format?
   ```

3. **Observe the response**:

   - The AI should provide a detailed table structure with columns and data types for the `Customers` table.

4. **Repeat for other tables**:

   - Ask for the structure of the `Locations` and `Purchases` tables.
   - Example prompt:

     ```
     Could you provide the structure of a database table for customer purchases, including fields like date of purchase, amount spent, and customer ID?
     ```

#### Step 4: Integrating Relationships Between Tables

1. **Ask about linking tables**:

   ```
   How should I link the `Purchases` table to the `Customers` table for efficient data organization and retrieval?
   ```

2. **Observe the response**:

   - The AI should provide guidance on establishing foreign keys and referential integrity between the tables.

3. **Incorporate the advice into your design**:
   - Update your database schema to include foreign keys linking `Customers` to `Locations` and `Purchases` to `Customers`.

#### Step 5: Consolidating the Database Design

1. **Start a new chat for a consolidated design**.
2. **Enter the following prompt**:

   ```
   Could you provide a consolidated table design that integrates all the discussed aspects, including the 'Customers' table with fields for name, email, and location; a separate 'Locations' table with state, country, and zip code; and a 'Purchases' table with purchase details like date and amount? How should these tables be structured and connected to ensure an efficient and organized database schema?
   ```

3. **Observe the response**:
   - The AI should provide a comprehensive and integrated database schema.

#### Step 6: Review and Experiment

1. **Review the provided schema**:

   - Ensure it meets your requirements and adjust any details as necessary.

2. **Experiment with variations**:

   - Try different prompts to refine your design further.
   - Example prompt:

     ```
     Can you suggest any optimization techniques for the database design to improve performance?
     ```

3. **Implement the suggested optimizations**.

#### Step 7: Applying AI-Generated Designs to Real Projects

1. **Implement the final database schema**:

   - Use a database management system (DBMS) like MySQL, PostgreSQL, or SQL Server to create your database.

2. **Test the database**:

   - Populate it with sample data and run queries to ensure it functions as expected.

3. **Evaluate the AI's contribution**:
   - Reflect on how the use of ChatGPT enhanced your database design process.
   - Consider the benefits and limitations of using AI for technical assistance.

### Part 4: Getting a Solution to a Given Coding Problem

In this part, we will explore how to effectively use ChatGPT to solve coding problems. By following a structured approach, you will learn how to pose questions, interpret responses, and refine your queries to obtain accurate and efficient coding solutions. This hands-on experience will enhance your problem-solving skills and demonstrate the potential of generative AI in coding tasks.

#### Step 1: Initial Prompt and Problem Statement

1. **Log in to ChatGPT**:

   - Open your ChatGPT application or website and log in to your account.

2. **Enter the initial prompt**:

   - In the Prompt Instructions field, enter the following to guide ChatGPT in providing detailed step-by-step solutions:

     ```
     Provide a comprehensive and detailed step-by-step solution to the coding problems in the Python programming language.
     ```

3. **Pose the first coding problem**:

   **Problem Statement**:

   ```
   Write a Python program to find the maximum and minimum elements in a list.
   ```

4. **Observe the response**:
   - Note the solution provided by ChatGPT and ensure it includes a clear explanation and step-by-step breakdown.

#### Step 2: Reviewing and Optimizing Code

1. **Enter a new prompt to review an existing solution**:

   **Problem Statement**:

   ```
   Verify whether the provided code can be optimized:

   def find_largest(arr):
       largest = arr[0]

       for num in arr:
           if num > largest:
               largest = num
       return largest
   ```

2. **Ask ChatGPT to optimize the code**:

   - Prompt ChatGPT with the following:

     ```
     Can you optimize the following Python function to find the largest element in an array?
     ```

3. **Observe the response**:
   - Review the optimized solution provided by ChatGPT and compare it to the original code for improvements in efficiency and readability.

#### Step 3: Developing Functions for Specific Tasks

1. **Pose a new coding problem to develop a specific function**:

   **Problem Statement**:

   ```
   Create a Python function to eliminate duplicates from a list of ten country names, sorting the result alphabetically. Provide an example input list containing duplicates to showcase the function's effectiveness.
   ```

2. **Enter the prompt**:

   - Prompt ChatGPT with the following:

     ```
     Create a Python function to eliminate duplicates from a list of ten country names, sorting the result alphabetically.
     ```

3. **Observe the response**:
   - Ensure the solution includes a function definition, example input, and a sorted output list without duplicates.

#### Step 4: Further Code Optimization

1. **Review another piece of code for optimization**:

   **Problem Statement**:

   ```
   Verify whether the provided code can be optimized:

   def remove_duplicates(nums):
       seen = set()
       unique_nums = []

       for num in nums:
           if num not in seen:
               seen.add(num)
               unique_nums.append(num)
       return unique_nums
   ```

2. **Ask ChatGPT for optimization suggestions**:

   - Prompt ChatGPT with the following:

     ```
     Can you optimize the following Python function for removing duplicates from a list?
     ```

3. **Observe the response**:
   - Review the suggestions and optimized code provided by ChatGPT, focusing on efficiency and alternative data structures.

#### Step 5: Implementing Functions for Specific Requirements

1. **Pose another coding problem to implement a specific function**:

   **Problem Statement**:

   ```
   Write a Python function using the 'append' function to identify and return a list of duplicate elements from a given list of integers. Include a sample input list with duplicates to illustrate the function's operation.
   ```

2. **Enter the prompt**:

   - Prompt ChatGPT with the following:

     ```
     Write a Python function using the 'append' function to identify and return a list of duplicate elements from a given list of integers.
     ```

3. **Observe the response**:
   - Ensure the solution includes a function definition, a sample input list, and an output list with the identified duplicates.

## REVIEW

### Summary

- In this module, you learned how to build a basic chatbot using ChatGPT and interact with it to obtain coding solutions, design patterns, and database structures.
- You explored leveraging AI for technical help, design patterns, and architecture best practices.
- You learned how to use generative AI for database design and coding problem solutions.

### Homework

1. **Practice Coding Problems**:

   - Solve additional coding problems using ChatGPT and refine your queries to obtain accurate solutions.
   - Experiment with different prompts and coding challenges to enhance your problem-solving skills.

2. **Explore Design Patterns and Architecture**:

   - Research and study various design patterns and architectural best practices.
   - Ask your chatbot for explanations and examples of different design patterns to deepen your understanding.

3. **Database Design Optimization**:
   - Experiment with generative AI for database design and optimization.
   - Use ChatGPT to suggest improvements to your existing database schema and evaluate the proposed changes.
