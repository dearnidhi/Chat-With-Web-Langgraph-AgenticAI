# LangGraph Agentic AI Chatbot with Streamlit UI

An extensible, agent-based chatbot framework built using **LangGraph**, **LangChain**, and **Streamlit**. This project demonstrates how to construct conversational AI workflows as graphs, with optional tool integration such as web search.

---

## 🚀 Features

- **Multiple Chatbot Use Cases**
  - Basic Chatbot
  - Chatbot with Web Search (Tavily)
- **Agentic Graph Architecture**
  - Built using LangGraph `StateGraph`
  - Conditional routing between nodes
- **LLM Abstraction**
  - Dynamic LLM configuration (Groq supported)
- **Tool Integration**
  - Web search via Tavily
- **Streamlit UI**
  - Interactive chat interface
  - Sidebar-based configuration
- **Streaming Responses**
  - Real-time graph execution for basic chatbot

---

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone <repo-url>
cd <repo-name>
2. Install Dependencies
pip install -r requirements.txt
3. Required API Keys
You will need:
Groq API Key (for LLM access)
Tavily API Key (only for “Chatbot With Web” use case)
These are entered securely via the Streamlit sidebar.

▶️ Running the Application

streamlit run app.py
(Replace app.py with the entry file where load_langgraph_agenticai_app() is called.)

🧪 Available Use Cases
Basic Chatbot
Simple conversational flow
Single-node graph
Direct LLM invocation
Chatbot With Web
Tool-augmented reasoning
Conditional graph edges
Tavily-powered web search integration

🧩 Extending the Project
Add new chatbot behaviors by creating new nodes
Introduce new tools using LangChain-compatible tools
Expand the graph logic inside GraphBuilder
Plug in additional LLM providers

📌 Technologies Used
Python
Streamlit
LangGraph
LangChain
Groq LLM
Tavily Search API
