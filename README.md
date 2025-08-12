# Smart To-Do — AI-Powered Task Manager

Smart To-Do is a lightweight, browser-based to-do list app with **AI-powered task suggestions**, drag-and-drop reordering, and offline support.

![Smart To-Do Screenshot](preview.png)

---

## ✨ Features

- **Add, edit, delete tasks** instantly
- **AI Suggest** — get helpful task ideas for work, fitness, learning, travel, and more
- **Offline support** — tasks are saved locally in your browser
- **Drag & drop reordering** for easy prioritization
- **No sign-up required** — open and start using

---

## 🚀 Getting Started

### Open Locally
1. Download `index.html`
2. Double-click to open it in your browser

### Deploy Online
You can deploy to **Netlify** or **Vercel** in minutes:
- [Netlify quick deploy](https://app.netlify.com/start)
- [Vercel quick deploy](https://vercel.com/new)

---

## 🧠 AI Suggest Feature

By default, Smart To-Do uses a **built-in heuristic** to generate suggestions offline.  
You can connect it to **OpenAI** for real AI-generated tasks:

1. Get an [OpenAI API key](https://platform.openai.com/account/api-keys)
2. Replace `OPENAI_API_KEY = null` in `index.html` with your key  
   (**⚠️ Security warning:** Don’t put API keys in client-side code for production — use a server proxy)
3. Uncomment the fetch request in the AI Suggest section

---

## 📷 Social Media Preview

When deployed, Smart To-Do shows a nice preview card with title, description, and screenshot when shared on WhatsApp, LinkedIn, or Twitter/X.

Example Open Graph card:
