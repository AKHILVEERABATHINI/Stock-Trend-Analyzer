# Stock Trend Analyzer

## Overview

**Stock Trend Analyzer** is a hybrid Python application that combines JupyterLab-based development and Streamlit for deployment. It enables automated ingestion, processing, and question-answering over stock-related news articles using modern language models and vector-based retrieval.

This project leverages:
- **Jupyter Notebooks** for experimentation and prototyping
- **Streamlit** for deploying an interactive web UI
- **LangChain**, **FAISS**, and **OpenAI** for NLP-based retrieval and QA

---

## Features

- URL-based news ingestion via `UnstructuredURLLoader`
- Chunking of raw text using `RecursiveCharacterTextSplitter`
- OpenAI Embeddings for vector representation
- FAISS for efficient vector search and retrieval
- Retrieval QA system with source attribution
- Streamlit interface for user-friendly interaction

---

## Environment Setup

### Prerequisites

- Python ≥ 3.8
- JupyterLab ≥ 3.x
- Streamlit ≥ 1.x
- An OpenAI API key

OPENAI_API_KEY=your-openai-api-key

Once preprocessing is complete, the app can be launched via:"streamlit run app.py
"