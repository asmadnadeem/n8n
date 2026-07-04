# 🤖 n8n Automation Projects

> Building real AI automation systems — from simple workflows to multi-node intelligent pipelines.

---

## 📁 Projects

### ✅ Week 1 — Automated Email Reply System

**What it does:**  
Eliminates manual follow-up emails. The moment someone submits a form, they get a personalized reply — instantly, automatically, zero human involvement.

**How it works:**  
1. User fills out a form (name, email, message)
2. n8n captures the submission in real time
3. Gmail node fires a personalized reply using their name dynamically

**Tools used:** `n8n` `Gmail`

---

### ✅ Week 2 — AI-Powered Freelance Client Intake & Management System

**What it does:**  
A fully intelligent client management pipeline. It doesn't just collect inquiries — it reads them, scores them with AI, makes decisions, and acts on them. No manual screening, no copy-pasting, no missed leads.

**How it works:**  
1. Client submits an intake form with project details and budget
2. Data is cleaned and structured automatically
3. Google Gemini AI analyzes the inquiry — returns a lead score (1–10), complexity rating, and recommendation
4. Low score → personalized rejection email sent automatically
5. High score → lead logged to Google Sheets with timestamp, onboarding email sent to client, instant notification sent to me with full AI summary
6. Everything tracked, nothing manual

**Nodes used:** `Form Trigger` `Set` `HTTP Request` `Code` `IF` `Google Sheets` `Gmail ×3`  
**Tools used:** `n8n` `Google Gemini API` `Google Sheets` `Gmail`

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| [n8n](https://n8n.io) | Workflow automation engine |
| Google Gemini API | AI-powered lead analysis |
| Gmail | Automated email delivery |
| Google Sheets | Lead logging and tracking |

---

## 👤 Author

**Asmad Nadeem**  
BSCS @ FAST-NUCES CFD  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/YOUR-HANDLE)
