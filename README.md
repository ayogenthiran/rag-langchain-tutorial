# rag-langchain-tutorial

# 🔍 LangChain RAG Tutorial with LangSmith + OpenAI + Chroma

This project is a hands-on walkthrough of building a **Retrieval-Augmented Generation (RAG)** app using:

- 🧠 [LangChain](https://www.langchain.com/)
- 🔍 [Chroma Vector Store](https://www.trychroma.com/)
- 🧬 OpenAI (`gpt-4o` and `text-embedding-3-large`)
- 📊 [LangSmith](https://smith.langchain.com/) for observability

It answers questions from the blog:
[LLM-Powered Autonomous Agents by Lilian Weng](https://lilianweng.github.io/posts/2023-06-23-agent/)

---

## 🚀 Features

- ✅ Web scraping with `WebBaseLoader`
- ✅ Text chunking with `RecursiveCharacterTextSplitter`
- ✅ Vector search with Chroma
- ✅ Question answering with a StateGraph
- ✅ LangSmith trace logging

---

## 🛠️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/ayogenthiran/rag-langchain-tutorial.git
cd rag-langchain-tutorial
