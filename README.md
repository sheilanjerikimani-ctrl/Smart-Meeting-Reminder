# 🤖 Smart Meeting Reminder

An AI-powered workflow built with n8n that automatically detects 
upcoming meetings and sends personalized, hard-to-ignore reminders 
via email — so you never miss an important meeting again.

## 🔧 How It Works

1. ⏰ **Schedule Trigger** — runs every 30 minutes automatically
2. 📅 **Google Calendar** — fetches meetings in the next 60 minutes
3. 🔀 **IF Node** — checks if a meeting actually exists
4. 🤖 **Gemini AI** — writes a personalized urgent reminder message
5. 📧 **Gmail** — sends the reminder to your inbox
6. 📊 **Google Sheets** — logs every reminder sent

## 💡 Problem Solved

Too many notifications = ignored notifications. This workflow 
cuts through the noise by generating a unique, personalized 
AI message for each meeting — impossible to ignore.

## 🛠️ Tech Stack

- n8n (workflow automation)
- Google Calendar API
- Google Gemini AI (gemini-2.5-flash-lite)
- Gmail API
- Google Sheets API

## 👩‍💻 Built By

Sheila Kimani — Software Engineering Student, MMU Kenya  
Built at the n8n Nairobi Hackathon, June 2026
