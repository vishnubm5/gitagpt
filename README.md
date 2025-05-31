# 🕉️ GitaGPT – Ask the Bhagavad Gita with AI

GitaGPT is an AI-powered Q&A application that lets you ask deep, philosophical, or practical life questions and receive context-aware answers grounded in the Bhagavad Gita. Built using Retrieval-Augmented Generation (RAG), this app leverages powerful language models and vector embeddings to deliver meaningful and accurate insights.

---

## ✨ Features

- 📖 Ask any question and get responses grounded in the Bhagavad Gita.
- 🔍 Uses advanced **RAG (Retrieval-Augmented Generation)** architecture.
- 🤖 Powered by **Mistral** for natural responses.
- 🧠 Semantic search with **Nomic Embed Text** embeddings via Ollama.
- 📄 Parses knowledge directly from the `bhagvad_gita.pdf` file.
- 🧘 Built with a simple and elegant **Streamlit** interface.

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (LangChain)
- **LLM**: Mistral via Ollama
- **Embeddings**: Nomic Embed Text
- **Vector DB**: ChromaDB
- **PDF Parsing**: LangChain's UnstructuredPDFLoader

---

## 🚀 How It Works

1. **PDF Ingestion**: The Bhagavad Gita is parsed and split into semantically meaningful chunks.
2. **Vectorization**: Each chunk is embedded and stored using Chroma vector database.
3. **User Query**: You ask a question — like “What does the Gita say about fear?”
4. **Multi-Query Retrieval**: The app reformulates your query in multiple ways to get deeper matches.
5. **Answer Generation**: The LLM (Mistral) responds using only the most relevant chunks from the Gita.

---

## 📷 Preview

![Screenshot](./screenshot.png)

---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/your-username/gitagpt.git
cd gitagpt

