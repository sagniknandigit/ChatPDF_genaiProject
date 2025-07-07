# 🤖 ChatPDF – Chat with Any PDF using GenAI

Upload PDF documents, ask questions, extract information, and summarize content using powerful AI models — all in one lightweight Python app.

> Works with Hugging Face transformers, FastAPI, and PyMuPDF. Minimal setup. Clear results. Easily extendable.

---

## 🚀 Features

- 📄 Upload and extract text from any PDF using PyMuPDF
- 🧠 Summarize content using BART model (`facebook/bart-large-cnn`)
- 💬 Ask questions with context using DistilBERT QA model
- ⚡ FastAPI backend with Swagger docs
- ✅ Jupyter notebook included for quick experimentation
- 💻 Streamlit version (UI) coming soon

---

## 📁 Project Structure

ChatPDF_genaiProject/
├── main.py # FastAPI app
├── pdfquery.py # Helper for PDF text and Q&A
├── Gemini_ChatPDF.ipynb # Notebook using Gemini API
├── requirements.txt # Python dependencies
├── LICENSE
└── README.md
