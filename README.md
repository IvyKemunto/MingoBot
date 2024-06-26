# Mingobot

Mingobot is a chatbot developed using Rasa NLU (Natural Language Understanding) and deployed on the Telegram messaging platform. It is designed to provide information and answer questions regarding Moringa School's data science program. It serves as a helpful resource for prospective students, current learners, and anyone interested in understanding the program's details. Mingobot employs natural language processing techniques to provide accurate and informative responses, making it a valuable tool for those exploring the world of data science education.

<img width="439" alt="Screenshot 2024-04-18 211555" src="https://github.com/IvyKemunto/MingoBot/assets/167242964/5a2e673a-06ff-4700-9138-ac335313f23b">


**Key Features:**
- Answers common questions about Moringa School's data science program.
- User-friendly and accessible via Telegram chat interface.

**Inspiration:**
Mingobot was created to enhance the accessibility of information about Moringa School's data science program and to make the application process more transparent and user-friendly.

## Table of Contents:

1. [Project Name and Description](#Mingobot)
2. [Installation](#Installation)
3. [Files used in the Project](#Files-used-in-the-project)
4. [Usage](#Usage)
5. [Features](#Features)
6. [Mingobot Flowchart](#Mingobot-Flowchart)
7. [Model Evaluation](#Model-Evaluation)
8. [Conclusion and Recommendation](#Conclusion-and-Recommendation)

# Installation

To get Mingobot up and running, follow these installation steps. You can deploy Mingobot on your own system or server.

### Prerequisites

Before you begin, ensure you have the following prerequisites installed on your system:

- [Python](https://www.python.org/downloads/) (Version 3.6 or higher)
- [Pip](https://pip.pypa.io/en/stable/installation/) (Python package manager)
  
 ### To install rasa and set up your environment 

- [To set up your environment](https://rasa.com/docs/rasa/installation/environment-set-up/)
- [To Install Rasa Open Source](https://rasa.com/docs/rasa/installation/installing-rasa-open-source)

# Files used in the project

## 1. domain.yml:

### Purpose:

Define how the chatbot behaves. Specify which intents it can understand, the responses it should give, and any information it needs to extract from user messages.

### Use-Case:

Customize responses, manage the chatbot's knowledge, and define how it handles different types of interactions.

## 2. nlu.yml(NLU Training Data):

### Purpose:
Train the chatbot's language understanding. Provide examples of user messages and what they mean (intents and entities) to help the chatbot understand and respond accurately.

### Use-Case:

Teach the chatbot to recognize different intents and extract important information from user input.

## 3. config.yml: 

### Purpose:

Configure the chatbot's behavior, including the language understanding pipeline and machine learning models. Set training parameters and customize how the chatbot understands language.

### Use-Case:

Customize the chatbot's language understanding, improve its performance, and adapt it to specific use cases.

## 4. endpoints.yml: 

Connect the chatbot to external services for performing actions, tracking user interactions, and integrating with other systems.

### Purpose:

Configure external services and connections. Specify how the chatbot interacts with external systems, such as action servers or user trackers.

### Use-Case:
Connect the chatbot to external services for performing actions, tracking user interactions, and integrating with other systems.

# Usage

Mingobot is designed to make it easy for users to access information about Moringa School's data science program through Telegram. You can interact with Mingobot by following these simple steps:

1. **Start a Chat with Mingobot**:

   - Open your Telegram app.
   - Search for your Mingobot by its username or display name. @myMingo_bot
   - Start a chat with Mingobot by clicking on it.

2. **Ask Questions**:

   - Once you're in a chat with Mingobot, you can start asking questions about the data science program at Moringa School. For example, you can inquire about the application process, curriculum, or any specific details you're interested in.

   - Mingobot uses natural language processing to understand your questions and provide relevant responses.

3. **Example Interactions**:

   Here are some examples of questions you can ask Mingobot:

   - "Where is Moringa located?"
   - "What are the learning modes are available?"
   - "How do I apply to Moringa School's data science program?"
   - "What career opportunities are avilable after completion of the program?"

4. **Receive Responses**:

   - Mingobot will respond to your questions with informative and helpful answers. It may also provide links or references for additional information.

5. **Continue the Conversation**:

   - Feel free to continue the conversation and ask follow-up questions. Mingobot is designed to provide a conversational experience.

Mingobot is here to assist you in getting the information you need about Moringa School's data science program. Don't hesitate to reach out and start a chat with Mingobot today!

# Features

Mingobot is equipped with several features that make it a valuable resource for users interested in Moringa School's data science program. Here are some of its key features:

1. **Question Answering**: Mingobot can answer a wide range of questions related to the data science program at Moringa School. Users can inquire about admission requirements, curriculum details, program benefits, and much more.

2. **Natural Language Processing (NLP)**: Mingobot utilizes advanced NLP techniques to understand and interpret user questions. This enables it to provide accurate and context-aware responses, making the conversation more natural and engaging.

3. **Telegram Integration**: Mingobot is integrated with the Telegram messaging platform, allowing users to access information conveniently through their Telegram accounts.

4. **User-Friendly Interface**: The chatbot provides a user-friendly chat interface, making it easy for users to initiate conversations and receive answers to their questions.

5. **Conversational Experience**: Mingobot is designed to provide a conversational experience, allowing users to ask follow-up questions and engage in informative dialogues.

6. **Informative Responses**: The chatbot provides detailed and informative responses, often including links or references to additional resources for further exploration.

7. **Availability**: Mingobot is available 24/7, ensuring that users can access information whenever it's convenient for them.

8. **Continuous Improvement**: We are committed to improving Mingobot's knowledge base and capabilities to ensure that users receive the most up-to-date and accurate information.

Mingobot's features are designed to make the process of gathering information about Moringa School's data science program as straightforward and informative as possible. Whether you're a prospective student or just curious about the program, Mingobot is here to assist you.

# Mingobot Flowchart

<img width="700" alt="Screenshot 2024-04-18 211816" src="https://github.com/IvyKemunto/MingoBot/assets/167242964/bdb40681-69a5-48c5-a069-ed9528dc8703">


This flow ensures a smooth and effective interaction between students and the MingoBot, allowing them to obtain the information they need about the data science program in a user-friendly manner.

# Model Evaluation

To give you a visual representation of Mingobot in action, here are some video demos and screenshot of how the chatbot works:

### Screenshot 1: Asking a Question

<img width="244" alt="mingobot in action" src="https://github.com/IvyKemunto/MingoBot/assets/167242964/2294e55f-8757-40dd-970b-31365c9dd203">


*Description: A user asking a question about Moringa School's data science program and Mingobot providing a detailed response to a user's question.*

### Demo: A Brief Interaction



https://github.com/IvyKemunto/MingoBot/assets/167242964/80a5fac5-ccc9-4c8a-be3a-621a7c790361

https://github.com/IvyKemunto/MingoBot/assets/167242964/ddecd240-8445-4617-9a9c-8c4978d4df15



*The above videos show user interactions with mingobot.*

# Conclusion 
Moringa School is an institution which is very big on matters of feedback. MingoBot is a solution that enhances this two-way communication channel, in a split of a second. Being readily available, to provide consistent assistance to current students, potential students, parents and other interested parties is very vital. 
Having MingoBot be easily accessible on Telegram messaging platform, enhances its usability, while continuously monitoring and improving it, to ensure that it remains relevant and effective. 
The ultimate goal is to create a chatbot that acts as a reliable, efficient, and engaging communication support tool, that will enrich the educational experience and facilitate smooth school operations.

