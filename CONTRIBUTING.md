# 🤝 Contributing to TaskFlow Pro

Thank you for your interest in contributing! Every contribution helps make TaskFlow Pro better for everyone.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Pull Request Process](#pull-request-process)
- [Style Guide](#style-guide)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)

---

## 📜 Code of Conduct

By participating in this project, you agree to:
- Be respectful and inclusive
- Welcome newcomers and beginners
- Focus on constructive feedback
- Avoid harassment of any kind

---

## 💡 How Can I Contribute?

### 🐛 Bug Reports
Found something broken? [Open an issue](../../issues/new?template=bug_report.md) with:
- A clear description of the problem
- Steps to reproduce it
- Your browser and OS
- Screenshots if possible

### ✨ Feature Requests
Have an idea? [Open an issue](../../issues/new?template=feature_request.md) describing:
- What you want and why
- How it would benefit other users
- Any similar apps/tools that do this

### 🔧 Code Contributions
Want to write code? Great! Pick an open issue or propose a new one first.

---

## 🚀 Getting Started

Since TaskFlow Pro is a **single HTML file**, there's no build setup needed:

```bash
# 1. Fork the repo on GitHub (click the Fork button)

# 2. Clone your fork
git clone https://github.com/YOUR-USERNAME/taskflow-pro.git
cd taskflow-pro

# 3. Create a branch for your change
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-bug-fix

# 4. Open index.html in your browser and make changes
# Use browser DevTools (F12) for debugging

# 5. Test your changes thoroughly in:
#    - Chrome / Edge
#    - Firefox
#    - Safari (if possible)
#    - Mobile browser

# 6. Commit your changes
git add .
git commit -m "feat: add your feature description"

# 7. Push to your fork
git push origin feature/your-feature-name

# 8. Open a Pull Request on GitHub
```

---

## 🔄 Pull Request Process

1. **One feature per PR** — keep pull requests focused
2. **Update README.md** if you add a new feature
3. **Update CHANGELOG.md** with your change under `[Unreleased]`
4. **Test in multiple browsers** before submitting
5. **Describe your changes** clearly in the PR description
6. PRs are reviewed within 3–5 days

### PR Title Format
```
feat: add pomodoro long break setting
fix: prevent delete on last list
docs: update keyboard shortcuts table
style: improve mobile layout
refactor: clean up render function
```

---

## 🎨 Style Guide

Since this is a vanilla HTML/CSS/JS project:

### HTML
- Use semantic elements where possible
- Keep inline styles minimal — prefer CSS variables
- Add `title` attributes to icon buttons for accessibility

### CSS
- Use CSS custom properties (`--var`) for all colors and sizes
- Follow the existing naming convention: `.task-card`, `.chk-box`, `.pom-btn` etc.
- Mobile-first for any new UI components
- Add transitions for interactive elements

### JavaScript
- Keep functions small and focused
- Use `camelCase` for variables and functions
- Add a comment for any non-obvious logic
- Always call `saveUD()` after mutating state
- Always call `render()` after saving

### Commit Messages
Follow [Conventional Commits](https://www.conventionalcommits.org/):
```
feat:     new feature
fix:      bug fix
docs:     documentation only
style:    formatting, no logic change
refactor: code restructure, no feature change
perf:     performance improvement
test:     adding tests
chore:    build process or tooling
```

---

## 🐛 Reporting Bugs

When reporting a bug, please include:

```markdown
**Describe the bug**
A clear description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '...'
3. See error

**Expected behavior**
What you expected to happen.

**Screenshots**
If applicable, add screenshots.

**Environment:**
- OS: [e.g. Windows 11, macOS Ventura]
- Browser: [e.g. Chrome 120, Firefox 121]
- Device: [e.g. Desktop, iPhone 15]
```

---

## 💬 Suggesting Features

When suggesting a feature:

```markdown
**Is your feature request related to a problem?**
A clear description of the problem. E.g. "I'm always frustrated when..."

**Describe the solution you'd like**
A clear description of what you want to happen.

**Describe alternatives you've considered**
Any alternative solutions or features you've considered.

**Additional context**
Any other context, mockups, or screenshots.
```

---

## 🏆 Recognition

All contributors will be listed in the README.md Contributors section. Thank you for helping make TaskFlow Pro better! 🎉
