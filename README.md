# 🤖 LLM-Powered File Management System

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
</p>

A capstone project that replaces traditional keyword-based file search with **natural language, semantic search** — powered by LLMs from OpenAI and Hugging Face.

🔗 **Live Demo:** [View Dashboard](https://kugan-29.github.io/AI_file_assist/)

---

## 📖 Overview

Traditional file search relies on exact filename or keyword matches, which fails when users don't remember exact names. This system uses LLM embeddings to understand the *meaning* behind a query, enabling natural language file retrieval and automatic categorization.

## ✨ Key Features

- **Semantic search** — find files by describing what's in them, not just filenames
- **Automatic categorization** of files using LLM-based classification
- Integrates both **OpenAI API** and **Hugging Face** models for flexibility
- Natural language query interface instead of rigid keyword search

## 🛠️ Tech Stack

- **Python** — core application logic
- **OpenAI API** — embeddings & natural language understanding
- **Hugging Face Transformers** — local model support / classification
- **[Add your vector DB if used, e.g., FAISS / ChromaDB]**

## 🏗️ Architecture

```
User Query → LLM Embedding → Vector Similarity Search → Ranked File Results
                                     ↓
                          Auto-Categorization Layer
```
> Replace with an actual architecture diagram if you have one (draw.io / Excalidraw export works great here).

## 🚀 How to Run

1. Clone this repo: `git clone https://github.com/kugan-29/llm-file-management-system.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Add your API key: create a `.env` file with `OPENAI_API_KEY=your_key_here`
4. Run the app: `python main.py`

## 📈 Impact / Learnings

- Hands-on experience integrating multiple LLM providers in one pipeline
- Learned to design retrieval systems beyond simple keyword matching

## 🔮 Future Improvements

- Add support for local open-source embedding models (no API dependency)
- Build a simple web UI for the search interface

---

📩 Questions or feedback? Reach me at kugankarthik67@gmail.com
