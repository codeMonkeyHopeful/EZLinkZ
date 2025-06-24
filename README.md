# EZLinkZ

**EZLinkZ** is a Tampermonkey user script that allows you to quickly copy all hyperlink URLs (`href`s) from your current text selection on any webpage. It provides a visual toast notification, and lets you review copied links in a popup overlay. You can also customize the keyboard shortcut via a simple menu command.

---

## 🚀 Features

- ✅ Copy all selected link URLs with a single keyboard shortcut
- ✅ Configurable shortcut key via Tampermonkey menu
- ✅ Clean toast notification with a click-to-view popup of copied links
- ✅ Works on **any website**
- ✅ Uses Tampermonkey’s persistent storage to remember your custom shortcut

---

## 🔧 Installation

1. Install with **Tampermonkey** (if not already installed get [Tampermonkey](https://www.tampermonkey.net/)).
2. [Click here to install the script](https://github.com/codeMonkeyHopeful/EZLinkZ/raw/refs/heads/main/EZLinkZ.user.js) _(direct install link)_.
3. Alternatively, go to the [GitHub repo](https://github.com/codeMonkeyHopeful/EZLinkZ) and install manually.

---

## ⌨️ Default Shortcut

Ctrl + Shift + C

You can change this shortcut anytime via the **Tampermonkey menu**:  
**Tampermonkey > EZLinkZ > Set Keyboard Shortcut**

Example input format:

Ctrl+Shift+X
Alt+C
Meta+Shift+Z

---

## 🖱️ How to Use

1. Select any portion of text on a webpage that contains links.
2. Press your configured shortcut key (default: Ctrl+Shift+C).
3. A toast will confirm how many links were copied.
4. Click the toast to view the copied links in a popup.
5. Click outside the popup or use the close button to dismiss it.

---

## 🛠️ Developer Notes

- Written in **vanilla JavaScript (ES6+)**
- Uses **DOM APIs** to interact with user selection and generate UI overlays
- No external libraries required
- Lightweight, fast, and self-contained

---

## 📮 Feedback & Issues

Found a bug or want to request a feature?  
[Open an issue on GitHub](https://github.com/codeMonkeyHopeful/EZLinkZ/issues)

---

## 📜 License

MIT License
© [CodeMonkeyHopeful](https://github.com/codeMonkeyHopeful)
