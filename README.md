# 💳 ABP-ICAS · AI Financial Intelligence System

> AI-powered bill parsing, expense categorisation, and cost-splitting assistant — built with vanilla HTML/CSS/JS and powered by the OpenAI GPT-4o API.

🔗 **Live Demo:** [Ayush-otcom.github.io/abp-icas](https://Ayush-otcom.github.io/abp-icas)

---

## ✨ Features

- **📄 Bill Parsing** — Paste any bill text; the AI extracts vendor, date, amount, and line items into structured JSON
- **🏷 Expense Categorisation** — Automatically classifies expenses: Food, Travel, Utilities, Healthcare, Entertainment, Shopping, Rent, Salary
- **➗ Cost Splitting** — Split bills among any number of people by equal share or custom percentages
- **💬 Finance Q&A** — Ask budgeting, savings, and expense-management questions (domain-restricted to Finance only)
- **📊 Session Stats** — Live bill count and total spend tracker with category breakdown charts
- **🔒 Login-protected** — Secure login screen with animated 3D card

## 🚀 Getting Started

1. Open `index.html` in any modern browser **or** visit the live GitHub Pages link above
2. Login with demo credentials: `admin` / `1234`
3. Enter your **OpenAI API key** in the sidebar (`sk-...`)
4. Start chatting — paste a bill, ask to split costs, or ask any finance question!

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML5, CSS3, JavaScript (ES2022) |
| AI | OpenAI GPT-4o via `/v1/chat/completions` |
| Fonts | Google Fonts (Orbitron, Rajdhani, Share Tech Mono) |
| Deployment | GitHub Pages |

## ⚙️ Model Parameters

| Parameter | Default | Description |
|---|---|---|
| Temperature | 0.20 | Low = accurate, ideal for finance |
| Top-p | 0.95 | Broad nucleus sampling |
| Max Tokens | 1024 | Per response |

## 🔑 API Key

This project requires an OpenAI API key. Get yours at [platform.openai.com/api-keys](https://platform.openai.com/api-keys).

> ⚠️ Your API key is never stored — it only lives in your browser session.

## 📁 Project Structure

```
abp-icas/
├── index.html   # Complete single-file app (HTML + CSS + JS)
└── README.md
```

---

Made with ❤️ by [Ayush-otcom](https://github.com/Ayush-otcom)
