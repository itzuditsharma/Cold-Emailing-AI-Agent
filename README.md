# 🤖 Agentic AI: Cold Sales Email Generation using GPT Agents + SendGrid

This project demonstrates an **Agentic AI system** where multiple autonomous AI agents collaborate to generate, evaluate, and select the best cold sales email for a SaaS company using OpenAI models and `sendgrid` for email delivery.

## 🚀 Overview

The system simulates a **team of sales agents** — each with a unique personality — that:
1. Generate sales emails independently.
2. Compare and evaluate those emails.
3. Select the most effective one to send.
4. Optionally send it using SendGrid.

---

## 👥 Agentic Workflow

| Agent Name                | Role & Behavior |
|--------------------------|------------------|
| `Professional Sales Agent` | Writes formal and serious cold emails. |
| `Engaging Sales Agent`     | Writes humorous and engaging cold emails. |
| `Busy Sales Agent`         | Writes short and to-the-point cold emails. |
| `Sales Picker`             | Picks the best email from all candidates. |

These agents are defined using the `Agent` class, and run using an orchestrator (`Runner`) that allows streaming or batch interaction.

---

## 🧱 Technologies Used

- 🧠 OpenAI GPT-4o-mini
- 🕸️ `sendgrid` API (for email delivery)
- ⚙️ `dotenv` for API key management
- ⚡ Async execution with `asyncio`
- 📜 Custom classes: `Agent`, `Runner`, `trace`, `function_tool`

---

## 👥 Screenshot:
![Uploading image.png…]()

