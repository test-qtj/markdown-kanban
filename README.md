# 📋 Markdown Kanban

> A beautiful, local-first kanban board in a **single HTML file**. Drag-and-drop, Markdown, dark mode, no signup, no server.

<p align="center">
  <img src="https://img.shields.io/badge/single%20file-HTML-orange.svg" alt="Single HTML file">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License">
  <img src="https://img.shields.io/badge/no%20build%20step-zero-blue.svg" alt="No build step">
</p>

## ✨ Features

- 🎯 **Single HTML file** — open in any browser, it just works
- 🖱️ **Drag & drop** — move cards between columns, reorder columns
- ✍️ **Full Markdown** — write cards in Markdown, rendered live
- 🌓 **Dark mode** — auto-detects system preference, toggle with `Ctrl+T`
- 💾 **Local-first** — everything saved to localStorage, no account needed
- 📥 **Export/Import** — backup your board as JSON
- ⌨️ **Keyboard shortcuts** — `Ctrl+N` new card, `Ctrl+T` theme, `Esc` close
- 📱 **Responsive** — horizontal scroll on mobile, works everywhere

## 🚀 Quick Start

```bash
# Option 1: Open directly
open index.html

# Option 2: Serve locally
python -m http.server 8080
# Open http://localhost:8080

# Option 3: Drop it on any static host
# Netlify, Vercel, GitHub Pages, S3...
```

That's it. No `npm install`, no build step, no server required.

## 🎮 Usage

| Action | How |
|--------|-----|
| **Add card** | Click `+ Add card` at the bottom of any column |
| **Edit card** | Click any card to open the editor |
| **Move card** | Drag and drop between columns |
| **Reorder column** | Drag the column header |
| **Add column** | Click `+ Add Column` on the right |
| **Rename column** | Click ✏️ on the column header |
| **Delete column** | Click 🗑️ on the column header |
| **Export** | Click 📥 Export in the top bar |
| **Import** | Click 📤 Import and select a JSON file |
| **Dark mode** | Click 🌓 or press `Ctrl+T` |

## 🏗️ Tech Stack

- **Zero dependencies** (except `marked.js` CDN for Markdown rendering)
- **Native HTML5 Drag & Drop API** — no library needed for DnD
- **CSS Custom Properties** — clean theme switching
- **localStorage** — instant persistence, no backend

## 📄 License

MIT — use it, fork it, share it.

---

⭐ **Star this repo** if you find it useful! No build step, no config, no excuses.
