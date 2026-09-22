# 🧠 MEMO — Interactive Memory Card Match Game

MEMO is a high-polish, browser-based cognitive memory training game featuring 3D card-flip animations, interactive combo multipliers, synthesized Web Audio sound effects, and persistent player statistics.

---

## 🛠️ Tech Stack

- **Frontend & Visuals:** Semantic HTML5, CSS3 (3D CSS Transforms, `perspective`, `backface-visibility`, Glassmorphism, Ambient Floating Particle Canvas)
- **Engine:** Vanilla JavaScript (ES6+, Fisher-Yates Card Shuffle, Game Loop, State Machines)
- **Audio:** Web Audio API (`AudioContext`, Oscillator nodes) for procedural synthesized sound effects without external MP3/WAV assets
- **Storage:** Browser `localStorage` for offline profile persistence and high-score leaderboards
- **Deployment:** GitHub Pages

---

## ✨ Features

- 🃏 **Multiple Card Themes & Difficulties:**
  - Card sets across diverse categories: Tech Icons, Animals, Space, Nature, Food, and Emojis.
  - Adaptive difficulty levels tailored for quick casual rounds or intense memory challenges.

- 🎵 **Zero-Asset Procedural Audio:**
  - Card flips, matching chimes, mismatch thuds, and victory fanfares are synthesized live in code via the browser's Web Audio API.

- ⚡ **Combos, Scoring & Hint Mechanics:**
  - **Dynamic Combo Multiplier:** Consecutive matches award exponential bonus points.
  - **Hint Power-Ups:** Reveal matching card locations when stuck.
  - **Memorization Countdown:** Initial card preview window before cards hide.

- 📊 **Statistics, Profiles & Achievements:**
  - Multi-profile player system with personalized avatars.
  - Tracks total games played, win rate, best times, lowest move counts, and unlockable achievement badges.

- ⌨️ **Desktop Keyboard Controls:**
  - `Space` or `P`: Pause / Resume game.
  - `H`: Activate hint power-up.
  - `R`: Quick restart round.

---

## 🚀 Live Demo

Play MEMO live in your browser:  
👉 **[https://akhil-tech258.github.io/Game/](https://akhil-tech258.github.io/Game/)**
