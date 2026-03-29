# ⚡ Focus Board — Daily Productivity Tracker

A clean, beautiful, single-file productivity app built with pure HTML, CSS & JavaScript. No frameworks. No installs. Just open and go.

![Focus Board Preview](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-purple?style=flat-square) ![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red?style=flat-square)

> Made with ❤️ by **PRIYAM**

---

## ✨ Features

- **Eisenhower Matrix** — Organize tasks into 4 quadrants: Do First, Schedule, Delegate, Drop
- **3 Views** — Matrix, List, and Focus mode
- **🍅 Pomodoro Timer** — Built-in 25-minute focus timer per task
- **Daily Motivational Quotes** — A fresh quote every day, auto-rotated
- **Personalized Welcome** — Greets you by name (saved to localStorage)
- **⭐ Star Tasks** — Pin important tasks to your Focus view
- **Task Search** — Filter tasks instantly in List view
- **Progress Bar** — Live win-rate tracker in the header
- **Stats Strip** — See Q1 pending, completed count, win rate & starred tasks
- **Confetti Celebration** — Satisfying animation when you complete a task
- **Reset Day** — One-click reset to start fresh (with timer safety fix)
- **Fully Responsive** — Works great on mobile and desktop
- **Zero dependencies** — Single HTML file, works offline

---

## 🚀 Getting Started

### Option 1 — Open directly
Just download `index.html` and open it in any browser. That's it.

### Option 2 — GitHub Pages (recommended)
1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app will be live at `https://yourusername.github.io/focus-board`

### Option 3 — Clone & run locally
```bash
git clone https://github.com/yourusername/focus-board.git
cd focus-board
open index.html   # macOS
# or
start index.html  # Windows
```

---

## 🗂️ Project Structure

```
focus-board/
├── index.html        # The entire app — HTML + CSS + JS in one file
├── README.md         # You're reading this
├── LICENSE           # MIT License
├── .gitignore        # Git ignore rules
└── .github/
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        └── feature_request.md
```

---

## 🧩 How It Works

### Eisenhower Matrix Quadrants

| Quadrant | Label | Description |
|----------|-------|-------------|
| 🔥 Q1 | Do First | Urgent & Important |
| 📅 Q2 | Schedule | Important, Not Urgent |
| 🤝 Q3 | Delegate | Urgent, Not Important |
| 🧊 Q4 | Drop/Later | Not Urgent, Not Important |

### Views
- **⊞ Matrix** — Classic 2×2 grid layout
- **≡ List** — All tasks in one list with search
- **◎ Focus** — Only your Q1 + starred tasks

### Pomodoro Timer
Click the 🍅 icon on any task to start a 25-minute focus session. Pause, resume, or stop at any time.

---

## 🛠️ Customization

Since everything is in `index.html`, customization is easy:

**Change Pomodoro duration** — find `TOTAL_SECS=1500` and change `1500` (seconds) to your preferred duration.

**Add your own quotes** — find the `QUOTES` array in the `<script>` section and add objects like:
```js
{text: "Your quote here.", author: "— Author Name"},
```

**Change color theme** — edit the CSS variables in `:root {}` at the top of the `<style>` block.

---

## 📸 Screenshots

> _Add your own screenshots here after deploying!_

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

Please use the issue templates for bug reports and feature requests.

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

<div align="center">Made with ❤️ by <strong>PRIYAM</strong></div>
