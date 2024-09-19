# Customer-support-agent

# Enhanced Llama 2 Chatbot with Sentiment Analysis

## Project Overview

This project implements an advanced chatbot system that combines the power of the Llama 2 language model with sentiment analysis capabilities. The chatbot is designed to provide informative responses to user queries while also adapting its behavior based on the user's emotional state.

### Key Features:

1. **Llama 2 Integration**: Utilizes the Llama 2 model from Hugging Face for generating human-like responses to a wide range of questions.

2. **Dynamic QA Dataset**: Maintains and updates a CSV file containing question-answer pairs, allowing the chatbot to learn and expand its knowledge base over time.

3. **Sentiment Analysis**: Incorporates a DistilBERT-based sentiment analysis model to detect the emotional tone of user responses.

4. **Adaptive Interaction**: Adjusts its communication style based on detected sentiment, offering empathetic responses for negative sentiment and enthusiastic engagement for positive sentiment.

5. **User-Friendly Interface**: Implements a Gradio-based chat interface for seamless interaction between users and the chatbot.

### Workflow:

1. The user initiates the conversation by asking a question.
2. The chatbot provides an answer using either the existing QA dataset or by generating a response with the Llama 2 model.
3. The user can then provide feedback or ask follow-up questions.
4. The chatbot analyzes the sentiment of the user's response and adapts its subsequent replies accordingly.

This project demonstrates the potential of combining large language models with sentiment analysis to create more empathetic and context-aware AI assistants. It has applications in various fields, including customer service, educational support, and mental health assistance.

### Technical Stack:

- Python
- Hugging Face Transformers (Llama 2 and DistilBERT models)
- Pandas for data management
- Gradio for the user interface

The modular design of this project allows for easy expansion and customization, making it a valuable starting point for developing more sophisticated AI-driven conversational systems.
