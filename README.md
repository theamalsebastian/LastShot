# ⚡ Last-Minute Life Saver

> AI-powered productivity co-pilot that helps you beat deadlines, prioritize tasks, and build winning habits.

**Built for Vibe2Ship Hackathon** · [Live Demo](https://last-minute-lifesaver.vercel.app)

## Features

- 🔴 **Urgency Heat Rings** — visual countdown rings on every task showing time vs completion
- 🤖 **AI Co-pilot** — streaming AI chat powered by Groq (Llama 3.3 70B) or OpenRouter, free
- 📊 **Smart Priority Scoring** — auto-ranks tasks by urgency × effort ratio
- 🔥 **Habit Tracker** — 7-day grid with streak counting
- ⚡ **Voice Input** — speak your tasks and queries
- 💾 **LocalStorage Persistence** — your data survives page refreshes
- 📱 **Responsive** — works on mobile and desktop

## Tech Stack

React 19 · Vite · Groq API (Llama 3.3 70B) · OpenRouter · CSS Modules

## Getting Started

```bash
git clone https://github.com/theamalsebastian/last-minute-lifesaver
cd last-minute-lifesaver
npm install
npm run dev
```

Then open the app, click **"Ask AI"**, and add your free [Groq API key](https://console.groq.com).

## Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/theamalsebastian/last-minute-lifesaver)

Or manually:
```bash
npm i -g vercel
vercel --prod
```
