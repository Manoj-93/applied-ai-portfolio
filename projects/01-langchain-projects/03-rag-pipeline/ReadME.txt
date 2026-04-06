# RAG Pipeline

This project demonstrates an end-to-end Retrieval-Augmented Generation system.

## Flow
- Load documents (PDF/Web/Text)
- Split into chunks
- Generate embeddings
- Store in vector DB (FAISS / Chroma)
- Retrieve relevant chunks
- Generate answer using LLM

## Key Insight
Retriever fetches → LLM reasons