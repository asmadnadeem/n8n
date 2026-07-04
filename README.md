# 🤖 n8n Automation Projects
> A collection of AI automation workflows built with n8n during my 2026 learning journey.
---
## 📁 Projects
### ✅ Week 1 — Auto Email Reply Workflow
**What it does:**  
A form submission triggers an automatic personalized email reply to whoever fills it out.
**How it works:**  
1. User fills out a form (name, email, message)  
2. n8n receives the submission  
3. Gmail node automatically sends a personalized reply using their name  
**Tools used:** `n8n` `Gmail`  
---
### ✅ Week 2 — AI-Powered Freelance Client Intake & Management System
**What it does:**  
A fully automated client intake system that uses AI to qualify leads, log data, and send personalized responses — without any manual work.
**How it works:**  
1. Client fills out an intake form (name, email, project type, budget, description)
2. Google Gemini AI analyzes the inquiry and returns a lead score, complexity rating, and recommendation
3. If lead score is low → automatic polite rejection email sent
4. If lead score is high → lead logged to Google Sheets, onboarding email sent to client, notification sent to me
**Nodes used:** `Form Trigger` `Set` `HTTP Request` `Code` `IF` `Google Sheets` `Gmail x3`  
**Tools used:** `n8n` `Google Gemini API` `Google Sheets` `Gmail`  
---
## 🛠 Tech Stack
- [n8n](https://n8n.io) — Workflow automation
- Google Gemini API — AI lead analysis
- Gmail — Email delivery
- Google Sheets — Data logging
