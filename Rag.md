# Resume RAG Assistant using Gemini & ChromaDB

## Overview

This project is a Retrieval-Augmented Generation (RAG) based Resume Assistant that allows users to ask questions about a resume PDF and receive accurate answers based only on the content present in the resume.

The system:

* Extracts text from a PDF resume
* Splits the text into overlapping chunks
* Generates embeddings using Sentence Transformers
* Stores embeddings in ChromaDB
* Retrieves relevant chunks based on user queries
* Uses Google's Gemini model to generate context-aware answers

---

## Features

* PDF Resume Parsing
* Text Chunking with Overlap
* Semantic Search using Embeddings
* ChromaDB Vector Storage
* Gemini-powered Answer Generation
* CPU Compatible
* Interactive Command Line Interface

---

## Tech Stack

* Python
* Google Gemini API
* ChromaDB
* Sentence Transformers
* PDFPlumber
* PyTorch

---

## Project Workflow

1. Load Resume PDF
2. Extract Text from PDF
3. Split Text into Chunks
4. Generate Embeddings
5. Store Embeddings in ChromaDB
6. Retrieve Relevant Resume Sections
7. Send Context to Gemini
8. Generate Resume-Based Answer

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/resume-rag-assistant.git

cd resume-rag-assistant
```

### Install Dependencies

```bash
pip install pdfplumber chromadb sentence-transformers google-generativeai torch
```

---

## Configuration

Replace:

```python
genai.configure(api_key="YOUR_API_KEY")
```

with your Gemini API key.

Example:

```python
genai.configure(api_key="AIzaSyXXXXXXXXXXXX")
```

---

## Usage

Place your resume PDF in the project directory and update:

```python
pdf_path = "your_resume.pdf"
```

Run the application:

```bash
python rag.py
```

Example:

```text
Ask about the resume: What are the candidate's skills?

Answer:
Python, Machine Learning, Deep Learning, NLP...
```

---

## Example Questions

* What are the candidate's skills?
* What projects has the candidate completed?
* What certifications are mentioned?
* What is the educational background?
* What programming languages does the candidate know?
* What internships are listed?

---

## Folder Structure

```text
resume-rag-assistant/
│
├── rag.py
├── resume.pdf
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Streamlit Web Interface
* Multi-PDF Support
* Persistent ChromaDB Storage
* Resume Summarization
* Resume Comparison
* ATS Score Analysis
* Voice-Based Question Answering

---

## Sample Output

```text
📄 Extracting text from resume...
✂️ Chunking text with overlap...
🧠 Generating embeddings & storing in ChromaDB...

✅ RAG System Ready!

Ask about the resume: What projects have been completed?

💬 Answer:

The candidate has completed projects including
Retinal Disease Detection using Deep Learning,
AI Chatbot Development, and Resume RAG Assistant.
```

---

## License

This project is open-source and available under the MIT License.

## Author

Sivasathya
AI & Machine Learning Enthusiast
