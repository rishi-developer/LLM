# 📧 Gmail RAG (Retrieval-Augmented Generation) Chatbot

A powerful end-to-end pipeline to fetch emails from your Gmail account, convert them into meaningful vector embeddings using HuggingFace, store them in ChromaDB, and query them through a Retrieval-Augmented Generation (RAG) system using ChatOllama. The project includes a sleek Gradio UI for interactive chat.

---

## 🚀 Features

- ✅ Gmail API authentication with OAuth2
- 📬 Email fetching and parsing
- 🧩 Chunking email content for vectorization
- 🔍 Embedding with HuggingFace (`all-MiniLM-L6-v2`)
- 🗃️ Vector storage using ChromaDB
- 🧠 LLM Query using ChatOllama
- 💬 Gradio UI for easy interaction
- 📊 Visualizations with t-SNE (2D & 3D)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

### 2. Create a Python Environment

### 3. Gmail API Setup

### 4. Authenticate and Fetch Emails


RAG Pipeline Workflow

Gmail API → Email Fetching → Chunking → Embedding → ChromaDB → Query → LLM (ChatOllama) → UI


🧪 Example Use Cases

Automatically query recent conversations

Summarize client communications

Build knowledge base from your Gmail


🤖 Technologies Used
Python

Google Gmail API

HuggingFace Transformers

LangChain

ChromaDB

ChatOllama

Gradio

t-SNE


📌 Notes

For security, never commit your credentials.json or token.pkl to GitHub.

Be mindful of Gmail API quotas.


⭐ Star the Repository
If you found this project helpful, give it a ⭐ to support it!

