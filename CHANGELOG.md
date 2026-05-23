# 📋 Changelog

All notable changes to TaskFlow Pro are documented here.

Format based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Versioning follows [Semantic Versioning](https://semver.org/).

---

## [Unreleased]
> Changes staged for the next release

---

## [4.0.0] — 2026-05-23

### 🎉 Major Release — TaskFlow Pro

### Added
- 🎨 **Black-blue theme** — complete redesign with deep navy and electric blue palette
- 🤖 **AI Subtask Generator** — Claude AI breaks any task into actionable subtasks
- 🍅 **Pomodoro Timer** — floating widget with focus/short/long break cycles and session counter
- 📊 **Analytics Panel** — 14-day heatmap, priority donut chart, weekly bar chart
- 🔥 **Streak Counter** — daily completion streak shown in the header
- ☐ **Bulk Actions** — select multiple tasks to complete, archive, or delete at once
- 📋 **Task Templates** — save and reuse task structures across lists
- 🗂 **Archive** — archive tasks instead of permanently deleting; restore anytime
- 🔁 **Recurring Tasks** — daily, weekly, or monthly task repeat
- 🎨 **List Color Labels** — assign custom colors when creating lists
- ⌨️ **Keyboard Shortcuts** — full power-user keyboard navigation
- 🔔 **Browser Notifications** — Pomodoro timer completion alerts
- 🌐 **Export to CSV & Text** — download any list

### Changed
- Complete UI redesign — new card layout, glow effects, animated progress bar
- Priority badges now show as colored left-border stripes on task cards
- Expanded task panel redesigned with cleaner sections

### Fixed
- Checkbox animation timing smoothed out
- Drag-and-drop no longer triggers expand on drop

---

## [3.0.0] — 2026-05-20

### Added
- 🔐 **Multi-user login system** — Sign Up / Sign In with SHA-256 password hashing
- 👤 **User chip** in header showing avatar and username
- 🔒 **Per-user data isolation** — each account has completely separate data
- 🗑 **Delete list** — hover a list tab to reveal delete button with confirmation modal
- 🎨 **List color dots** on tab bar

### Changed
- Data storage migrated to per-user namespaced keys in localStorage

---

## [2.0.0] — 2026-05-18

### Added
- ✨ **Animated strikethrough** on task completion (CSS transition)
- 💫 **Ripple effect** on checkbox when completing a task
- 🌙 **Dark mode** (deep green dark theme) with toggle
- 🖱️ **Drag to reorder** tasks
- 📌 **Pin tasks** to keep them at the top
- 📝 **Subtasks** with individual checkboxes per task
- 🗒️ **Notes** field per task
- 📅 **Due dates** with overdue/today/tomorrow smart labels
- 🏷️ **Tags** with search support
- 📊 **Weekly productivity chart** (canvas bar chart)
- 📤 **Export** to CSV and plain text
- 🎉 **Confetti** animation when all tasks in a list are done
- 📋 **Multiple lists** (Personal, Work, Shopping)
- 🔍 **Live search** across tasks, tags, and notes
- 🔀 **Sort** by priority, due date, A-Z, newest
- 🎛️ **Filter** pills — All, Active, Done, High, Overdue, Pinned
- 💾 **localStorage persistence**
- 📊 **Stats cards** — Total, Done, Remaining, Overdue
- 📈 **Animated progress bar**

### Changed
- Complete UI redesign from basic to premium aesthetic

---

## [1.0.0] — 2026-05-15

### Added
- ✅ Basic to-do list with add, complete, delete
- 🟢🟡🔴 Priority levels (Low, Medium, High)
- 📊 Simple stats (total, done, remaining)
- 🔵 Filter by All / Active / Done / High Priority
- 💅 Clean green-themed UI

---

[Unreleased]: https://github.com/YOUR-USERNAME/taskflow-pro/compare/v4.0.0...HEAD
[4.0.0]: https://github.com/YOUR-USERNAME/taskflow-pro/compare/v3.0.0...v4.0.0
[3.0.0]: https://github.com/YOUR-USERNAME/taskflow-pro/compare/v2.0.0...v3.0.0
[2.0.0]: https://github.com/YOUR-USERNAME/taskflow-pro/compare/v1.0.0...v2.0.0
[1.0.0]: https://github.com/YOUR-USERNAME/taskflow-pro/releases/tag/v1.0.0
