# 🏥 CADx AI — Computer-Aided Diagnosis System

An AI-powered Computer-Aided Diagnosis (CADx) web application built with HTML, Tailwind CSS, and JavaScript, simulating IBM Watson NLU, IBM Text-to-Speech, and IBM Cloudant.

---

## 🚀 How to Run

### Option 1 — Open directly in browser
Just double-click `index.html` — no server needed.

### Option 2 — Open in VS Code with Live Server
1. Open this folder in VS Code
2. Install the **Live Server** extension (ritwickdey.LiveServer)
3. Right-click `index.html` → **Open with Live Server**

---

## 📁 Project Structure

```
cadx-ai-system/
├── index.html        ← Main single-page application
├── .env              ← Your private IBM API credentials (fill in)
├── .env.example      ← Safe-to-commit blank template
├── .gitignore        ← Ignores .env and node_modules
└── README.md         ← This file
```

---

## 🔑 IBM API Setup (Production)

Fill in `.env` with your credentials from [IBM Cloud](https://cloud.ibm.com):

| Service | Where to get key |
|---|---|
| Watson NLU | cloud.ibm.com → Natural Language Understanding |
| Watson TTS | cloud.ibm.com → Text to Speech |
| Cloudant | cloud.ibm.com → Cloudant |
| IAM | cloud.ibm.com → Manage → Access (IAM) |

---

## ⚙️ Features

- 🧠 **Watson NLU Simulation** — Extracts symptoms, risk level, severity
- 🔊 **IBM TTS Simulation** — Reads diagnosis aloud (Browser SpeechSynthesis)
- 🗄️ **Cloudant Simulation** — Saves/deletes records via localStorage
- 📊 **Dashboard** — Stats, weekly chart, recent cases
- 📋 **Patient Intake** — Full form with AI analysis
- 💾 **Saved Records** — Searchable table with CSV export
- ⚙️ **Settings** — API config panel + preferences toggles

---

## 🛠️ Tech Stack

- **HTML5 / CSS3 / JavaScript** (Vanilla, no framework)
- **Tailwind CSS** via CDN
- **Lucide Icons** via CDN
- **Google Fonts** — Syne + DM Mono
- **IBM Watson NLU** (simulated → production-ready comments inside code)
- **IBM Text-to-Speech** (simulated → Browser SpeechSynthesis API)
- **IBM Cloudant** (simulated → localStorage)

---

## 📌 Recommended VS Code Extensions

- **Live Server** — ritwickdey.LiveServer
- **Prettier** — esbenp.prettier-vscode
- **DotENV** — mikestead.dotenv
- **Tailwind CSS IntelliSense** — bradlc.vscode-tailwindcss

---

## ⚠️ Disclaimer

This application is for educational/demonstration purposes only.
Always verify AI-generated diagnoses with a licensed medical professional.
