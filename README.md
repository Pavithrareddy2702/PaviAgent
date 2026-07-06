# PaviAgent

**PaviAgent** is an open-source **Agentic AI Assistant** built with **Python, FastAPI, LangGraph, LangChain, Google Gemini, Tavily, ChromaDB, and SQLite**.

It supports **real-time streaming conversations**, **document uploads**, **Retrieval-Augmented Generation (RAG)**, **web search**, **conversation memory**, and a clean web interface.

---

## ✨ Features

- 🤖 Agentic AI Assistant powered by Google Gemini
- 💬 Real-time streaming responses
- 📄 Upload and chat with documents (PDF, DOCX, TXT, MD, PY, CSV)
- 📚 Retrieval-Augmented Generation (RAG) with ChromaDB
- 🌐 Web Search using Tavily
- 🧠 Long-Term Memory
- 💾 Conversation History Management
- ⚡ FastAPI-powered backend
- 🎨 Simple and responsive web interface
- 🔍 LangSmith integration for tracing and debugging

---

## 🏗️ Project Overview

PaviAgent combines modern AI technologies to build an intelligent conversational assistant.

### Core Technologies

- **FastAPI** – Backend API and web server
- **Jinja2** – Frontend template rendering
- **LangGraph** – Agent orchestration and workflow management
- **LangChain** – Tool calling, prompt management, and RAG pipeline
- **Google Gemini** – Large Language Model (LLM)
- **Tavily Search** – Real-time web search
- **ChromaDB** – Vector database for document retrieval
- **SQLite** – Conversation history and long-term memory storage

---

## 📋 Prerequisites

Make sure you have the following installed:

- Python 3.11
- pip or Conda
- Git
- Google Gemini API Key
- Tavily API Key

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Pavithrareddy2702/PaviAgent.git
```

---

## 2️⃣ Navigate to the Project Directory

```bash
cd PaviAgent
```

---

## 3️⃣ Create a Virtual Environment

Using Conda:

```bash
conda create -n paviagent python=3.11 -y
```

---

## 4️⃣ Activate the Environment

```bash
conda activate paviagent
```

---

## 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ⚙️ Environment Variables

Create a `.env` file in the project root directory.

```env
GOOGLE_API_KEY=your_google_api_key
GOOGLE_MODEL=gemini-2.5-flash

TAVILY_API_KEY=your_tavily_api_key

LANGSMITH_TRACING=true
LANGSMITH_ENDPOINT=https://api.smith.langchain.com
LANGSMITH_API_KEY=your_langsmith_api_key
LANGSMITH_PROJECT=PaviAgent
```

If you don't want LangSmith tracing, use:

```env
LANGSMITH_TRACING=false
```

---

## ▶️ Run the Application

```bash
python app.py
```

The application will be available at:

```
http://127.0.0.1:8080
```

---

## 📁 Project Structure

```text
PaviAgent/
│
├── app.py                  # FastAPI application and streaming endpoints
├── agent.py                # LangGraph agent workflow
├── database.py             # SQLite database and conversation persistence
├── rag.py                  # Document ingestion and Retrieval-Augmented Generation
├── tools.py                # Agent tools (Web Search, Calculator, Memory, RAG)
├── requirements.txt        # Project dependencies
├── .gitignore
├── README.md
│
├── templates/
│   └── index.html          # Chat interface
│
├── uploads/                # Uploaded documents
├── chroma_db/              # Chroma Vector Database
└── data/                   # SQLite database
```

---

## 🛠️ Tech Stack

- Python
- FastAPI
- LangGraph
- LangChain
- Google Gemini
- Tavily Search API
- ChromaDB
- SQLite
- Jinja2
- LangSmith

---

##  Use Cases

- AI-powered conversational assistant
- Question answering over uploaded documents
- Retrieval-Augmented Generation (RAG)
- Real-time web search
- Long-term memory for conversations
- Multi-session chat management

---
