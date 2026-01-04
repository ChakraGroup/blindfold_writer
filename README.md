# Blindfold Writer

A **distraction-free, browser-based writing app** with typewriter and blindfold modes.  
Runs entirely client-side and saves directly to a local text file.

---

## ✨ Overview

**Minimal Writer** is a lightweight, single-file web application designed for focused writing. It removes distractions and editing temptations by offering **append-only writing modes**, including a blindfold mode that hides text as you type.

There is **no backend, no cloud sync, no tracking, and no dependencies**. Your writing stays on your machine.

Once a file is selected, the editor **autosaves directly to disk**, making it ideal for long writing sessions without manual exports.

---

## ✍️ Writing Modes

### Normal Mode
- Standard text editing
- Full cursor movement and editing

### Typewriter Mode (Append-Only)
- Text can only be added at the end
- Deletion and mid-text edits are blocked
- Caret stays vertically centered for a classic typewriter feel

### Blindfold Mode (Append-Only, Hidden Text)
- Text is invisible while typing
- Cursor remains visible
- Encourages uninterrupted flow and first-draft writing

---

## 💾 File Saving & Autosave

- Uses the **File System Access API**
- Click **Save As…** once to choose a `.txt` file
- After that:
  - Changes are **autosaved automatically**
  - Manual save via button or `Ctrl/Cmd + S`
- File writes occur directly on your local filesystem

> ⚠️ Supported in **Chrome and Edge** (HTTPS required)

---

## 📊 Features

- Single-file HTML app
- Autosave with debounce
- Word and character count
- Append-only enforcement
- Safe paste and drop handling
- Writing mode persistence via LocalStorage
- Minimal UI with system fonts
- Works offline after initial load

---

## 🚀 Getting Started

### Run Locally
1. Download `index.html`
2. Open it in **Chrome or Edge**
3. Click **Save As…** to choose a file
4. Start writing

---

## 📄 License

MIT License  
Free to use, modify, and distribute.

---


