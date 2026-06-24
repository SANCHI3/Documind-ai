# DocuMind – AI Document Intelligence Platform

## Overview

DocuMind is an AI-powered document intelligence platform that enables users to upload PDF documents and interact with them using natural language queries.

The system uses Retrieval-Augmented Generation (RAG) to retrieve relevant document content and generate context-aware answers using Large Language Models.

## Features

* PDF Upload and Processing
* Semantic Search
* Vector Embeddings
* ChromaDB Vector Database
* Retrieval-Augmented Generation (RAG)
* FastAPI Backend
* Streamlit Frontend
* Groq LLM Integration
* Gemini Integration

## Tech Stack

* Python
* FastAPI
* Streamlit
* LangChain
* ChromaDB
* Sentence Transformers
* Groq API
* Google Gemini API

## Architecture

PDF → Chunking → Embeddings → ChromaDB → Semantic Retrieval → LLM → Response

## How to Run

### Backend

```bash
cd server
python main.py
```

### Frontend

```bash
cd client
streamlit run app.py
```

## Author

Sanchi Gangurde
