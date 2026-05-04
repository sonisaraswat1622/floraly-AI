# Floraly — AI Cycle Intelligence

> **Your cycle, understood.**

A GenAI-powered period tracking Progressive Web App (PWA) that goes beyond basic symptom logging. Built with the Anthropic Claude API.

---

## Live Demo

**[Launch Floraly →](https://sonisaraswat1622.github.io/floraly-ai/index.html)**

---

## What makes Floraly different

Most period tracking apps (Clue, Flo, Natural Cycles) use rule-based algorithms. They predict your next period but can't explain *why* you feel the way you do, or tell you something meaningful about your specific patterns.

Floraly uses GenAI to do three things no existing app does:

### 1. Conversational AI with full cycle context
Ask Floraly anything in plain English — "why am I so tired this week?", "is my PMS getting worse?", "when is my next fertile window?" — and it responds using *your actual logged data*, not generic advice. The AI knows your cycle length, current phase, recent symptoms, and energy patterns.

### 2. Pattern intelligence
After logging daily symptoms, Floraly analyses your data to surface patterns like "your PMS symptoms start 6 days before your period, not the typical 2 days" or "your energy drops 47% in your luteal phase every cycle." This is the kind of insight that takes months of manual tracking to spot.

### 3. Doctor visit prep report
One tap generates a clinical summary — cycle stats, frequent symptoms, mood patterns, AI-flagged concerns, and 4 suggested questions to ask your doctor. Copy it to your clipboard and bring it to your next appointment.

---

## Features

| Feature | Description |
|---|---|
| Cycle wheel | Visual 28-day cycle with period, fertile, ovulation zones |
| Period logging | Log start date, duration, track history |
| Daily symptom log | Physical symptoms, mood, flow, energy slider, notes |
| AI Chat | Conversational AI with your full cycle context |
| Pattern insights | AI analysis of symptom trends, energy by phase, frequency map |
| Doctor report | Clinical cycle summary with flagged concerns |
| PWA | Installs on phone like a native app, works offline |
| Persistent storage | All data saved locally via localStorage |

---

## Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript — zero frameworks, zero dependencies
- **AI:** Anthropic Claude API (`claude-sonnet-4-20250514`)
- **Storage:** localStorage (client-side, private by default)
- **Hosting:** GitHub Pages
- **PWA:** Service worker, Web App Manifest, offline caching

---

## Install as an App

Floraly is a Progressive Web App — it installs on your phone like a native app:

**iPhone (iOS):**
1. Open the link in Safari
2. Tap the Share button
3. Tap "Add to Home Screen"
4. Tap "Add"

**Android:**
1. Open the link in Chrome
2. Tap the "Install Floraly" banner that appears
3. Or tap the three-dot menu → "Add to Home Screen"

---

## Running Locally

```bash
# Clone the repo
git clone https://github.com/sonisaraswat1622/floraly-ai.git
cd floraly-ai

# Serve locally (required for service worker)
npx serve .

# Open http://localhost:3000
```

---

## Using the AI Features

1. Get an Anthropic API key at [console.anthropic.com](https://console.anthropic.com)
2. Open Floraly and paste your key in the API key field at the top
3. Your key is stored locally in your browser — never sent anywhere except Anthropic's API

---

## Project Structure

```
floraly-ai/
├── index.html          # Complete app (single file)
├── manifest.json       # PWA manifest
├── sw.js               # Service worker (offline + caching)
├── README.md
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

---

## Why I Built This

Current period tracking apps have a fundamental limitation: they're observation tools, not intelligence tools. They record data but don't reason about it. GenAI changes that entirely.

As a Business Analyst with a background in banking analytics and a Post-Graduate Certificate in GenAI from UT Austin, I built Floraly to demonstrate:
- Applied GenAI product development
- User-centred design in an underserved health space
- Full-stack thinking from data model → AI integration → PWA deployment

---

## Built By

**Soni Saraswat** | Senior Business Analyst | MBA Business Analytics (GPA 3.92)
University of North Texas | Microsoft PL-300 | AI-900 | GenAI Certificate — UT Austin

[LinkedIn](https://linkedin.com/in/soni-saraswat) · [GitHub](https://github.com/sonisaraswat1622) · [Portfolio](https://sonisaraswat1622.github.io)

---

## Disclaimer

Floraly is not a medical device and does not provide medical advice. Always consult a qualified healthcare professional for health concerns.
