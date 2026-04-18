# RAG AI Agent (PDF-Based Question Answering System)

An AI-powered Retrieval-Augmented Generation (RAG) system that allows users to upload PDF documents and ask questions, receiving accurate and context-aware answers based on the document content.

---

## Overview

This project implements a complete RAG pipeline where PDF documents are converted into text, split into chunks, embedded into vectors, and used to generate accurate answers using AI.

---

## Features

* PDF to text conversion
* Intelligent text chunking
* Semantic search using embeddings
* AI-powered answer generation
* React-based frontend
* Modular architecture

---

## Project Structure

.
├── App.jsx
├── main.jsx
├── index.html
├── styles.css
├── pdf_to_text.py
├── chunking.py
├── embed_store.py
├── rag_answer.py
├── generate_sample_pdf.py
├── requirements.txt
├── package.json
├── README.md

---

## How It Works

PDF → Text → Chunks → Embeddings → Vector Search → LLM → Answer

1. Convert PDF into text
2. Split text into chunks
3. Generate embeddings
4. Store embeddings
5. Retrieve relevant chunks
6. Generate final answer

---

## Tech Stack

Backend:

* Python
* OpenAI API
* FAISS / Vector DB

Frontend:

* React.js
* HTML, CSS

---

## Installation

1. Clone the repository
   git clone https://github.com/your-username/rag-ai-agent.git
   cd rag-ai-agent

2. Install backend dependencies
   pip install -r requirements.txt

3. Install frontend dependencies
   npm install

---

## Environment Setup

Create a .env file and add:
OPENAI_API_KEY=your_api_key_here

---

## Usage

Run the following commands step by step:

python pdf_to_text.py
python chunking.py
python embed_store.py
python rag_answer.py

To start frontend:
npm run dev

---

## Example

Input: What is the main topic of the document?

Output: The document discusses key insights extracted from the uploaded PDF.

---

## Use Cases

* Student study assistant
* PDF Q&A system
* Business document analysis
* Developer documentation assistant

---

## Future Enhancements

* Chat memory
* Multi-PDF support
* Drag & drop upload
* Improved UI
* Cloud deployment

---

## Contributing

Feel free to fork and improve the project.

---

## License

MIT License

---

## Author

T R Pavithra
