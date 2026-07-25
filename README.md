# 📕 Agentic AI Study Assistant

An AI-powered Study Assistant built using Google Gemini, RAG, ChromaDB, and Streamlit.

## 🚀 Features

- 📄 Upload PDF
- 🤖 Ask questions from the PDF
- 🧠 Memory
- 🔍 RAG (Retrieval-Augmented Generation)
- 📚 Quiz Generator
- 📅 Study Planner
- 🌐 Streamlit Web Interface

## 🛠️ Tech Stack

- Python
- Google Gemini API
- ChromaDB
- Sentence Transformers
- Streamlit
- Google Colab
- GitHub

## 📂 Project Structure

```
Agentic_AI_Study_Assistant/
│
├── Agentic_AI_Study_Assistant.ipynb
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
├── pdfs/
├── chroma_db/
└── screenshots/
```

## ▶️ How to Run

1. Install dependencies

```
pip install -r requirements.txt
```

2. Run the application

```
streamlit run app.py
```

## 📌 Project Flow

```
PDF
 ↓
Text Extraction
 ↓
Chunking
 ↓
Embeddings
 ↓
ChromaDB
 ↓
RAG
 ↓
Gemini
 ↓
Answer
```

## 👨‍💻 Author

Kishore

## 📜 License

This project is for learning and educational purposes.
