# 💰 Budgetor — Smart Budget Tracker

A beautiful, production-grade personal budget tracking app built as a **single HTML file** with zero dependencies. Dark-mode-first fintech-inspired design with glassmorphism cards, smooth animations, and interactive Chart.js visualizations.

🔗 **[Live Demo](https://yourusername.github.io/budgetor/)** ← _replace with your GitHub Pages URL_

---

## ✨ Features

- **Transaction Management** — Add, edit, and delete income & expenses with categories, dates, and notes
- **Dashboard** — KPI cards showing total income, expenses, and balance with monthly breakdown
- **Charts & Reports** — Doughnut chart (expenses by category), bar chart (monthly income vs expenses), line chart (daily spending trend)
- **Filters & Search** — Filter by date range, category, type + live keyword search
- **Budget Alerts** — Set monthly spending limits with visual warnings at 80% and 100%
- **Categories** — 11 built-in categories + add your own custom categories
- **Dark / Light Mode** — Toggle between refined dark and clean light themes
- **CSV Export & Import** — Download all transactions as CSV or import from CSV files
- **Responsive** — Works on desktop, tablet, and mobile (375px+)
- **Offline-Ready** — All data stored in localStorage, works without internet after first load

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure & semantic markup |
| CSS3 | Glassmorphism, animations, responsive layout, CSS variables for theming |
| Vanilla JavaScript | State management, DOM manipulation, localStorage persistence |
| [Chart.js](https://www.chartjs.org/) | Interactive data visualizations |
| [Google Fonts](https://fonts.google.com/) | DM Serif Display, Inter, JetBrains Mono |

**No frameworks. No build tools. No backend. Just open and use.**

## 🚀 Getting Started

1. **Download** or clone this repo
2. **Open** `index.html` in any modern browser
3. Start tracking your budget!

```bash
git clone https://github.com/yourusername/budgetor.git
cd budgetor
# Just open index.html in your browser — that's it!
```

## 📁 Project Structure

```
budgetor/
├── index.html    # The entire app — HTML + CSS + JavaScript
└── README.md     # This file
```

## 💾 Data Storage

All data is stored in your browser's `localStorage`:
- Transactions, categories, budget limits, and theme preference persist across sessions
- Data is private to your browser — nothing is sent to any server
- Use the **Export** feature in Settings to back up your data as CSV

## 📄 License

MIT License — free to use, modify, and distribute.

---

