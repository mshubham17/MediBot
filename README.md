# MediBot 🩺

An AI-powered Medical Assistant built using Retrieval-Augmented Generation (RAG).

MediBot retrieves relevant medical information from a curated knowledge base and generates context-aware responses using Large Language Models.

## Features

- AI-powered medical question answering
- Retrieval-Augmented Generation (RAG)
- FAISS vector database for semantic search
- Groq-hosted LLM integration
- Conversational chat interface
- Source-aware responses

## How It Works

1. Medical documents are converted into embeddings.
2. Embeddings are stored in a FAISS vector database.
3. User queries are matched against relevant document chunks.
4. Retrieved context is passed to the LLM.
5. The model generates a context-aware response.
