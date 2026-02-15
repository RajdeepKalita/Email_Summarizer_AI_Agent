# 📬 Inbox Intelligence Agent

An **Agentic AI-powered Gmail briefing system** that reads your inbox, prioritizes emails intelligently using a ReAct agent, and presents a clean, human-readable summary directly in your terminal.

---

## 🚀 What Makes This Different?

### 1️⃣ The "Agentic" Difference

Traditional email filters rely on rigid **If/Then rules**:

> If sender is “Bank” → Mark as “Finance”

This project uses a **ReAct Agent** that *reasons* before acting.

Example reasoning:

> "The user asked for urgent updates. I see an email from Crio about a scholarship ending in 2 days. That is mathematically urgent. I will prioritize this at the top."

Instead of keyword filtering, the agent:
- Understands context  
- Evaluates urgency  
- Makes intelligent prioritization decisions  

---

### 2️⃣ 🔐 Privacy-First Summarization

- The script connects **directly from your machine to Gmail**
- Only the **relevant email text** is sent to Gemini for summarization
- Attachments and metadata remain local
- No external storage of your inbox

Your data stays under your control.

---

### 3️⃣ 🖥️ Human-Readable UI

Instead of raw JSON or cluttered text, this project uses the **Rich** library to create a clean “Command Center” experience in the terminal.

Features:
- Emojis for visual priority cues
- Bold headers
- Clean horizontal dividers
- Easy-to-scan layout

---

##      ⚙️ Configuration

 Open the script and update the following variables:


  EMAIL_USER = "your_email@gmail.com"
  EMAIL_PASS = "your_16_character_app_password"
  GEMINI_API_KEY = "your_google_ai_studio_api_key"
