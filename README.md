# 🎮 Lua Mentor — Game Modding Study Guide

> An interactive senior mentor for learning Lua through game modding. Self-paced, multilingual, with daily tracking and PDF export.

![Lua Mentor](https://img.shields.io/badge/Language-Lua-blue?style=flat-square)
![Languages](https://img.shields.io/badge/UI-ES%20%7C%20EN%20%7C%20PT%20%7C%20FR-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

---

## ✨ Features

- 🧑‍💻 **AI Mentor persona** — adaptive feedback based on quiz score
- 🌍 **4 languages** — English, Español, Português, Français
- 📅 **10 structured days** across 3 weeks (expandable to 60 days)
- 🎮 **Game modding focus** — Roblox, Garry's Mod, Factorio examples
- 📝 **Interactive quizzes** with automatic evaluation
- 💻 **Code exercises** with official solutions
- 📊 **Daily progress tracking** (saved in browser)
- 📄 **PDF export** — progress report with all scores and submitted code
- ⚡ **Zero dependencies** — single HTML file, runs anywhere

---

## 🚀 Quick Start

### Option 1: Just open the file
```bash
# Download and open directly in your browser
open lua-mentor.html
```

### Option 2: Local server (recommended)
```bash
git clone https://github.com/YOUR_USERNAME/lua-mentor
cd lua-mentor
npx serve .          # Node.js
# OR
python -m http.server 8000   # Python
# Then open: http://localhost:8000/lua-mentor.html
```

### Option 3: Replit (no install)
1. Go to [replit.com](https://replit.com) → New Repl → **HTML, CSS, JS**
2. Delete default files → Upload `lua-mentor.html`
3. Rename to `index.html` → Click **Run**
4. Share the Replit URL with your community 🎉

### Option 4: GitHub Pages (free hosting)
```bash
git clone https://github.com/YOUR_USERNAME/lua-mentor
# Rename lua-mentor.html to index.html
git add . && git commit -m "Deploy Lua Mentor"
git push origin main
# Go to Settings → Pages → Source: main branch
# Your URL: https://YOUR_USERNAME.github.io/lua-mentor
```

---

## 📚 Curriculum

| Week | Theme | Days | Topics |
|------|-------|------|--------|
| 1 | 🏗️ Foundations | 1–5 | Intro, Variables, Operators, Conditionals, Loops |
| 2 | ⚙️ Functions & Tables | 6–8 | Functions, Tables, OOP with Metatables |
| 3 | 🏛️ Architecture | 9–10 | Modules, Error Handling |
| 4–8 | *(coming soon)* | 11–60 | Coroutines, Events, Networking, Roblox API, Garry's Mod... |

---

## 🧑‍💻 How the Mentor Works

The AI mentor evaluates quiz results and gives adaptive feedback:

| Score | Action |
|-------|--------|
| 100% | 🏆 Advance immediately |
| 80–99% | ✅ Advance, review missed questions |
| 60–79% | 🔄 Reread theory, then advance |
| < 60% | 📚 Restart the day's theory |

---

## 🌍 Language Support

Switch language at any time from the header dropdown. Progress and names are preserved across language switches.

| Language | Code | Status |
|----------|------|--------|
| English | `en` | ✅ Full |
| Español | `es` | ✅ Full |
| Português | `pt` | ✅ Full |
| Français | `fr` | ✅ Full |

---

## 📄 PDF Export

Click **Export PDF** in the header to generate a progress report including:
- Day-by-day quiz scores
- Overall statistics (average, best, worst)
- All submitted code exercises
- Personalized recommendations

---

## 🤝 Contributing

Pull requests welcome! To add content:

1. Open `lua-mentor.html`
2. Find the `curriculum` object in the `<script>` section
3. Add new days following the existing structure:

```javascript
{
  day: 11,
  title: "Coroutines",
  obj: "Learn async patterns for game events",
  theory: `...`,
  examples: [{ title: "...", code: `...`, note: "..." }],
  exercises: [{ q: "...", hint: "...", sol: `...` }],
  quiz: [
    { q: "Question?", opts: ["A","B","C","D"], c: 0 }  // c = correct index
  ]
}
```

---

## 📬 Share with your Discord Community

Post this in your server:

```
🎮 FREE Lua Game Modding Course — Interactive Mentor

Learn Lua for Roblox, Garry's Mod & Factorio modding!
✅ 4 languages (EN/ES/PT/FR)
✅ Daily exercises with mentor feedback  
✅ Quiz-based progress tracking
✅ No install needed (runs in browser)

## 📝 License

MIT — Free to use, modify and distribute. Attribution appreciated!

---

*Built with ❤️ for the modding community*
