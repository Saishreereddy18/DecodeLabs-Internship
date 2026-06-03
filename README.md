# DecodeLabs-Internship
AI chatbot with rule-based engine and LLM fallback
# 🤖 ShreeBot — AI Chatbot

A rule-based AI chatbot with LLM fallback, built as part of the DecodeLabs Logic Engine module.

## 🚀 Live Demo
👉 [Click here to chat with ShreeBot](https://saishreereddy18.github.io/rule-based-chatbot/chatbot.html)

---

## 💡 How it works
User types a question
↓
Rule engine checks dictionary (O(1) lookup)
↓
Match found? → Instant reply
↓
No match?   → Claude AI answers it

---

## ⚙️ Architecture

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Rule Engine | Python Dictionary | Handles 30+ known intents instantly |
| Sanitization | .lower().strip() | Cleans user input |
| Fallback | Claude LLM API | Answers unknown questions |
| Frontend | HTML + CSS + JS | Interactive chat UI |

---

## 🧠 Concepts demonstrated
- White-box AI system (fully traceable)
- O(1) dictionary lookup vs O(n) if-elif ladder
- Hybrid AI architecture (rules + LLM)
- Input sanitization and keyword matching
- REST API integration

---

## 📁 Project structure
rule-based-chatbot/
│
├── chatbot.html      ← full chatbot website (open in browser)
└── README.md         ← you are here

---

## 🛠️ Run locally
Just download `chatbot.html` and open it in any browser. No installs needed.

---

## 📬 Contact
- **Name:** Saishree Reddy
- **Email:** saishreereddy18@gmail.com
- **GitHub:** [github.com/Saishreereddy18](https://github.com/Saishreereddy18)

---

*Built with ❤️ by Saishree Reddy at DecodeLabs*
