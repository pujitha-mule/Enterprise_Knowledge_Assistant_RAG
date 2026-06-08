# Enterprise Knowledge Assistant (RAG System)

## Overview
A Retrieval-Augmented Generation (RAG) system that enables natural-language querying of PDF-based knowledge repositories.

## Features
- PDF ingestion
- Text chunking
- Embedding generation
- FAISS vector indexing
- Semantic retrieval
- Gemini-powered response generation
- Multi-document question answering

## Tech Stack
- Python
- Flask
- FAISS
- Google Gemini API
- Sentence Transformers

## Project Structure
app.py
ingest.py
rag_pipeline.py
requirements.txt
data/

## Run
1. Install dependencies
2. Add Gemini API key
3. Run `python ingest.py`
4. Run `python app.py`
