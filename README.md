# RAG-Streamlit

# 📄 Streamlit RAG App (Qwen3 + ChromaDB)

This is a Retrieval-Augmented Generation (RAG) system built with Streamlit.

## Features
- Upload PDF, DOCX, TXT
- Semantic search using BGE embeddings
- ChromaDB vector store
- Qwen3-4B LLM for grounded answers
- Multi-query retrieval
- Strict hallucination control

## Setup

```bash
git clone https://github.com/yourname/yourrepo.git
cd yourrepo
python -m venv venv
source venv/bin/activate  # windows: venv\Scripts\activate
pip install -r requirements.txt
