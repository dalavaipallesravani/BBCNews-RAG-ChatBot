BBC News RAG Chatbot
Overview:

The BBC News RAG Chatbot is an AI-powered question-answering system that retrieves relevant news content and generates accurate responses using a Retrieval-Augmented Generation (RAG) architecture.
The chatbot allows users to ask questions about news articles and receive context-aware answers derived from BBC News data.
This project demonstrates how modern Large Language Models (LLMs) can be combined with vector databases and document retrieval techniques to create intelligent conversational systems.

Features:

Retrieval-Augmented Generation (RAG) architecture
Context-aware answers based on BBC News articles
Document embedding and semantic search
Efficient vector similarity retrieval
Interactive question-answering interface
Scalable pipeline for news-based knowledge retrieval

Tech Stack:

Programming Language: Python
Frameworks / Libraries: LangChain, Transformers
Vector Database: Weaviate
LLM Integration: OpenAI / HuggingFace models
Data Source: BBC News Dataset

Project Architecture:

Data Collection
BBC News articles are loaded into the system.
Text Processing
Articles are cleaned and split into smaller chunks.
Embedding Generation
Each chunk is converted into vector embeddings.
Vector Storage
Embeddings are stored in a vector database.
Query Processing
User queries are embedded and matched with relevant documents.
Augmentation
The relevant documents are agumented with the query and sent to the LLM using prompt engineering techniques
Response Generation
The LLM generates answers using retrieved context.
