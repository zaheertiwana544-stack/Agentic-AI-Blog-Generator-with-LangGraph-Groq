# 🚀 Agentic AI Blog Generator with LangGraph & Groq

## 📌 Overview

This project is an **Agentic AI system** that automatically generates **high-quality technical blog posts** using a multi-agent workflow.

It leverages:

* **LangGraph** for orchestration
* **Groq LLM (LLaMA 3.3 70B)** for generation
* **Pydantic** for structured outputs
* **Parallel worker agents** for scalable content creation

---

## 🧠 Architecture

The system follows a **Planner → Workers → Reducer** pattern:

```
User Input (Topic)
        ↓
   Orchestrator (Planner)
        ↓
   Task Distribution (Fan-out)
        ↓
 Parallel Workers (Write Sections)
        ↓
     Reducer (Combine)
        ↓
   Final Blog Output (.md)
```

---

## ⚙️ Features

* ✅ Multi-agent architecture (LangGraph)
* ✅ Structured planning using Pydantic schemas
* ✅ Parallel section generation
* ✅ Production-style orchestration
* ✅ Markdown blog export
* ✅ Developer-focused technical writing

---

## 🧩 Tech Stack

* Python
* LangGraph
* LangChain
* Groq LLM (LLaMA 3)
* Pydantic
* dotenv

---

## 📂 Project Structure

```
.
├── main.py
├── .env
├── requirements.txt
└── generated_blog.md
```

---

## 🔑 Setup Instructions

### 1. Clone repo

```bash
git clone https://github.com/zaheertiwana544-stack/Agentic-AI-Blog-Generator-with-LangGraph-Groq.git
cd agentic-blog-generator
```

### 2. Create virtual environment

```bash
python -m venv myenv
myenv\Scripts\activate   # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add API key

Create `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run the Project

```bash
python main.py
```

Enter a topic:

```
enter blog topic... RAG systems in production
```

---

## 📝 Output

* Generates a **complete technical blog**
* Saves it as a `.md` file automatically
* Includes structured sections and actionable insights

---

## 💡 Example Use Cases

* Technical content generation
* Developer documentation automation
* AI writing assistants
* Knowledge sharing tools

---

## 🔐 Safety & Design

* Structured outputs using Pydantic
* Controlled generation via system prompts
* Modular agent design for scalability

---

## 🚀 Future Improvements

* Add RAG (Retrieval-Augmented Generation)
* Add web UI (Streamlit / React)
* Add citation tracking
* Multi-language support

---

## 👨‍💻 Author

Zaheer Abbas
Aspiring AI Engineer | Agentic AI | LLM Systems

---

## ⭐ Star This Repo

If you found this useful, give it a ⭐ on GitHub!
