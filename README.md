 FinTech AI Document Question Answering System (RAG)

An AI-powered system that allows users to upload PDF documents and ask natural-language questions, with accurate answers generated directly from document content using Retrieval-Augmented Generation (RAG).

---

Features

- Upload and process PDF documents
- Semantic search using vector embeddings
- AI-powered question answering using local LLM (Ollama)
- Multi-document support
- Document-level filtering (query specific or all docs)
- Citation-based answers (traceable responses)
- Privacy-friendly (runs locally, no external APIs required)

---

## How It Works

1. Upload PDF
2. Text Extraction & Chunking
3. Embedding Generation (Sentence Transformers)
4. Store embeddings + metadata
5. User asks a question
6. Semantic Search retrieves relevant chunks
7. LLM (Mistral via Ollama) generates answer
8. Return answer with citations



Tech Stack

- Backend:FastAPI  
- Database:MongoDB  
- Embeddings:Sentence-Transformers (`all-MiniLM-L6-v2`)  
- Vector Search:Cosine Similarity  
- LLM:Ollama (Mistral - Local Model)  
- Language:Python  




