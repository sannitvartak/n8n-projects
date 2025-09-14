# 🤖 Website Support Chatbot Workflow

Welcome! This repo contains an n8n workflow for a smart website support chatbot that can answer questions, check your calendar, and book appointments—all automatically! 🚀

## ✨ What’s Inside?

- **AI Agent**: Handles chat messages and picks the right tool for the job.
- **OpenRouter Chat Model**: Powers natural conversations.
- **Calendar Booking Handler**: Checks Google Calendar for free slots and books events. 📅
- **Send Email to Support**: Sends support requests via Gmail. 📧
- **RAG API Call**: Answers business FAQs using Retrieval-Augmented Generation.
- **Store Chat Memory**: Saves chat history in Postgres for context.
- **Date & Time Tool**: Understands phrases like "tomorrow" or "in 3 days".

## 🚦 How to Use

1. Import `RAG-chat-bot.json` into your n8n instance.
2. Set up your credentials (Google Calendar, Gmail, OpenRouter, Postgres).
3. Replace placeholder values (calendar ID, API keys, URLs).
4. Activate the workflow and connect it to your website chat!

## 🛠️ Customization

- Edit the AI Agent’s system message for your brand’s tone.
- Update calendar and email settings as needed.

---

Enjoy automated support and seamless bookings!  
Questions? Open an issue or