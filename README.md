# Enterprise Knowledge Assistant (RAG System)

A Retrieval-Augmented Generation (RAG) system that enables natural-language querying of PDF-based knowledge repositories using semantic search, vector retrieval, and Large Language Models (LLMs).

## Overview

Enterprise Knowledge Assistant is designed to help users efficiently retrieve information from large collections of documents. Instead of manually searching through PDFs, users can ask questions in natural language and receive context-aware answers generated using retrieved document content.

The system combines document ingestion, intelligent chunking, embedding generation, FAISS vector search, and Gemini-powered response generation to deliver accurate and relevant answers while reducing hallucinations.

---

## Features

- PDF document ingestion and processing
- Intelligent document chunking
- Embedding generation for semantic understanding
- FAISS-based vector indexing and similarity search
- Retrieval-Augmented Generation (RAG)
- Context-aware response generation using Gemini API
- Multi-document knowledge retrieval
- Knowledge extraction and summarization
- Natural language question answering

---

## Architecture

```text
PDF Documents
      │
      ▼
Text Extraction
      │
      ▼
Document Chunking
      │
      ▼
Embedding Generation
      │
      ▼
FAISS Vector Index
      │
      ▼
User Query
      │
      ▼
Query Embedding
      │
      ▼
Similarity Search
      │
      ▼
Relevant Chunks
      │
      ▼
Gemini API
      │
      ▼
Generated Response
```

## Tech Stack

### Programming Language
- Python

### Backend
- Flask
- REST APIs

### AI & NLP
- Gemini API
- Sentence Transformers
- Embeddings
- Semantic Search
- Retrieval-Augmented Generation (RAG)

### Vector Database
- FAISS

### Document Processing
- PyPDF

---

## Project Workflow

1. Upload PDF documents into the system.
2. Extract text from uploaded documents.
3. Split text into meaningful chunks.
4. Generate embeddings for each chunk.
5. Store embeddings in a FAISS vector index.
6. Convert user query into embeddings.
7. Perform semantic similarity search.
8. Retrieve the most relevant document chunks.
9. Provide retrieved context to Gemini.
10. Generate a context-grounded response.

---

## Key Concepts Implemented

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Embeddings
- Similarity Search
- Prompt Engineering
- Context Grounding
- Hallucination Reduction
- Knowledge Retrieval

---

## Challenges Addressed

- Retrieving relevant information from large document collections.
- Reducing hallucinations in LLM-generated responses.
- Improving search accuracy beyond keyword matching.
- Efficient vector-based retrieval using FAISS.
- Handling multi-document knowledge repositories.

---

## Future Improvements

- Multi-document reasoning
- Hybrid Search (Keyword + Semantic Search)
- Conversation Memory
- AI Agent Integration
- Multi-modal Document Support
- Cloud Deployment using AWS
- pgvector Support
- User Authentication and Role-Based Access

---

## Installation

```bash
git clone https://github.com/pujitha-mule/Enterprise_Knowledge_Assistant_RAG.git

cd Enterprise_Knowledge_Assistant_RAG

pip install -r requirements.txt
```

## Run Application

```bash
python ingest.py
python app.py
```

---

## Resume Highlights

- Developed a Retrieval-Augmented Generation (RAG) system enabling natural-language querying of PDF-based knowledge repositories.
- Implemented document ingestion, intelligent chunking, embedding generation, vector indexing, and semantic retrieval using FAISS.
- Integrated Gemini API to generate context-grounded responses and reduce hallucinations through retrieval-based prompting.
- Designed scalable document-processing workflows supporting knowledge extraction, summarization, and question-answering across multiple documents.

---

## Author

**Pujitha Mule**

Computer Science Undergraduate  
Generative AI | AI Agents | Intelligent Applications
