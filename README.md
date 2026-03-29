<div align="center">

# ⚡ Focus Board

### Your ruthless daily productivity tracker

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-focus--board--theta.vercel.app-845EF7?style=for-the-badge)](https://focus-board-theta.vercel.app/)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-e05a6e?style=for-the-badge)](https://github.com/priyam)
[![License: MIT](https://img.shields.io/badge/License-MIT-20C997?style=for-the-badge)](./LICENSE)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-FFA940?style=for-the-badge)](#)

**[🌐 Open App →](https://focus-board-theta.vercel.app/)**

</div>

---

## 📸 Preview

> **[➡️ Try it live: https://focus-board-theta.vercel.app/](https://focus-board-theta.vercel.app/)**

Focus Board is a zero-dependency, single-file productivity app powered by the **Eisenhower Matrix** method. No sign-up, no installs, no clutter — just open and start crushing your day.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🧩 **Eisenhower Matrix** | 4-quadrant system: Do First, Schedule, Delegate, Drop |
| 🔍 **3 Views** | Matrix grid, flat List with search, and laser Focus mode |
| 🍅 **Pomodoro Timer** | Built-in 25-min focus timer on any task, with pause & resume |
| 💡 **Daily Quotes** | A fresh motivational quote every single day, auto-rotated |
| 👋 **Personalized Greeting** | Remembers your name across sessions via localStorage |
| ⭐ **Star Tasks** | Pin high-priority tasks to the Focus view |
| 📊 **Live Stats** | Win rate, pending Q1 count, completions & starred tasks |
| 🎉 **Confetti Celebration** | Satisfying animation every time you complete a task |
| ↺ **Reset Day** | One-click full reset — safely stops the timer too |
| 📱 **Fully Responsive** | Works beautifully on mobile, tablet and desktop |
| ⚡ **Zero Dependencies** | Pure HTML + CSS + JS — works completely offline |

---

## 🗂️ Project Structure

```
focus-board/
├── index.html        ← The entire app (HTML + CSS + JS in one file)
├── README.md         ← You're reading this
├── LICENSE           ← MIT License
├── .gitignore        ← Git ignore rules
└── .github/
    ├── workflows/
    │   └── deploy.yml               ← Auto-deploy to GitHub Pages
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        └── feature_request.md
```

---

## 🚀 Getting Started

### ▶️ Just use it
**[https://focus-board-theta.vercel.app/](https://focus-board-theta.vercel.app/)** — open and go, nothing to install.

### 💾 Run locally
```bash
git clone https://github.com/yourusername/focus-board.git
cd focus-board
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### ☁️ Deploy your own fork
```bash
# 1. Fork this repo on GitHub
# 2. Connect to Vercel or enable GitHub Pages
# 3. Done — it deploys automatically on every push
```

---

## 🧩 The Eisenhower Matrix

The app is built around the **Eisenhower Matrix** — a proven method for prioritizing tasks by urgency and importance.

```
                  URGENT          NOT URGENT
             ┌──────────────┬──────────────────┐
  IMPORTANT  │  🔥 Q1       │  📅 Q2           │
             │  DO FIRST    │  SCHEDULE        │
             ├──────────────┼──────────────────┤
NOT IMPORTANT│  🤝 Q3       │  🧊 Q4           │
             │  DELEGATE    │  DROP / LATER    │
             └──────────────┴──────────────────┘
```

---

## 🛠️ Customization

Everything lives in `index.html` — open it in any editor and tweak away.

**Change Pomodoro duration**
```js
const TOTAL_SECS = 1500; // 1500 = 25 min, 2700 = 45 min
```

**Add your own daily quotes**
```js
const QUOTES = [
  { text: "Your quote here.", author: "— Author Name" },
  // ...
];
```

**Restyle the theme** — edit the CSS variables in `:root {}` at the top of the `<style>` block.

---

## 🤝 Contributing

All contributions are welcome — bug fixes, new features, UI tweaks.

1. Fork the repo
2. Create your branch: `git checkout -b feature/awesome-feature`
3. Commit changes: `git commit -m 'Add awesome feature'`
4. Push: `git push origin feature/awesome-feature`
5. Open a Pull Request

Please use the issue templates for bug reports and feature requests.

---

## 📄 License

Licensed under the **MIT License** — see [LICENSE](./LICENSE) for details. Free to use, modify and distribute.

---

<div align="center">

Made with ❤️ by **PRIYAM**

⭐ Star this repo if it helped you stay focused!

</div>
