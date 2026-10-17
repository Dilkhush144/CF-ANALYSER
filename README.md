# 📊 Codeforces Stats Analyzer

<p align="center">
  <strong>Analyze user performance • Track rating progress • Inspect contest & problem statistics</strong>
</p>

<p align="center">
  A modern, responsive web application for deep competitive programming analytics built with <strong>React</strong>, <strong>Material-UI</strong>, <strong>Tailwind CSS</strong>, and <strong>Recharts</strong>.
</p>

---

## 📌 Overview

**CF-ANALYSER** is an interactive analytics tool designed for competitive programmers on [Codeforces](https://codeforces.com/). It queries the official Codeforces Public API directly from the client side to provide comprehensive breakdowns of problem-solving activity, contest trajectories, accuracy distributions, and topic masteries.

---

## ✨ Features

- **⚡ Instant Handle Lookup**: Search any Codeforces handle with quick pre-filled tags (tourist, Benq, jiangly).
- **📈 Rating Growth & Contest History**: Interactive line and bar charts tracking contest rating movements, rank fluctuations, and performances across time periods.
- **🎯 Accuracy & Verdict Breakdowns**: Visualize practice vs. contest accuracy, acceptance rates, and submission breakdowns.
- **🏷️ Problem Tag & Topic Distribution**: Pie charts and ranking charts classifying solved problems by topics (dynamic programming, math, greedy, data structures, etc.).
- **📊 Rating-Wise Solved Count**: Inspect problem count solved categorized by Codeforces problem difficulty ratings (800 to 3500+).
- **🎨 Modern Dark Dashboard UI**: Polished interface with Material UI icons and responsive Tailwind layout.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React 18** | Modular UI component architecture |
| **Vite** | Fast development server and build tool |
| **Material-UI (@mui/material)** | Pre-styled modern UI elements & icons |
| **Recharts / MUI X-Charts** | Interactive visualizations and data graphing |
| **Tailwind CSS** | Utility-first styling & responsive layouts |
| **Codeforces API** | Real-time competitive programming data source |

---

## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Dilkhush144/CF-ANALYSER.git
cd CF-ANALYSER
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### 4. Build for production
```bash
npm run build
```

---

## 📁 Project Structure

```text
CF-ANALYSER/
├── public/
├── src/
│   ├── components/
│   │   ├── charts/        # Recharts & MUI graph components
│   │   ├── common/        # Shared StatCard, Section, LoadingPanel
│   │   ├── dashboard/     # Metric grids, profile strip, tag highlights
│   │   ├── layout/        # Hero, Topbar, Footer
│   │   └── search/        # Search bar & handle lookup
│   ├── constants/         # Default configurations & quick handles
│   ├── Data/              # Codeforces API fetch & data extraction helpers
│   ├── helpers/           # Analytics calculation algorithms
│   ├── hooks/             # Custom useCodeforcesAnalysis hook
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

## 👨‍💻 Author

### Dilkhush Raj
- **GitHub**: [@Dilkhush144](https://github.com/Dilkhush144)
- **Email**: [kdilkhush844@gmail.com](mailto:kdilkhush844@gmail.com)
- **LinkedIn**: [Dilkhush Raj](https://www.linkedin.com/in/dilkhush-raj)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).