# Machine Learning RAG Assistant

## Overview
A Retrieval-Augmented Generation (RAG) based assistant that answers Machine Learning questions using provided course materials.

## Data Used
- Machine Learning lecture PDFs
- Selected educational websites related to ML concepts

##Architecture
- RAG

## Models & Technologies Used
- **LLM:** Qwen2.5-7B-Instruct
- **Embedding Model:** sentence-transformers/all-MiniLM-L6-v2
- **Vector Database:** FAISS
- **Framework:** LangChain
- **Interface:** Streamlit

## Authentication
- HuggingFace authentication was used to access the language model.

## Pipeline
Documents → Chunking → Embeddings → FAISS Retrieval → Qwen Response

## Features
- Source-based answers
- Conversation memory
- Multiple answer modes (Student, Simple, Exam, Detailed)
- Hallucination control