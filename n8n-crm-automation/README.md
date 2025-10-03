🤖 Custom AI-Powered CRM & Chatbot Automation

End-to-end AI-driven CRM workflow with chat integration, automated scheduling, contact management, and 30-day reminders — powered by Google Gemini + n8n.

📌 Overview

This project automates a Customer Relationship Management (CRM) system with an integrated custom chatbot. It connects Google Gemini’s AI capabilities with webhooks, Google Sheets, Gmail, and Calendar to:

Handle chatbot inquiries via webhook

Collect & format contact form responses

Send automated follow-up emails

Manage calendar scheduling & availability

Maintain a knowledge base with memory

Trigger 30-day reminders for follow-ups

⚙️ Workflows
🟤 1. Custom Chatbot

Handles incoming webhook messages and responds with AI-powered answers using Google Gemini Chat Model + memory + tools.

🟢 2. Main CRM Flow

Processes contact form data, formats it, and schedules follow-ups with automatic email notifications.

Includes:

Contact Form Webhook → Format Data → AI Answering → Gmail Integration

30 Days Reminder → Google Calendar + Sheets + Gmail

🟠 3. Data Processing & Calendar Integration

Handles form submissions & calendar events, updates client dashboards, and sends confirmation or alert messages.

Includes:

Client form intake

Email validation

Individual client sheet creation & update

Automated Gmail confirmations

🧩 Tech Stack

n8n
 — Workflow Automation

Google Gemini
 — Chat Model with Memory

Google Sheets — Data Storage & Dashboard

Google Calendar — Scheduling & Availability

Gmail — Automated Messaging

🚀 Getting Started

Clone this repo:

git clone https://github.com/your-username/custom-crm-chatbot.git
cd custom-crm-chatbot


Import workflows into n8n.

Configure environment variables:

GOOGLE_API_KEY=your_google_api_key
N8N_WEBHOOK_URL=your_webhook_url
GMAIL_CREDENTIALS=your_gmail_oauth


Deploy and run your workflows.

📅 Features

✔️ AI-powered chatbot with memory
✔️ Contact form automation
✔️ 30-day reminders
✔️ Google Sheets dashboards
✔️ Gmail notifications
✔️ Calendar integration

📌 Roadmap

 Add multi-language chatbot support

 Add analytics dashboard for CRM insights

 Expand integrations (Slack, WhatsApp, etc.)

🖼️ Preview

All workflows are modular and can be customized to fit any CRM pipeline.

📜 License

MIT License © 2025
