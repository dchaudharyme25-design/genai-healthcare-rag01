# genai-healthcare-rag01
A GenAI healthcare Q&amp;A system that answers questions from medical documents using Retrieval-Augmented Generation (RAG) to avoid hallucination.
# 🏥 GenAI Healthcare RAG System

This project is a GenAI-based Question Answering system for healthcare documents.

## Features
- Reads healthcare PDF documents
- Uses Retrieval-Augmented Generation (RAG)
- FAISS-based semantic search
- Open-source LLM (FLAN-T5)
- Streamlit-based user interface
- Avoids hallucination by answering only from documents

## Tech Stack
- Python
- Sentence Transformers
- FAISS
- HuggingFace Transformers
- Streamlit

## How to Run
```bash 
pip install -r requirements.txt
streamlit run src/ui.py

