# AI-Engineering-GenAI-RAG-Medical

An end-to-end AI-Engineering demo showcasing Retrieval-Augmented Generation (RAG) over medical guidance documents, powered by GenAI.

## 🚀 Project Overview

This repository demonstrates how to build a complete RAG pipeline in Python:

1. **Data Ingestion**  
   Download and parse the EMA Bioanalytical Method Validation guideline PDF.

2. **Embedding & Indexing**  
   • Use a local HuggingFace embedder (`all-MiniLM-L6-v2`) and FAISS to vectorize and index the document.  
   • (Can optionally swap to OpenAI embeddings for higher semantic fidelity.)

3. **Generation**  
   Wire up a GPT-3.5-turbo “ChatGPT” LLM via OpenAI’s API to answer user questions, grounded in your indexed text.

4. **Interactive UI**  
   Launch a Gradio‐based chat interface—with conversation history—that anyone can use via a public share link.
