# RAG-Streamlit

# 📄 Streamlit RAG Application – Document Question Answering System

A production-style **Retrieval-Augmented Generation (RAG)** application that allows users to upload documents (PDF, DOCX, TXT), index them into a vector database, and interactively ask questions. The system retrieves relevant sections from the document and constrains a large language model to answer **strictly from the retrieved content**.

This project demonstrates a full modern AI pipeline: document ingestion, semantic chunking, vector search, multi-query retrieval, and grounded answer generation.

---

## 🚀 Key Features

- 📂 Upload PDF, DOCX, and TXT documents  
- 🧠 Sentence-aware hybrid chunking with overlap  
- 🔎 Semantic search using BGE embeddings  
- 🗄 Persistent ChromaDB vector store  
- 🔁 Multi-query retrieval for higher recall  
- 🤖 Qwen3-4B instruction-tuned LLM for answering  
- 🧾 Source-grounded answers with strict citation rules  
- 🌐 Interactive Streamlit web interface  

---

## 🏗 System Architecture

Document Upload
↓
Text Extraction (Unstructured)
↓
Smart Chunking (spaCy + overlap)
↓
Embeddings (BAAI/bge-small-en-v1.5)
↓
Vector Database (ChromaDB)
↓
User Question
↓
Multi-Query Expansion
↓
Semantic Retrieval
↓
Context Injection
↓
LLM Answer Generation (Qwen3-4B)




---

## ⚙️ Technologies Used

- **Streamlit** – Web application UI  
- **HuggingFace Hub** – Embeddings & LLM inference  
- **BAAI/bge-small-en-v1.5** – Text embedding model  
- **Qwen/Qwen3-4B-Instruct** – Instruction-tuned LLM  
- **ChromaDB** – Vector database  
- **Unstructured** – Document parsing  
- **spaCy** – Sentence segmentation  
- **NumPy** – Vector processing  

---

