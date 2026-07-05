# 🤖 Telegram Personal AI Assistant

An Agentic AI-powered personal assistant built with **n8n** and **Telegram** that helps users manage daily tasks, answer questions, maintain conversational context, and interact with Google services through intelligent tool calling.

Unlike a traditional chatbot, this assistant can remember previous conversations, retrieve Google Tasks, and delegate calendar operations to specialized workflows, creating a more capable and context-aware AI experience.

---

## 🚀 Features

* 💬 Chat with an AI directly from Telegram
* 🧠 Context-aware conversations with memory
* 📅 Google Calendar integration through workflow delegation
* ✅ Retrieve Google Tasks on demand
* 🤖 Powered by Google Gemini via OpenRouter
* 🔄 Automatic tool selection based on user intent
* ⚡ Real-time responses inside Telegram
* 🛠 Modular Agentic AI architecture

---

## 🛠 Tech Stack

* **n8n**
* **Telegram Bot API**
* **Google Gemini 2.5 Flash**
* **OpenRouter**
* **Google Tasks API**
* **Google Calendar**
* **AI Agent**
* **Memory Buffer Window**

---

## 📌 Workflow Overview

```text
Telegram Message
        │
        ▼
Telegram Trigger
        │
        ▼
Prepare User Input
        │
        ▼
AI Agent
        │
        ├── Conversation Memory
        ├── Google Tasks Tool
        ├── Google Calendar Workflow
        └── Google Gemini (LLM)
        │
        ▼
Generate Response
        │
        ▼
Reply in Telegram
```

---

## ⚙️ How It Works

1. A user sends a message through Telegram.
2. The workflow captures the message and prepares it for processing.
3. The AI Agent analyzes the user's request.
4. Based on the request, the agent can:

   * Answer general questions
   * Maintain conversation context using memory
   * Retrieve tasks from Google Tasks
   * Delegate calendar-related operations to a dedicated Google Calendar workflow
5. The AI generates a natural response.
6. The response is sent back to the user in Telegram.

---

## 🧩 Agent Capabilities

### 💬 General AI Assistant

* Answer questions
* Explain concepts
* Brainstorm ideas
* Draft emails and documents
* Coding assistance
* Learning support

### 📅 Calendar Assistant

* Create calendar events
* View today's schedule
* Retrieve upcoming events
* Manage appointments

### ✅ Task Management

* Retrieve Google Tasks
* Help organize daily work
* Improve productivity

### 🧠 Conversation Memory

* Remembers recent conversation history
* Produces more natural and contextual responses

---

## 📂 Project Structure

```text
Telegram-Personal-AI-Assistant/
│
├── workflow.json
├── README.md
└── screenshots/
    ├── workflow.png
    ├── telegram-chat.png
    └── execution.png
```

---

## 📸 Screenshots

Add screenshots of:

* Complete n8n workflow
* Telegram conversation
* Workflow execution
* Google Tasks integration
* Calendar integration

---

## 💡 Use Cases

* Personal AI Assistant
* Productivity Assistant
* Daily Task Management
* Calendar Scheduling
* Learning Companion
* Coding Assistant
* Content Creation
* General Knowledge Assistant

---

## 🔮 Future Improvements

* Voice message support
* Image understanding
* Web search integration
* Email management
* Weather updates
* News summaries
* File upload analysis
* Multi-user support
* Long-term memory with a vector database

---

## 👨‍💻 Author

**B Sunil Kumar**

Final Year Engineering Student

Passionate about Agentic AI, Workflow Automation, and Building Real-World AI Solutions.

---

⭐ If you found this project useful, consider giving it a star!
