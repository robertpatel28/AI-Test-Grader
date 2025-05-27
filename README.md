# 🧠 AI-Powered Grading System

An intelligent, multi-agent application that automates the grading of student-submitted test files using Azure OpenAI, Azure Cognitive Search, and Azure Blob Storage. The system extracts answers, compares them to an answer key, calculates scores, and generates a readable report — all through orchestrated AI agents.

---

## 📌 Features

- 🔍 **SearchAgent**: Extracts student answers from uploaded test files using Azure Cognitive Search and OpenAI GPT.
- 📝 **GradingAgent**: Compares extracted answers with the answer key and calculates grades with detailed validation rules.
- 📊 **ReportAgent**: Automatically generates a concise performance report based on grading output.
- 🧠 **PlannerAgent**: Orchestrates all agents and manages user interaction through the command line.

---

## ⚙️ Tech Stack

- **Language**: Python
- **LLM**: Azure OpenAI GPT
- **Data Search**: Azure Cognitive Search
- **Storage**: Azure Blob Storage
- **Authentication**: Azure Identity / Entra ID
- **Environment Management**: `python-dotenv`
