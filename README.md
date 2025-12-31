# 🤖 Feedback AI Automation System (n8n)

A **production-ready AI workflow** built with **n8n** that automatically analyzes website feedback and takes action — no manual review required.

This project demonstrates how **AI Agents** can replace repetitive human workflows using real automation logic.

---

## 🚀 What This Workflow Does

When a user submits feedback on a website form, the system automatically:

1. Receives the feedback (Trigger)
2. Analyzes sentiment and intent using an AI Agent
3. Processes and structures the AI output
4. Routes the result based on sentiment
5. Sends notifications and stores data

All steps run **fully automated**.

---

## 🧠 Workflow Overview

![Feedback AI Automation Workflow](./workflow.png)

> Dark-mode n8n workflow showing an AI-powered feedback automation system.

---

## 🧩 Nodes Breakdown

### 1️⃣ Form / Webhook Trigger
- Entry point for website feedback
- Captures user name, email, and message

### 2️⃣ AI Agent (Core Logic)
- Understands user intent
- Detects sentiment (positive / neutral / negative)
- Decides what action to take

> This is **not a chatbot** — this is an **agentic system**.

### 3️⃣ LLM (Google Gemini / OpenAI / Claude)
- Provides reasoning and language understanding
- Powers all AI decisions

### 4️⃣ JavaScript Logic Node
- Parses AI output
- Normalizes structured data
- Ensures predictable downstream behavior

### 5️⃣ Filter Node
- Routes workflow based on sentiment or urgency

### 6️⃣ Action Nodes
- 📧 Email notification
- 💬 Slack alert
- 📊 Google Sheets logging (optional)

---

## 📦 Files Included

| File | Description |
|-----|------------|
| `feedback-ai-automation.json` | Complete n8n workflow export |
| `workflow.png` | Visual overview of the workflow |
| `README.md` | Project documentation |

---

## ⚙️ How to Use

1. Clone this repository
2. Open **n8n**
3. Import `feedback-ai-automation.json`
4. Set your API keys:
   - LLM (Gemini / OpenAI / Claude)
   - Gmail / Slack (optional)
5. Activate the workflow

✅ Ready for production use.

---

## 🌍 Use Cases

- SaaS products
- E-commerce websites
- Landing pages
- Personal portfolios
- Support feedback systems

---

## ⭐ Why This Matters

- No manual feedback review
- Faster response times
- Scalable automation
- Clear example of **Agentic AI**

> **Stop reading feedback.  
Let AI do the work.**

---

## 👤 Author

**Behrouz Khanjani**  
AI Automation & n8n Workflows

---

## 📜 License

MIT License – free to use, modify, and deploy.
