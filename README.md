# 🧠 Simple LLM Chatbot using LangGraph + Groq

This is a basic chatbot project built using:

- [LangGraph](https://www.langgraph.dev) – for stateful agent graph flow
- [LangChain](https://www.langchain.com) – for tool and chain abstraction
- [LangSmith](https://smith.langchain.com) – for observability, logging, and debugging
- [Groq API](https://console.groq.com) – for ultra-fast inference with Mixtral LLM

---

## 🚀 Features

- Chatbot with memory and conversation flow using LangGraph
- Connected to **Groq's LLM** for blazing-fast responses
- Integrated with **LangSmith** for traceability and debugging
- Simple architecture with a start node → LLM response → end node

---

## 🛠️ Stack

| Tool      | Usage                              |
|-----------|-------------------------------------|
| LangGraph | Build the chat flow (start → end)   |
| LangChain | LLM wrapper, prompt handling        |
| LangSmith | Debug and monitor conversation logs |
| Groq      | LLM provider (Gemma2-9b-It)    |

---

## 📁 Folder Structure

