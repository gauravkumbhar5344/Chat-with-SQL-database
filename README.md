# 💬 LangChain + Streamlit: Chat with Your SQL Database

This project allows users to interact with a SQL database using natural language through a chat interface powered by LangChain and Groq's **Gemma2-9b-It** language model. The app supports both SQLite (default `student.db`) and custom MySQL connections.

Built with:
- 🧠 [LangChain](https://www.langchain.com/)
- 🧪 [Streamlit](https://streamlit.io/)
- ⚡ [GROQ](https://console.groq.com/)
- 🛢️ SQLite & MySQL

---

## 🚀 Features

- ✅ Ask natural language questions to your database
- ✅ Switch between local SQLite and remote MySQL databases
- ✅ Uses LangChain SQL agent and Groq LLMs
- ✅ Interactive Streamlit UI with chat history
- ✅ Securely input your GROQ API Key and DB credentials

---

## 📦 Installation

### Clone the repo:

```bash
git clone https://github.com/yourusername/sql-chat-app.git
cd sql-chat-app
```
### Install dependencies:
```bash
pip install -r requirements.txt
```

### Set up your local SQLite database (Optional):

Make sure you have a student.db file in the same directory. You can modify the schema as needed.



