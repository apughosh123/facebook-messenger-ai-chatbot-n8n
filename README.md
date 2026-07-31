# 🤖 Facebook Messenger AI Chatbot with n8n

An AI-powered Facebook Messenger Chatbot built with **n8n**, **Google Gemini**, and the **Facebook Graph API**. This chatbot automatically responds to customer messages, maintains conversation memory, and provides intelligent customer support for a saree business.

---

## 🚀 Features

- ✅ Facebook Messenger Webhook Integration
- ✅ Webhook Verification using Production URL
- ✅ Facebook Graph API Integration
- ✅ AI-powered responses with Google Gemini
- ✅ Conversation Memory (Simple Memory)
- ✅ Automatic customer support
- ✅ Custom Prompt Engineering
- ✅ Messenger auto-reply
- ✅ Production-ready webhook workflow

---

## 🛠 Tech Stack

- n8n
- Google Gemini API
- Facebook Graph API
- Webhooks
- HTTP Request
- AI Agent
- Simple Memory
- JSON
- REST API

---

## 📌 Workflow Overview

```
Facebook Messenger
        │
        ▼
    Webhook Trigger
        │
        ├──────────────► Verification Request
        │                    │
        │                    ▼
        │           Respond to Webhook
        │
        ▼
     AI Agent
        │
        ▼
 Google Gemini
        │
        ▼
 Conversation Memory
        │
        ▼
HTTP Request
(Facebook Graph API)
        │
        ▼
 Messenger Reply
```

---

## 💬 Chatbot Capabilities

The chatbot can:

- Welcome customers
- Show product categories
- Answer delivery-related questions
- Explain payment methods
- Guide customers through the ordering process
- Provide exchange policy information
- Maintain conversation context using memory
- Respond naturally in Bangla and English

---

## 📸 Workflow Screenshot

> Add your workflow screenshot here.

Example:

```
/images/workflow.png
```

---

## ⚙️ Setup

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/facebook-messenger-ai-chatbot.git
```

---

### 2. Import Workflow

Import the provided `workflow.json` into n8n.

---

### 3. Configure Credentials

Configure:

- Facebook Page Access Token
- Google Gemini API Key

---

### 4. Configure Webhook

Set your Production URL inside the Facebook Developer Portal.

---

### 5. Activate Workflow

Activate the workflow and send a message to your Facebook Page.

---

## 📂 Project Structure

```
facebook-messenger-ai-chatbot
│
├── workflow.json
├── README.md
├── LICENSE
├── images
│   └── workflow.png
└── screenshots
    ├── messenger-chat.png
    └── chatbot-demo.png
```

---

## 📚 What I Learned

During this project I learned:

- AI Workflow Automation
- Facebook Messenger Webhooks
- Facebook Graph API
- Prompt Engineering
- Google Gemini Integration
- Session Memory
- Production Webhook Deployment
- API Debugging
- JSON Request Formatting
- Error Handling

---

## 🔥 Challenges Faced

- Webhook Verification
- Production URL Configuration
- Facebook Graph API Authentication
- JSON Formatting
- Messenger Response Issues
- Google Gemini API Rate Limits
- Prompt Engineering Improvements

---

## 🎯 Future Improvements

- Better Prompt Engineering
- Smarter Follow-up Questions
- Product Database Integration
- Google Sheets Order Storage
- Voice Support
- Human Handover
- Multi-language Support
- Image-based Product Recommendation

---

## 🤝 Connect With Me

**Apu Ghosh**

- LinkedIn: https://www.linkedin.com/in/apughosh123/
- GitHub: https://github.com/apughosh123

---

## ⭐ Support

If you found this project helpful, please consider giving it a **Star ⭐** on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
