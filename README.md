# 🎯 LastShot

> Your last shot at getting things done.

**LastShot** is an AI-powered productivity co-pilot built for students and professionals who work best under pressure. It moves beyond passive reminders — giving you real-time urgency signals, streaming AI coaching, and habit tracking in one command-center interface.

**Built for [Vibe2Ship Hackathon](https://vibe2ship.com)** · [Live Demo →](https://last-minute-lifesaver1.vercel.app)

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔴 **Urgency Heat Rings** | Circular progress rings on every task — color shifts red → gold → green based on time left vs completion |
| 🤖 **Streaming AI Co-pilot** | Real-time AI chat with full task context — plans your day, breaks down tasks, beats procrastination |
| 📊 **Smart Priority Scoring** | Auto-ranks tasks using `(hours needed ÷ hours remaining) × 100` — surfaces what you're most at risk of missing |
| 🔥 **Habit Streak Tracker** | 7-day completion grid with streak counting and AI habit analysis |
| 🎙️ **Voice Input** | Speak tasks and queries via Web Speech API |
| ⚡ **Context-aware AI Banner** | Dynamic insight panel that changes based on overdue/critical/safe states |
| 💾 **Persistent Storage** | localStorage-backed state — survives page refreshes |

---

## 🛠 Tech Stack

- **Frontend:** React 19, Vite, CSS Modules
- **AI:** Groq API (Llama 3.3 70B) — free tier, 14,400 req/day
- **Fallback AI:** OpenRouter (free models)
- **Deployment:** Vercel

---

## 🚀 Getting Started

```bash
git clone https://github.com/theamalsebastian/last-minute-lifesaver
cd last-minute-lifesaver
npm install
npm run dev
```

Open the app → click **Ask AI** → add your free [Groq API key](https://console.groq.com) → done.

> Groq is 100% free, no credit card needed. Sign up at console.groq.com → API Keys → Create Key.

---

## 📦 Deploy Your Own

```bash
npm i -g vercel
vercel --prod --yes
```

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/theamalsebastian/last-minute-lifesaver)

---

## 🏗 Project Structure

```
src/
├── components/
│   ├── AIPanel.jsx        # Streaming AI chat with provider switcher
│   ├── AIBanner.jsx       # Context-aware insight banner
│   ├── TaskCard.jsx        # Expandable task card with heat ring
│   ├── HeatRing.jsx        # SVG urgency ring component
│   ├── HabitTracker.jsx    # 7-day habit grid
│   ├── StatsBar.jsx        # Live stats (critical/done/streak)
│   └── AddTaskModal.jsx    # Task creation form
├── hooks/
│   └── useTaskStore.js     # localStorage-backed task + habit state
├── utils/
│   ├── aiService.js        # Groq + OpenRouter streaming API
│   └── taskUtils.js        # Urgency scoring, priority ranking
└── data/
    └── defaults.js         # Sample tasks and habit data
```

---

## 👤 Author

**Amal Sebastian** — Final-year CS student, Kerala, India  
Azure AI-102 Certified · Building in AI/ML & Full-Stack  
[GitHub](https://github.com/theamalsebastian) · [LinkedIn](https://linkedin.com/in/theamalsebastian)

---

*Built in one session for Vibe2Ship Hackathon.*
