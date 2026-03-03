# Quill
Premium Web WordPad

Quill is a modern, production-ready rich text editor built with pure HTML, CSS, and Vanilla JavaScript.

It delivers a refined, Apple-inspired interface with advanced editing tools, theme support, autosave, zoom control, file export, and more — all running fully in the browser.

---

## 🚀 Features

### 📝 Rich Text Editing
- Bold, Italic, Underline, Strikethrough
- Text alignment (Left, Center, Right, Justify)
- Ordered & Unordered lists
- Insert links, images, tables
- Line spacing control
- Clear formatting

### 🎨 Advanced Font System
- 50+ Google Fonts integrated
- Live preview font picker
- Font size selection
- Text color & highlight color

### 🌗 Theme System
- Light mode
- Dark mode
- Sepia mode
- System theme detection

### 💾 Storage & Autosave
- Automatic local autosave
- Save documents to browser storage
- Recent documents list
- Word & character count
- Zoom persistence

### 📂 File Operations
- New document
- Open `.html` and `.txt` files
- Save as HTML
- Save as TXT
- Export as PDF (via browser print)

### 🔎 Productivity Tools
- Find & Replace with live highlighting
- Floating contextual toolbar
- Keyboard shortcuts
- Undo / Redo
- Page breaks
- Modal-based insert dialogs

### 📐 Premium UI
- Apple-inspired minimal design
- Smooth animations
- Responsive layout
- Clean design tokens system
- CSS-based theme engine
- Backdrop blur effects

---

## 🛠️ Tech Stack

- **HTML5** – Semantic structure
- **CSS3** – Design system & theming
- **Vanilla JavaScript (ES6+)** – Modular architecture
- **LocalStorage API** – Persistence
- **document.execCommand** – Rich text operations

No frameworks. No dependencies. Fully standalone.

---

## 📁 Project Structure

```
.
├── index.html     # Main application UI
├── styles.css     # Design system & themes
└── script.js      # Editor core logic
```

---

## ⚙️ How to Run

1. Download or clone the repository
2. Open `index.html` in your browser

That’s it. No build tools required.

---

## 💡 Architecture Overview

The editor is modularly structured inside `script.js`:

- ThemeManager
- ZoomManager
- Storage (Autosave & Recent Docs)
- Editor Core
- Find & Replace Engine
- File Operations
- Modal System
- Floating Toolbar
- Insert Utilities

State is centrally managed and persisted where necessary.

---

## Possible Enhancements

- Markdown mode
- Real-time collaboration
- Plugin system
- Cloud sync
- Offline PWA support
- Desktop packaging (AppImage / Electron)
- Custom theme builder

---

## License

Open-source —> free to modify and extend.

