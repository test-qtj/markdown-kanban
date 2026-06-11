# 📋 Markdown Kanban

> A beautiful, local-first kanban board in a **single HTML file.** Drag & drop cards, write in Markdown, toggle dark mode. No signup, no server, no build step.

<p align="center">
  <img src="https://img.shields.io/badge/single%20file-HTML-orange.svg" alt="Single HTML file">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License">
  <img src="https://img.shields.io/badge/no%20build%20step-zero-blue.svg" alt="No build step">
  <img src="https://img.shields.io/badge/offline%20ready-yes-success.svg" alt="Offline ready">
</p>

## ✨ Features

- 🎯 **Single HTML file** — open `index.html` in any browser and it just works
- 🖱️ **Drag & drop** — move cards between columns, reorder columns, native HTML5 DnD API
- ✍️ **Full Markdown** — write card bodies in Markdown with live preview in the editor
- 🌓 **Dark mode** — auto-detects system preference, toggle with `Ctrl+T` or the 🌓 button
- 💾 **Local-first** — everything saved to `localStorage`, zero data leaves your machine
- 📥 **Export / Import** — backup and restore your board as a single JSON file
- ⌨️ **Keyboard shortcuts** — `Ctrl+N` new card, `Ctrl+T` toggle theme, `Esc` close modal, `/` search (coming soon)
- 📱 **Responsive** — horizontal scroll layout works on desktop, tablet, and mobile
- 🔌 **Offline ready** — only CDN dependency is `marked.js` for rendering; caches in browser after first load

## 🚀 Quick Start

```bash
# Option 1: Open directly
open index.html

# Option 2: Serve locally (if CDN doesn't load)
python -m http.server 8080
# → http://localhost:8080

# Option 3: Drop it anywhere
# Netlify, Vercel, GitHub Pages, S3, or just double-click it
```

That's it. **No `npm install`. No build step. No server required.**

## 🎮 Usage Guide

| Action | How |
|--------|-----|
| **Add a card** | Click the `+ Add card` button at the bottom of any column |
| **Edit a card** | Click any card to open the editor modal |
| **Move a card** | Drag and drop the card to another column |
| **Reorder cards** | Drag within a column to change order |
| **Reorder columns** | Drag the column header left or right |
| **Add a column** | Click the `+ Add Column` button on the far right |
| **Rename a column** | Click ✏️ on the column header |
| **Delete a column** | Click 🗑️ on the column header (also deletes all cards inside) |
| **Delete a card** | Hover over a card → click ×, or use the delete button in the editor |
| **Export board** | Click 📥 **Export** in the top bar → downloads `kanban-export.json` |
| **Import board** | Click 📤 **Import** → select a previously exported JSON file |
| **Reset board** | Click 🗑️ **Reset** to restore the default demo board |
| **Dark mode** | Click 🌓 in the top bar or press `Ctrl+T` |
| **Markdown preview** | In the card editor, click the **Preview** tab |

## 🏗️ Tech Stack

| Concern | Solution |
|---------|----------|
| Structure | HTML5 |
| Styling | CSS Custom Properties (no preprocessor) |
| Interactivity | Vanilla JavaScript (no framework) |
| Drag & Drop | Native [HTML5 Drag and Drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API) |
| Markdown | [marked.js](https://marked.js.org/) via CDN (auto-cached) |
| Persistence | `localStorage` with JSON serialization |
| Theme | CSS custom property swap on `<html class="dark">` |

**Zero framework. Zero build tools. Zero dependencies** (except the optional marked.js CDN).

## 🔒 Privacy

Everything stays in your browser. No analytics, no tracking, no server — the board data lives in `localStorage` and only leaves your device when you explicitly export it.

## 🤝 Contributing

Pull requests are welcome! Ideas:
- Multi-board support (switch between boards)
- Card colors / labels
- Due dates and reminders
- WebDAV / GitHub Gist sync backends
- Offline marked.js bundling for fully offline use

## 📄 License

MIT © 2024 — use it, fork it, share it.

---

⭐ **Star this repo** if you've ever wanted a Trello-like board without creating an account!
