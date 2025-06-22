# DiagnoAI 🩺🤖

**DiagnoAI** is an AI-powered medical chatbot designed to assist with healthcare-related queries by retrieving relevant information from clinical documents. Built on a RAG (Retrieval-Augmented Generation) architecture, DiagnoAI combines the power of **Gemini 1.5 Pro** with **Pinecone vector search** for accurate and reliable medical information extraction.

---

## 🧠 Key Features

- 🩻 Ingest and process **medical PDFs** (reports, research papers, clinical notes)
- 🔍 Perform **semantic search** using vector embeddings and Pinecone
- 💬 Answer medical questions using **Gemini 1.5 Pro**
- 🧱 RAG-based architecture: **Retrieve** relevant document chunks + **Generate** responses
- 🌐 Scalable via API and cloud-based components
- 🔐 Secure and modular architecture for healthcare data

---

## ⚙️ Tech Stack

| Component         | Technology Used             |
|------------------|-----------------------------|
| Embedding Model   | `sentence-transformers` / `Instructor-XL` |
| Vector Store      | **Pinecone**                |
| Chunking          | Recursive text splitter     |
| LLM               | **Gemini 1.5 Pro (via API)**|
| Document Parsing  | `PyMuPDF`, `pdfplumber`     |
| Backend Logic     | Python (LangChain or custom RAG pipeline) |

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/DiagnoAI.git
cd DiagnoAI
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
