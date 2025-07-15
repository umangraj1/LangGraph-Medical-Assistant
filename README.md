# 🏥 LangGraph Medical Assistant

An intelligent medical assistant built with **LangGraph** and **Gemini (Google Generative AI)**. The assistant accepts user-reported symptoms, uses an LLM to classify them into medical categories, and routes the user accordingly using a graph-based control flow.

---

## 🚀 Features

- Accepts symptom input via terminal/console
- Classifies symptoms into:
  - General
  - Emergency
  - Mental Health
- Uses Gemini LLM for natural language classification
- LangGraph framework to define agent flow and routing
- Lightweight and modular architecture

---

## 🧠 Tech Stack

- Python
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [LangChain](https://www.langchain.com/)
- Google Generative AI (Gemini Pro via `langchain-google-genai`)

---

## 📦 Requirements

Install Python dependencies:

```bash
pip install -qU \
  google-generativeai==0.8.5 \
  google-ai-generativelanguage==0.6.15 \
  langgraph \
  langchain \
  langchain-google-genai \
  openai
