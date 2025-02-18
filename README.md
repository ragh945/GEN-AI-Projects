# Project: Enhanced Q&A ChatBot
## Project Description
- The Enhanced Q&A ChatBot is an interactive AI-powered chatbot built using Streamlit and OpenAI's GPT models. It enables users to ask questions and receive intelligent, context-aware responses. The chatbot is designed to enhance user engagement with a customizable interface, allowing selection of OpenAI models, response tuning via temperature and max token settings, and secure API key handling.
This chatbot can be used in various applications, such as customer support, research assistants, and general knowledge Q&A.

## Main Features
- User-friendly interface with Streamlit for easy interaction.
- Multiple OpenAI models support (gpt-4o, gpt-4-turbo, gpt-4, DALL-E).
- Customizable response parameters (temperature & max_tokens).
- Secure API Key input via the Streamlit sidebar.
- LangSmith tracking enabled for monitoring performance.
- Dynamic prompt engineering using ChatPromptTemplate.
- Efficient response generation with LangChain's ChatOpenAI and StrOutputParser.

## Requirements
## 1. System Requirements
- Python 3.8+
## Internet connection (for API calls)
- OpenAI API Key
## 2. Libraries Used
- Library	Purpose
- streamlit	For creating the web-based UI
- openai	For calling OpenAI's GPT models
- langchain_openai	For integrating LangChain with OpenAI models
- langchain_core	For prompt templates and response parsing
- dotenv	For managing API keys securely
- os	For setting environment variables

## To install all dependencies, use:
- bash
- Copy
- Edit
- pip install streamlit openai langchain-openai langchain-core python-dotenv

## Main Aim of the Project
The main objective of this project is to develop a customizable, interactive, and AI-powered chatbot that:
- Provides relevant and concise answers to user queries.
- Offers model selection for diverse use cases (e.g., GPT-4o for chat, DALL-E for image generation).
- Allows users to fine-tune responses using temperature and max token settings.
- Enables secure and seamless API key input for user authentication.
- Uses LangChain and OpenAI to improve AI-assisted Q&A interactions.
- This chatbot is ideal for developers, researchers, students, and businesses looking to integrate AI-powered conversational agents into their applications.

Deployment Screenshot : ![image](https://github.com/user-attachments/assets/0bb4d6db-1a5f-4108-b4c7-975ee8adec88)


# Project: AI-Powered Research Assistant (RAG) 📄
## Project Description
- The AI-Powered Research Assistant leverages Retrieval-Augmented Generation (RAG) to provide intelligent responses based on research papers. It integrates Groq’s LLM, OpenAI/Hugging Face embeddings, FAISS vector storage, and ChromaDB to efficiently retrieve and summarize information from uploaded PDFs.

## Main Features
- PDF Document Processing: Loads and splits research papers for efficient retrieval.
- Vector Database: Uses FAISS for semantic search and embeddings.
- Groq LLM Integration: Leverages Gemma2-9B-IT for response generation.
- Efficient Retrieval Chain: Combines document retrieval and answer generation.
- Real-Time Response: Measures query execution time for optimization.

## Libraries Used
- streamlit - Web interface
- langchain - LLM and retrieval chains
- PyPDFDirectoryLoader - PDF loading
- FAISS - Vector storage
- OpenAIEmbeddings & HuggingFaceEmbeddings - Text embeddings
- Chroma - Alternative vector DB
- dotenv - Environment variable management

## Objective
To create an AI-powered assistant that extracts, retrieves, and summarizes key insights from research papers, enabling faster and more efficient academic exploration. 

## Deployment Screenshot : ![image](https://github.com/user-attachments/assets/93a853e5-2555-4512-8700-dbab6dab92af)

# Conversational RAG Q&A Chatbot with Chat History
## Project Description
- This Conversational RAG Chatbot allows users to upload PDFs and interact with their content through an AI-powered question-answering system. It integrates GROQ’s LLM, FAISS vector storage, and OpenAI embeddings while maintaining a chat history for context-aware responses.

## Main Features
- PDF Upload & Processing: Extracts and splits text from uploaded research papers.
- Retrieval-Augmented Generation (RAG): Uses FAISS for document retrieval.
- Contextual Question Understanding: Reformulates queries based on chat history.
- Conversational Memory: Maintains session-based chat history.
- Efficient & Accurate Responses: Generates concise, context-aware answers.

## Libraries Used
- streamlit - Web-based UI
- langchain - LLM integration & retrieval chains
- PyPDFLoader - PDF processing
- FAISS - Vector database
- OpenAIEmbeddings - Text embeddings
- ChatGroq - LLM processing
- dotenv - Environment management

## Objective
To create an AI chatbot that retrieves, understands, and responds to questions based on uploaded PDFs while preserving message history for enhanced user experience.

## Deployment Screenshot : ![image](https://github.com/user-attachments/assets/03f077e4-1a71-474a-9722-0b3698cb7cf6)


