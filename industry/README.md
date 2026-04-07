# 🚀 Real-Time Industry Insight & Strategic Intelligence System

An AI-driven decision support system that combines real-time data collection with intelligent analysis to deliver actionable business insights. The platform enables users to monitor industry movements, evaluate competitors, and understand market dynamics through continuously updated information streams.

---

## 🔍 Overview

Most conventional analytics tools rely on historical or static datasets, limiting their ability to reflect current trends. This system overcomes that limitation by integrating live data from multiple external sources such as Google services and Wikipedia.

It follows a service-oriented architecture, where a Streamlit-based interface communicates with a FastMCP backend to handle data processing, analysis, and response generation efficiently.

---

## ✨ Key Features

- 📊 Real-time market trend monitoring  
- 🏷️ Brand comparison (price, ratings, product details)  
- 📈 Pattern-based trend analysis  
- 🤖 AI-generated insights and summaries  
- 💬 Chat-based intelligent assistant  
- 🌐 Wikipedia integration for additional context  
- 📉 Data visualization using charts  

---

## 🛠 Tech Stack

- Python  
- Streamlit (Frontend)  
- FastMCP (Backend Communication)  
- SerpAPI (Google Search & Shopping Data)  
- Wikipedia API  
- LangChain / HuggingFace (AI Models)  
- Matplotlib (Visualization)  
- dotenv (Environment Management)  

---

## 📂 Project Structure

```
Real-Time-Industry-Insight-and-Strategic-Intelligence-System/

│
├── industry/                 # Main application code
│   ├── app.py                # Streamlit UI
│   ├── main.py               # Entry point
│   ├── ai_engine.py          # AI analysis logic
│   ├── chat_module.py        # Chat assistant
│   ├── compclient.py         # API client handling
│   ├── compserver.py         # Comparison processing
│   ├── mcp_server.py         # MCP backend server
│   ├── pdf_report.py         # Report generation
│   ├── debug_mcp.py          # Debugging utilities
│   ├── promptclient.py       # Prompt handling
│   ├── promptserver.py       # Prompt backend
│

```

## ⚙️ How It Works

1. User enters a query or brand name  
2. Streamlit UI sends request to backend  
3. FastMCP server processes the request  
4. External APIs fetch real-time data  
5. AI models analyze and interpret the data  
6. Results are displayed as charts, tables, and insights  

---

## 💡 Use Cases

- Market trend analysis  
- Business intelligence  
- Brand comparison  
- Competitor analysis  
- AI-assisted decision making  

---

## 🚀 Future Scope

- Integration of additional data sources (news, social media)  
- Advanced predictive analytics  
- User authentication system  
- Cloud deployment for scalability  

---

## 👩‍💻 Developed By

Developed as part of a collaborative academic/industry project under the **Infosys Springboard Initiative**

---

## 📄 License

This project is licensed under the MIT License.
