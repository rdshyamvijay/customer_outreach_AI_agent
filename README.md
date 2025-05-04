# Customer Outreach AI - Multi-Agent CrewAI System

## Project Overview

This project implements a **multi-agent customer outreach workflow** using **CrewAI**. It features two collaborative AI agents that simulate a sales workflow:

*  **Sales Representative**: Gathers lead information and drafts initial outreach messages.
*  **Lead Sales Representative**: Reviews and improves the messages for clarity and tone before sending.

The system uses **LLMs** (via Hugging Face or OpenAI), **tools** like Serper for web search, and supports agent memory and task delegation.

---

##  Project Structure

```bash
customer-outreach-agents/
├── customer_outreach.ipynb       # Main notebook with AI agent logic
├── utils.py                      # Utility functions (API keys, configurations)
├── requirements.txt              # Dependency list
├── README.md                     # Project documentation
```

---

##  Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/rdshyamvijay/customer-outreach-agents.git
cd customer-outreach-agents
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up API Keys

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your-openai-key
SERPER_API_KEY=your-serper-key
```

### 4. Run the Notebook

```bash
jupyter notebook
```

Then open `customer_outreach.ipynb` and run the cells to simulate the outreach workflow.

---

##  Technologies Used

* [CrewAI](https://crewai.com)
* [LangChain Community](https://www.langchain.com)
* [Serper.dev](https://serper.dev)
* Hugging Face / OpenAI (for LLMs)
* Python 3.8+
* Jupyter Notebook

---

##  Features

* Multi-agent collaboration using CrewAI
* Memory-enabled agents
* Role-based tasks and delegation
* Serper-integrated research workflow
* Human-like, high-quality outreach message generation
* Easily extensible to include CRMs, analytics, etc.

---

##  License

This project is licensed under the **MIT License**.

---

##  Support

If you have questions or need help:

* Open an issue on [GitHub Issues](https://github.com/<your-username>/customer-outreach-agents/issues)
* Contact via email: [rdshyamvijay@gmail.com](mailto:rdshyamvijay@gmail.com)
