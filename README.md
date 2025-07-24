# 💬 RAG-Powered Question Answering System using LLMs and Vector Databases

This project demonstrates how **knowledge workers** can leverage **Large Language Models (LLMs)** with **Retrieval-Augmented Generation (RAG)** and **Vector Databases** (like FAISS/Chroma) to extract meaningful answers from a large set of documents.

---

## 🚀 Features

- 🔍 **Semantic Search**: Embed and store documents as vectors for efficient and relevant search
- 🧠 **RAG Pipeline**: Retrieve context from a vector DB and generate answers using LLMs
- 🧰 **Embeddings Support**: Includes `OpenAIEmbeddings` and `HuggingFaceEmbeddings`
- 📚 **Use Case**: Tailored for knowledge workers – analysts, product managers, legal, etc.
- 🧪 **Interactive Q&A**: Ask natural language questions and get concise, context-aware answers

---

## 🏗️ Tech Stack

| Component       | Description                                        |
|-----------------|----------------------------------------------------|
| **LLM**         | OpenAI GPT / HuggingFace models                    |
| **RAG**         | Retrieval-Augmented Generation                     |
| **Vector DB**   | FAISS or Chroma (configurable)                     |
| **Embeddings**  | OpenAI / SentenceTransformers from Hugging Face   |
| **LangChain**   | Framework to orchestrate document loading, indexing, and QA |

---

---

## 📥 Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/Atharvax16/AI-Knowledge-Worker-using-RAG.git
   cd AI-Knowledge-Worker-using-RAG
