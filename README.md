 # Simple RAG Project

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using LangChain and FAISS to answer questions from a breast cancer research paper. It uses a local LLM (like `llama3.2` via Ollama) and semantic search over PDF chunks to provide concise answers.

### Features
- Loads and splits a breast cancer research PDF
- Embeds text using HuggingFace Transformers
- Stores and retrieves documents with FAISS
- Answers queries using a local LLM (`llama3.2`)
- Built for efficient question-answering over research documents

### Technologies Used
- LangChain
- HuggingFace Transformers
- FAISS
- Ollama (for llama3.2 model)
- PyPDFLoader
