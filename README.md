# Jarvis

## Introduction
A high-performance AI Q&A platform built with LangChain, leveraging RAG workflows to combine local knowledge, user-uploaded files, and real-time web search. Features role-based model switching, voice input, semantic search, and safe, fast responses.

## Key Features
- **Backend & Frontend** Integration: Built with Django for a stable backend and Chainlit for an intuitive frontend interface, seamlessly connected via APIs.
- **CORS Support**: Fully configured Cross-Origin Resource Sharing to ensure secure communication.
- **LangChain Framework**: Unified management of retrieval and generation workflows, enabling fast construction of intelligent QA pipelines.
- **Complete RAG Pipeline**: Includes document processing, vector storage, and semantic retrieval for high-precision knowledge access.
- **User File Upload**: Allows users to upload files, which are automatically chunked, vectorized, and stored in a vector database for personalized knowledge retrieval.
- **Knowledge-Enhanced Answers**: Combines retrieved documents with user queries to generate context-enriched prompts, delivering accurate answers.
- **Optimized Chunking & Semantic Search**: Efficient text chunking and semantic search improve retrieval accuracy and relevance.
- **Real-Time Search**: Integrated with SerpAPI to fetch real-time web search results.
- **Structured Results**: Extracts titles, summaries, and links, formatting them into structured data.
- **Hybrid Answer Generation**: Merges local knowledge, uploaded files, and web information to provide comprehensive and precise responses.
- **Role-Based Model Switching**: Supports switching between multiple language models, each with a specific area of expertise, to provide more accurate and professional answers.
- **Response Cache**: Implements response caching to significantly speed up answers to common queries.
- **Content Filter**: Ensures generated responses are safe and free from harmful or inappropriate content.
- **Voice Input Support**: Supports voice input for natural and intuitive human-computer interaction.
