# 🤖 Conversational Q&A Chatbot

A simple conversational chatbot web app built using [Streamlit](https://streamlit.io/) and [LangChain](https://www.langchain.com/) that interacts with the [Groq API](https://groq.com/) to answer user queries in a natural, conversational way.

---

## ✨ Features

- Chat interface powered by Streamlit  
- Conversational memory handling  
- Uses `langchain-groq` integration for AI responses  
- Interactive web UI with avatars for user and AI messages  

---

## 🔧 Prerequisites

- Python 3.8 or higher

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/qa-chatbot
cd qa-chatbot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set up API Keys

Create a `.streamlit/secrets.toml` file with your Groq API key:

```toml
GROQ_API_KEY = "your_groq_api_key_here"
```

### 4. Run the app

```bash
streamlit run app.py
```

---

## 🛠 Tech Stack

- Python  
- [Streamlit](https://streamlit.io/)  
- [LangChain](https://www.langchain.com/)  
- [Groq API](https://groq.com/)  

---

## 📁 Project Structure

```text
.
├── app.py                  # Main Streamlit app
├── requirements.txt        # Python dependencies
├── langchain.ipynb         # (Optional) Notebook for LangChain experiments
└── .streamlit
    └── secrets.toml        # Contains API keys (not included in repo)
```

---

## 🧠 Notes

- Chat history is preserved during the session using `st.session_state`.  
- You can modify the system message or model parameters (e.g., temperature) in `app.py` as needed.
- Provide your API key in Streamlit as follows: Go to ⚙️**Settings > Secrects**
  ```bash
  GROQ_API_KEY = "YOUR_API_KEY_HERE"
  HUGGINGFACEHUB_API_TOKEN = "YOUR_API_KEY_HERE"
  ```
---

## 📝 License

This project is open source and free to use for personal or educational purposes.
