# ✓ TaskFlow Pro

<div align="center">

![TaskFlow Pro Banner](https://img.shields.io/badge/TaskFlow-Pro-4f7eff?style=for-the-badge&logo=checkmarx&logoColor=white)
![Version](https://img.shields.io/badge/version-4.0.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2B%20CSS%20%2B%20JS-orange?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=for-the-badge)

**A beautiful, feature-rich to-do app with login system, AI subtasks, Pomodoro timer, analytics and more — all in a single HTML file.**

[🚀 Live Demo](#) · [📖 Features](#-features) · [🛠 Installation](#-installation) · [🤝 Contributing](#-contributing)

</div>

---

## 📸 Preview

> *(Add a screenshot here — press `F12` → Mobile view → Screenshot)*

---

## ✨ Features

### 🔐 Auth & Security
- Multi-user **Sign Up / Sign In** system
- Passwords hashed with **SHA-256** via Web Crypto API
- Each user's data is fully **isolated** — no crossover
- All data stored **locally** — no servers, no tracking

### 📋 Task Management
- Create tasks with **priority** (High / Medium / Low), **due date**, **tags**, and **recurring** schedule
- Animated **strikethrough** when a task is completed
- **Subtasks** with individual checkboxes
- **Notes** per task
- **Pin** important tasks to the top
- **Drag to reorder** tasks
- **Archive** tasks instead of deleting permanently

### 🤖 AI-Powered
- **AI Subtask Generator** — click ✨ on any task and Claude AI breaks it into actionable steps automatically

### 🍅 Pomodoro Timer
- Start a focus timer directly from any task
- **25 min focus → 5 min short break → 15 min long break** cycle
- Visual ring progress indicator
- Session counter per day
- Browser notification support

### 📊 Analytics
- **14-day activity heatmap** (GitHub-style)
- **Priority donut chart** — high / medium / low breakdown
- **Weekly bar chart** — tasks completed per day
- **Streak counter** — daily completion streak 🔥

### 📂 Organization
- Multiple **lists** with custom color labels
- Delete lists (with confirmation modal)
- **Filter** tasks — All / Active / Done / High / Overdue / Pinned / Recurring
- **Sort** — Default / Priority / Due Date / A–Z / Newest
- **Live search** across tasks, tags, and notes

### ☐ Bulk Actions
- Select multiple tasks → **Complete All**, **Archive**, or **Delete**

### 📋 Templates
- Save your task structure as a reusable template
- Apply templates to any list instantly

### ⌨️ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `N` | Focus new task input |
| `F` | Focus search |
| `B` | Toggle bulk select |
| `A` | Open analytics |
| `T` | Open templates |
| `D` | Toggle dark/light theme |
| `1`–`5` | Switch list tabs |
| `Esc` | Close modals |
| `?` | Show all shortcuts |

### 💾 Persistence
- All data auto-saved to **localStorage**
- Survives page refresh — your tasks are always there

### 📤 Export
- Export any list as **CSV** or **plain text**

### 🎨 Theming
- Stunning **dark black-blue** theme by default
- Toggle to **light mode** with one click

---

## 🛠 Installation

### Option 1 — Use directly (no install needed)
1. Download `index.html`
2. Open it in any modern browser
3. Sign up and start using!

### Option 2 — GitHub Pages (live website)
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your app is live at `https://YOUR-USERNAME.github.io/taskflow-pro/`

### Option 3 — Clone & run locally
```bash
git clone https://github.com/YOUR-USERNAME/taskflow-pro.git
cd taskflow-pro
# Open index.html in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 📁 Project Structure

```
taskflow-pro/
├── index.html          # The entire app (single file)
├── README.md           # This file
├── LICENSE             # MIT License
├── CONTRIBUTING.md     # How to contribute
├── CHANGELOG.md        # Version history
├── .gitignore          # Git ignore rules
└── assets/             # (optional) screenshots
    └── preview.png
```

---

## 🧠 How It Works

TaskFlow Pro is intentionally a **single-file app** — no frameworks, no build tools, no dependencies. Everything runs in the browser:

- **Auth** — usernames + SHA-256 hashed passwords stored in `localStorage` under a namespaced key
- **Data** — each user's tasks, lists, history, and settings are stored as JSON in `localStorage`
- **AI** — calls the Anthropic Claude API directly from the browser for subtask generation
- **Crypto** — uses the native `window.crypto.subtle` API for password hashing
- **Charts** — drawn with native `<canvas>` API, no chart libraries needed

---

## ⚠️ Limitations

| Limitation | Why |
|---|---|
| Data is device-specific | No backend server — data lives in your browser |
| No cross-device sync | Would require a server/database |
| AI feature needs API key | Anthropic API is called client-side |
| Not suitable for sensitive data | localStorage is not encrypted at rest |

---

## 🤝 Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Ideas for contributions:**
- Backend server (Node.js + MongoDB) for cloud sync
- Mobile PWA support (service worker + manifest)
- Dark/light theme improvements
- More chart types in analytics
- Due date reminder notifications

---

## 📜 Changelog

See [CHANGELOG.md](CHANGELOG.md) for full version history.

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

## 🙌 Acknowledgements

- [Anthropic Claude](https://anthropic.com) — AI subtask generation
- [Google Fonts](https://fonts.google.com) — Inter & Sora typefaces
- [Web Crypto API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API) — password hashing

---

<div align="center">
Made with ❤️ · <a href="#">Live Demo</a> · <a href="#">Report Bug</a> · <a href="#">Request Feature</a>
</div>
