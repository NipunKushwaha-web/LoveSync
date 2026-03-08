# Project Valentine

Minimal web app for couples to test their compatibility.
No signup.
No backend.
Just clean results.

<img width="1918" height="978" alt="Screenshot 2026-03-08 193831" src="https://github.com/user-attachments/assets/3123eb2c-be3f-4248-8cfe-6b556a654190" />

---

## Live Demo
https://valentinesync.netlify.app/

---

## Features
- **10-question relationship quiz** covering conflict, love language, communication & more
- **Dual person mode** — each partner answers separately
- **Compatibility score** with animated counter (0-100%)
- **Radar chart** showing category breakdown
- **Confetti celebration** for scores 70%+
- **Subtle sound effects** via Web Audio API
- Download results as **PNG** (Story 9:16 or Square 1:1)
- Progress saved to **local storage**
- Fully responsive (mobile-first)
- Full keyboard accessibility
- No authentication
- No ads
- No tracking

---

## Tech Stack
- React (Vite)
- Tailwind CSS
- html2canvas (PNG export)
- Web Audio API (sounds)
- Vercel (static deploy)

---

## How It Works
1. Click **Start Test**
2. Person A answers 10 questions
3. Person B answers the same questions
4. Click **View Results** to see compatibility score
5. Download and share your result card

> All processing happens client-side. Nothing is uploaded.

---

## Privacy
All processing happens **locally in your browser**.
No data is sent to any server.
Your answers never leave your device.

---

## Installation
```bash
# Clone the repo
git clone https://github.com/NipunKushwaha-web/LoveSync

# Install dependencies
cd love-sync
npm install

# Run locally
npm run dev
```
