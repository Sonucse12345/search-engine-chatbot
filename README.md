# Building AI Chatbot using Tavily, Qwen model for real-time

Problem Statement
This project focuses on building a comprehensive AI chatbot using Tavily Search Engine for real-time, accurate web searches and Qwen Model for generating responses based on those searches. The goal is to create an AI assistant that can efficiently search for relevant information and provide detailed, meaningful answers to diverse user queries.

Features
Real-time Search: Utilizes the Tavily Search Engine to perform real-time searches based on user queries.

Contextual Responses: Integrates relevant information retrieved from search results to provide contextually accurate and helpful responses.

Qwen Model Integration: Leverages the Qwen Model for generating responses based on the retrieved web context.

Conversational AI: Provides a conversational interface where users can interact with the chatbot and receive detailed responses.

No Repetition: The AI assistant avoids repeating answers, delivering a single, concise response for each query.

Technologies Used
Tavily Search Engine: A search tool that retrieves relevant web results to provide context to the chatbot.

Qwen Model: A large-scale AI language model for generating human-like responses based on the provided context.

Python: The main programming language used to implement the chatbot.

Requests Library: For making HTTP requests to interact with Tavily Search and other APIs.

Transformers Library: To work with Qwen Model for generating responses.

Prerequisites
Before running this project, make sure you have Python 3.x and the following libraries installed:
torch
transformers
requests
langchain_tavily

git clone https://github.com/your-repository-url.git
cd your-project-directory
pip install -r requirements.txt
