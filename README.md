# 🤖 Customer Outreach AI - Multi-Agent CrewAI System

## 📌 Project Overview
This project implements a **multi-agent customer outreach workflow** using **CrewAI**. It features two collaborative AI agents that simulate a sales workflow:

- 🔹 **Sales Representative**: Gathers lead information and drafts initial outreach messages.
- 🔹 **Lead Sales Representative**: Reviews and improves the messages for clarity and tone before sending.

The system uses **LLMs** (via Hugging Face or OpenAI), **tools** like Serper for web search, and supports agent memory and task delegation.

---

## 🗂️ Project Structure

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository
git clone https://github.com/rdshyamvijay/customer-outreach-agents.git
cd customer-outreach-agents

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Set Up API Keys

Create a .env file in the project root:
OPENAI_API_KEY=your-openai-key
SERPER_API_KEY=your-serper-key

4️⃣ Run the Jupyter Notebook
Open customer_outreach.ipynb and run all cells to simulate the outreach workflow.

⚙️ Technologies Used
	•	CrewAI
	•	LangChain Community
	•	Serper.dev
	•	Hugging Face / OpenAI (for LLMs)
	•	Python 3.8+
	•	Jupyter Notebook

⸻

🚀 Features
	•	AI agents with distinct roles (sales + QA)
	•	Memory-enabled workflow
	•	Tool integration for research (Serper/Web search)
	•	Human-like multi-step collaboration
	•	Easily extendable to include CRMs, email triggers, etc.

⸻

📝 License

This project is licensed under the MIT License.
