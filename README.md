# AI-Ethics-RAG-Explorer

A Retrieval-Augmented Generation (RAG) chatbot built using Flowise to enable accurate, context-aware question answering from custom documents.

---

## Overview

This project demonstrates how RAG enhances traditional LLMs by reducing hallucinations and improving response accuracy through external knowledge retrieval.

The chatbot processes documents, converts them into embeddings, stores them in a vector database, and retrieves relevant context to generate grounded responses.

---

## Architecture

- Document Loader (PDF)
- Text Splitter (Recursive Chunking)
- Embeddings (Google Gemini)
- Vector Store (In-Memory)
- LLM (Mistral AI)
- Conversational Retrieval QA Chain
- Memory Buffer

---

## Tech Stack

- Flowise
- Mistral AI
- Google Gemini Embeddings
- Vector Database (In-Memory)
- Node.js (for deployment)

---

## Features

- Context-aware Q&A from documents  
- Reduced hallucinations using RAG  
- Conversational memory support  
- Modular and scalable architecture  
- Easy API integration  

---

## Project Workflow

1. Upload document (PDF)
2. Split into chunks
3. Generate embeddings
4. Store in vector DB
5. Retrieve relevant chunks
6. Generate response using LLM
<img width="1809" height="867" alt="image" src="https://github.com/user-attachments/assets/52dfa4ed-72aa-4df0-b8e9-73f573a2144d" />

---

## Workflow Screenshot

![RAG Flow](./assets/rag-flow.png)

---

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/your-username/AI-Ethics-RAG-Explorer.git
cd AI-Ethics-RAG-Explorer
