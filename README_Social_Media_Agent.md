# 📱 Social Media AI Agent

> Built with n8n | Groq LLM | llama-3.3-70b-versatile

[![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-orange)](https://n8n.io)
[![Groq](https://img.shields.io/badge/Groq-LLM-blue)](https://groq.com)
[![Llama](https://img.shields.io/badge/Llama-3.3--70b-purple)](https://groq.com)

---

## 🎯 What It Does

An intelligent AI agent that **automatically generates professional social media posts** for LinkedIn and Twitter/X — just give it a topic!

Simply type your topic in the chat → AI generates ready-to-post content for both platforms instantly!

---

## 🔄 Workflow

```
User types topic in Chat
          ↓
Chat Trigger Node (Receives input)
          ↓
AI Agent Node (System prompt for social media)
          ↓
Groq LLM — llama-3.3-70b-versatile (Generates posts)
          ↓
Simple Memory (Remembers context)
          ↓
LinkedIn Post + Twitter Post ready! ✅
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation platform |
| Groq API | Fast LLM inference |
| llama-3.3-70b-versatile | AI model for content generation |
| Simple Memory Node | Conversation context |
| Chat Trigger | User interface |

---

## ✨ Features

- Generates LinkedIn post (150-200 words, professional tone)
- Generates Twitter/X post (under 280 characters)
- Adds relevant emojis automatically
- Adds trending hashtags (#AI #AgenticAI #n8n #Automation)
- Remembers previous topics for follow-up
- Works for any topic instantly

---

## 🚀 How to Use

1. Open the chat interface
2. Type your topic like:
```
Create posts about: I built an AI Resume Analyzer using n8n
```
3. Get instant LinkedIn + Twitter posts!

### Example Topics
- "I built an AI automation agent using n8n"
- "Tips for learning Agentic AI in 2026"
- "How n8n changed my workflow automation"
- "My journey from content writer to AI developer"

---

## 📸 Workflow Screenshot

![Social Media Agent Workflow](workflow.png)

---

## ⚙️ Setup

### Prerequisites
- n8n account (cloud or self-hosted)
- Groq API key — free at [console.groq.com](https://console.groq.com)

### Installation
1. Clone this repository
2. Import `social-media-workflow.json` into n8n
3. Add your Groq API credentials
4. Click **Publish**
5. Open chat and start generating posts!

---

## 🎨 System Prompt Used

```
You are a Social Media Content Expert.
When a user gives you a topic, create:

1. LINKEDIN POST:
- Professional tone
- 150-200 words
- Add relevant emojis
- Add 5 hashtags like #AI #AgenticAI #n8n #Automation #Tech

2. TWITTER/X POST:
- Short and catchy
- Under 280 characters
- Add 3 hashtags

Make both posts engaging and professional.
```

---

## 👩‍💻 Built By

**Marisha Dwivedi** — Agentic AI Developer
- 🌐 Portfolio: [marishadwivedi.netlify.app](https://marishadwivedi.netlify.app)
- 💼 LinkedIn: [linkedin.com/in/marisha-dwivedi-513269271](https://linkedin.com/in/marisha-dwivedi-513269271)
- 🐙 GitHub: [github.com/marisha119-AI](https://github.com/marisha119-AI)

---

## 🔮 Future Improvements

- Direct LinkedIn API integration for auto-posting
- Schedule posts for specific time
- Instagram caption generator
- Hashtag trend analyzer
- Multi-language post generation

---

*Made with passion for AI automation 🤖*
