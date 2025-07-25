# ZOHO-CHAT-AGENT
An intelligent finance chatbot built with Streamlit, OpenAI GPT-4o, and the Zoho Books API. This tool allows you to interact with your Zoho Books data — like invoices, profit & loss reports, and more — using natural language.

# 💬 Zoho Books Chat Assistant

An AI-powered Streamlit chatbot connected to the Zoho Books API via GPT-4o (OpenAI). This tool allows finance teams and business owners to interact with their accounting data using plain language.

---

## 🚀 Features

- 🔗 GPT-4o + Zoho Books API Integration
- 📊 Fetch Profit & Loss reports, invoices, customer balances
- 🧠 Smart query interpretation using OpenAI
- 🌐 Interactive Streamlit UI
- 📎 Easily expandable for custom business use cases

---

## 🛠️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/zoho-books-chat-assistant.git
   cd zoho-books-chat-assistant

Install Requirements

bash
Copy
Edit
pip install -r requirements.txt
Edit app.py Configuration
Replace these with your real credentials:

python
Copy
Edit
client = OpenAI(api_key="your-openai-api-key")
zoho_access_token = "your-zoho-access-token"
organization_id = "your-zoho-org-id"
Run the Chat Assistant

bash
Copy
Edit
streamlit run app.py
💬 Example Queries
“What is the profit for Q1 2024?”

“List all unpaid invoices.”

“Show customer balances”

“Who are my top 3 customers this year?”

📌 Future Ideas
 Voice input with Whisper

 Create/edit contacts & invoices

 Export reports to PDF or Excel

 Web deployment on Streamlit Cloud

