# Local AI Agent With RAG

Build a **Local AI Agent with Python**, using **Ollama**, **LangChain**, and **RAG (Retrieval‑Augmented Generation)**.

This project lets you run a smart AI assistant entirely **locally** — no cloud API keys needed. It connects:
- a local LLM (Ollama)
- a vector store (Chroma)
- Python RAG workflow

so you can query over documents or datasets and get helpful answers.

---

## 🚀 Features

- 🧠 Uses **local LLMs with Ollama** for private inference
- 🔍 Adds RAG — AI can search and reason over your data
- 📚 Uses **vector embeddings** (via Chroma) for retrieval
- 🐍 Entirely Python‑based, easy to customize

---

## 📦 Requirements

You’ll need:

- Python 3.10+
- Ollama installed and running
  - Pull a local model (like a lightweight one)  
    ```bash
    ollama pull (model_name, e.x llama3.2:1b)
    ```
  - Pull a embed model (like a lightweight one)  
    ```bash
    ollama pull (model_name, e.x mxbai-embed-large)
    ```
- Virtual environment (recommended)

---

## 🛠 Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/miuceo/local-rag-agent.git
   cd local-rag-agent
