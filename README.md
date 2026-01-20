# 📰 NewsSense AI: Agentic RAG-Powered News Summarizer & Fact-Checker  

## 📌 Overview  
**NewsSense AI** is an **Agentic GenAI system** built using **LangChain, RAG, and AI Agents** that enables users to analyze and fact-check news articles.  
Given a news article URL, the system retrieves, summarizes, fact-checks using trusted sources (Wikipedia/NewsAPI), and performs sentiment analysis.  
It delivers insights through an **interactive Streamlit app** for real-time use.  

---

## 🚀 Features  
- 🔎 **RAG-Powered Retrieval** – Splits and indexes news text for efficient context-aware Q&A.  
- 🤖 **Agentic Workflow** – Planner agent decides when to summarize, fact-check, or perform sentiment analysis.  
- 🌐 **External Knowledge Integration** – Uses **Wikipedia/NewsAPI** for claim verification.  
- 😊 **Sentiment Analysis** – Classifies article tone (positive, neutral, negative).  
- 💻 **Interactive UI** – Streamlit app to paste links and receive results instantly.  

---

## 🏗️ Tech Stack  
- **LangChain** – Orchestration of LLMs, RAG, and agents.  
- **Gemini / HuggingFace Models** – For text generation.  
- **Chroma / FAISS** – Vector database for retrieval.  
- **Wikipedia API / NewsAPI** – Fact-checking and external references.  

---

## ⚙️ Installation  

1. Clone the repository:  
```bash
git clone https://github.com/Avirup221/NewsSense-AI.git
cd NewsSense-AI
