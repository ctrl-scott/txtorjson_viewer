ChatGPT Link: https://chatgpt.com/share/68f15a22-84d8-800c-b512-7bfef8e1825c

ChatGPT Canvas Link - https://chatgpt.com/canvas/shared/68f16102d53481919e74e09bd9f5ebe1

Offline version with embedded Constitution from U.S. Senate and Cornell L.I.I. per ChatGPT recommendation for modernized labeling and punctuation.

---

```markdown
# 🗽 Constitution Navigator — Clean Offline App

**Constitution Navigator** is an entirely offline, single-page HTML application that allows users to import, explore, and annotate the **United States Constitution** (or other structured historical/legal texts) without requiring internet access.  
It supports `.json`, `.txt`, and `.md` files and runs locally in any modern web browser.

---

## 📦 Features

- **Offline-first design** — no network requests, all logic runs in-browser.  
- **Smart import** — accepts:
  - Normalized JSON (`{ sequence, nodes }` schema)
  - Structured JSON (`{ preamble, articles[], amendments[] }`)
  - Well-formed plain text or Markdown transcriptions
- **Navigation controls** — arrow keys (← / →) or on-screen buttons for paging.
- **Sidebar TOC** — collapsible Table of Contents for Articles and Amendments.
- **Search and highlighting** — fast keyword search across all sections.
- **Annotations system** — add, edit, and export notes for each section.
- **Compare view** — side-by-side display of original vs. amended text.
- **Bookmarks** — save and jump to favorite sections.
- **HTML export** — save the current section as a standalone HTML fragment.
- **Light/Dark theme** toggle.
- **Self-test module** — runs internal diagnostics on parsing and features.
- **Reset option** — clear localStorage, notes, and bookmarks.

---

## 🧭 Keyboard Shortcuts

| Key / Combo | Action |
|--------------|---------|
| ← / → | Navigate previous / next section |
| `/` or `Ctrl/Cmd + K` | Focus search bar |
| `Enter` | Open top search result |
| `B` | Toggle bookmark |
| `P` | Toggle tools palette |
| `T` | Toggle Table of Contents |
| `C` | Toggle compare view |
| `Ctrl/Cmd + .` | Add a note |

---

## ⚙️ How to Use

1. **Open `index.html`** directly in your browser — no server required.
2. Click **📥 Import** or **drag-and-drop** a JSON/TXT/MD file into the page.
3. Use **← / →** to page through the document.
4. Press `/` or **Ctrl/Cmd + K** to search.
5. Add notes or annotations with **Ctrl/Cmd + .**
6. Export your notes or current section any time.

---

## 🧪 Self-Testing

Click **🧪 Self-test** to verify:
- Dataset structure
- Navigation and wrapping
- Search functionality
- Export routines
- Notes persistence

The test log will appear within the page.

---

## 🗂️ File Structure

```

constitution-navigator/
├── index.html         # Main offline app (single file)
├── constitution.json  # Optional normalized JSON bundle
└── README.md          # This file

````

---

## 🧱 JSON Structure Example

```json
{
  "meta": { "title": "United States Constitution", "source": "Public domain" },
  "sequence": [
    { "kind": "preamble", "id": "preamble" },
    { "kind": "article", "num": 1, "section": 1, "id": "art1-sec1" },
    { "kind": "amendment", "num": 1, "id": "am1" }
  ],
  "nodes": {
    "preamble": {
      "title": "Preamble",
      "text": "We the People of the United States..."
    },
    "art1-sec1": {
      "title": "Article I, Section 1",
      "text": "All legislative Powers herein granted..."
    },
    "am1": {
      "title": "Amendment I",
      "text": "Congress shall make no law respecting..."
    }
  }
}
````

---

## 📘 License

This project and its bundled transcriptions are in the **Public Domain (CC0 1.0 Universal)**.
Attribution is appreciated but not required.

---

## 👨‍💻 Author



*Developed collaboratively with ChatGPT-5 (2025).*

```

---

```
