# 🤖 AI Agent ChatBot

This project is a dynamic and customizable **AI chatbot application** built using **LangGraph**, **OpenAI/Groq LLMs**, **Tavily Search**, and a sleek **Streamlit** frontend. It allows users to define intelligent agents with custom instructions, web search capabilities, and multiple LLM providers.

## 🔧 Features

- 💬 Chat with AI agents powered by Groq (LLaMA, Mixtral) or OpenAI (GPT-4o-mini)
- ✍️ Customize system prompts to shape agent behavior
- 🌐 Enable/disable real-time web search using **Tavily**
- ⚙️ Modular architecture using `FastAPI` (backend) and `Streamlit` (frontend)
- 📤 POST-based API for chatbot queries via `/chat` endpoint
- ✅ LangGraph-powered tool selection and message flow

## 🧠 Tech Stack

| Layer       | Tech                                |
|-------------|-------------------------------------|
| LLMs        | OpenAI, Groq (via `langchain`)      |
| Tools       | Tavily Search                       |
| Frameworks  | LangGraph, LangChain                |
| UI          | Streamlit                           |
| Backend API | FastAPI                             |
| Others      | Pydantic, Uvicorn, dotenv (optional)|

---

## 📁 Project Structure

  ```bash
  AI_Agent_ChatBot/
  ├── ai_agent.py       # Agent logic using LangGraph
  ├── backend.py        # FastAPI backend server
  ├── frontend.py       # Streamlit UI
  ├── requirements.txt  # Dependencies
  └── README.md

## 🚀 How to Run
🔐 Step 1: Set API Keys
Set the following environment variables in your terminal or .env file:

OPENAI_API_KEY

GROQ_API_KEY

TAVILY_API_KEY
