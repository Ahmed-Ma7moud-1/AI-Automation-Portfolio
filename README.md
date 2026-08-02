# 🤖 AI Automation & Agentic Solutions Portfolio

Welcome! I am an **AI Automation & Agentic Systems Developer** specializing in building autonomous workflows, intelligent agents, and seamless enterprise integrations.

I design custom AI solutions using **n8n**, **LLMs**, **Custom Tools**, and **APIs** to automate complex business processes and eliminate repetitive manual tasks.

---

## 🚀 Core Expertise & Technologies

* 🧠 **Agentic AI Frameworks:** Building multi-node AI agents with memory, tool calling, and structured JSON parsing.
* ⚡ **Workflow Automation:** Advanced process orchestration using **n8n** (Self-Hosted).
* 🔌 **Integrations:** Telegram Bot API, Google Workspace (Sheets, Gmail, Drive), Webhooks, REST APIs.
* 💰 **Cost-Optimized Architecture:** Designing self-hosted solutions using open-source models/routers.

---

## 📁 Featured Projects

### 1️⃣ Telegram AI Sales & Inventory Agent
* **Description:** An autonomous AI agent integrated with Telegram and Google Sheets. It receives unstructured natural language input, extracts structured sales data, and logs verified entries automatically.
* **Tech Stack:** `n8n` | `OpenRouter API` | `Telegram Bot API` | `Google Sheets API`

### 2️⃣ Smart Crypto & Financial ReAct Assistant
* **Description:** A ReAct-pattern agent that reasons and acts autonomously to fetch real-time crypto prices via external APIs and executes error-free deterministic math computations.
* **Tech Stack:** `n8n` | `OpenRouter API` | `CoinGecko API` | `Calculator Tool` | `Window Buffer Memory`

---

## 📌 Portfolio Index / قائمة المشاريع

| # | Project / Agent Name | Architecture Pattern | File Link |
|:---:|:---|:---|:---:|
| **01** | Telegram Sheets AI Inventory Agent | Webhook & Dynamic Data Extraction | [`telegram-sheets-ai-workflow.json`](./telegram-sheets-ai-workflow.json) |
| **02** | ReAct Crypto & Financial Assistant | ReAct (Reasoning + Acting + Tools) | [`Agent_01_ReAct_Financial_Assistant.json`](./Agent_01_ReAct_Financial_Assistant.json) |
# Autonomous AI Routing & Customer Service System 🤖

An advanced end-to-end AI automation workflow built using **n8n**, **OpenRouter (LLMs)**, and **Telegram / Chat Triggers**, developed under **NexFlow**.

## 🌟 Overview
This system automates customer communication by ingesting incoming messages, analyzing user intent and sentiment in real-time, intelligently routing leads (Sales, Technical Support, and Spam) to internal CRMs, and instantly generating contextual, human-like replies.

## 🛠️ Tech Stack & Architecture
* **Orchestration:** n8n (Local Docker environment)
* **AI & LLMs:** OpenRouter (Gemini / Smart Models via AI Agents)
* **Data Processing:** JavaScript Code Node (JSON formatting & cleaning)
* **Integration & Logging:** Google Sheets (CRM Lead Logging) & Telegram / Web Chat Triggers

## 🔄 Workflow Pipeline
1. **Trigger:** Captures incoming messages from users.
2. **Intent & Mood Analyzer (AI Agent):** Extracts customer intent, emotional state, and summarizes the core request.
3. **Data Formatting (Code Node):** Cleans and normalizes the output into a strict JSON structure.
4. **Smart Router (Switch):** Directs traffic based on intent categories (`sales_lead`, `technical_support`, `spam`).
5. **CRM Logging & Response:** Automatically logs sales leads to Google Sheets and deploys dynamic, polite customer responder agents for real-time engagement.

---
*Built with ❤️ by Ahmed / NexFlow*
---

## 🛠️ How to Import Workflows

Each project in this repository includes a production-ready `.json` workflow file:
1. Download the target `.json` file from the repo.
2. Open your **n8n** instance.
3. Select **Import from File** and upload the workflow.
4. Add your API credentials.

---

🤝 **Open for Collaboration & Freelance Projects**
