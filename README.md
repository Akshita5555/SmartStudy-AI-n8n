# SmartStudy AI – Student Assistant

An AI-powered student assistant built using **n8n and Google Gemini** to help students understand academic concepts and prepare for exams.

## Features
- AI-powered academic question answering
- Simple explanations of technical concepts
- Support for DBMS, DAA, Machine Learning, C++ and Web Technology
- Chat-based interaction
- Conversation memory support

## Tech Stack
- n8n – Workflow automation
- Google Gemini – AI language model
- Simple Memory – Conversation context

## Workflow
1. Student sends a question through the chat.
2. The n8n Chat Trigger receives the message.
3. The AI Agent processes the question using Google Gemini.
4. The assistant generates a response.
5. The response is displayed in the chat.

## Setup
1. Import the workflow JSON file into n8n.
2. Configure your Google Gemini credentials.
3. Connect the chat trigger, AI Agent, language model and memory.
4. Test the workflow with an academic question.
5. Publish the workflow to make the hosted chat available.

## Example Questions
- Explain DBMS normalization with an example.
- What is dynamic programming in DAA?
- Explain overfitting in Machine Learning.
- Explain OOP concepts in C++.

## Future Improvements
- Add quiz generation.
- Add exam revision notes.
- Integrate a question bank.
- Improve error handling and response formatting.

## Author
Akshita Choudhary

## Disclaimer
This project is for educational purposes. Configure API credentials securely and never publish secret keys in the repository.
