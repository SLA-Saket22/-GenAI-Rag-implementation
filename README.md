# 🤖 Multi-Agent Research Assistant

> **An AI-powered research system that uses multiple specialized agents to search, analyze, verify, and generate structured research reports.**

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/LangChain-Framework-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LLM-Agentic%20AI-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RAG-Enabled-orange?style=for-the-badge" />
</p>

---

## 🚀 Overview

Researching a topic manually requires searching multiple sources, reading large amounts of information, verifying facts, and organizing everything into a structured report.

**Multi-Agent Research Assistant** automates this workflow using a team of specialized AI agents.

The system can:

* 🔎 Search for relevant information
* 📄 Read and extract useful content
* ✍️ Generate structured research reports
* 🧐 Critically evaluate generated content
* 🔗 Ground responses using retrieved sources
* ♻️ Refine the final output through an agentic workflow

---

## 🧠 Multi-Agent Architecture

```text
                    👤 User
                       │
                       ▼
              ┌─────────────────┐
              │  Research Query │
              └────────┬────────┘
                       │
                       ▼
              🔎 Search Agent
                       │
             Web / Documents
                       │
                       ▼
              📖 Reader Agent
                       │
             Extract & Analyze
                       │
                       ▼
              ✍️ Writer Agent
                       │
            Generate Research
                       │
                       ▼
              🧐 Critic Agent
                       │
             Evaluate & Refine
                       │
                       ▼
              📑 Final Report
```

---

## 🤖 Agents

| Agent               | Responsibility                                       |
| ------------------- | ---------------------------------------------------- |
| 🔎 **Search Agent** | Finds relevant information from available sources    |
| 📖 **Reader Agent** | Extracts and analyzes useful information             |
| ✍️ **Writer Agent** | Converts research findings into a structured report  |
| 🧐 **Critic Agent** | Reviews the report and identifies gaps or weaknesses |

---

## ✨ Key Features

### 🔍 Intelligent Research

Automatically searches and collects information relevant to the user's research query.

### 📚 RAG-Based Retrieval

Uses document retrieval and vector databases to provide context-aware information to the LLM.

### 🤝 Multi-Agent Workflow

Different agents handle different stages of the research process instead of relying on a single LLM call.

### 🧠 Source Grounding

Retrieved information is used as context to improve factual grounding and reduce unsupported responses.

### 📝 Automated Report Generation

Research findings are synthesized into a structured and readable report.

### 🧐 AI-Based Evaluation

A dedicated Critic Agent evaluates the generated research and helps identify missing or weak information.

---

## 🛠️ Tech Stack

```text
Python
│
├── LangChain
├── LangGraph
├── LLMs
├── RAG
├── Vector Database
├── Web Search
└── Document Retrieval
```

### Technologies Used

* 🐍 Python
* 🦜 LangChain
* 🔗 LangGraph
* 🧠 Large Language Models (LLMs)
* 📚 Retrieval-Augmented Generation (RAG)
* 🗄️ Vector Database
* 🌐 Web Search
* 📄 Document Processing

---

## 📂 Project Structure

```text
Multi-Agent-Research-Assistant/
│
├── agents.py
├── pipeline.py
├── requirements.txt
├── README.md
│
└── .env
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/multi-agent-research-assistant.git
cd multi-agent-research-assistant
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file:

```env
LLM_API_KEY=your_api_key
SEARCH_API_KEY=your_api_key
```

---

## ▶️ Usage

Run the research pipeline:

```bash
python pipeline.py
```

Example:

```text
Enter research topic:
Impact of AI on Software Engineering
```

The system will:

```text
Query
  ↓
Search
  ↓
Read
  ↓
Analyze
  ↓
Write
  ↓
Critic Review
  ↓
Final Research Report
```

---

## 📊 Example Output

### Research Topic

> **Impact of AI on Software Engineering**

### Generated Report

```text
1. Introduction

2. Current Applications of AI
   - Code generation
   - Automated testing
   - Code review

3. Benefits
   - Increased developer productivity
   - Faster development cycles

4. Challenges
   - Hallucinations
   - Security concerns
   - Code reliability

5. Future Scope

6. Sources
```

---

## 🎯 Problem Statement

Traditional research requires manually searching, reading, verifying, and organizing information from multiple sources. This project automates the process using specialized AI agents for **search, analysis, writing, and critical evaluation**.

---

## 🔮 Future Improvements

* [ ] Add more specialized research agents
* [ ] Improve source verification
* [ ] Add citation generation
* [ ] Add PDF report export
* [ ] Build a React-based frontend
* [ ] Add conversational research
* [ ] Add persistent research memory
* [ ] Improve agent evaluation
* [ ] Add multi-source fact checking

---

## 📈 Learning Outcomes

Through this project, I explored:

* Multi-Agent AI architecture
* LangChain and LangGraph
* Agentic workflows
* RAG pipelines
* Vector databases
* LLM orchestration
* Tool calling
* Prompt engineering
* Source grounding
* AI-based evaluation

---

## 👨‍💻 Author

**Your Name**

💼 AI Engineer | Full Stack Developer
🐍 Python | 🤖 AI/ML | 🦜 LangChain | ⚛️ React | 🟢 Node.js

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

> **Built with Python + LangChain + LLMs + Agentic AI**
