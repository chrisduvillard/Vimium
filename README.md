# Vimium Custom Key Mappings

This repository documents my **Vimium** configuration for efficient browser navigation with a Swiss QWERTZ keyboard.  

---

## 📑 Configuration

```vimium
map ,p visitPreviousTab
map ; Marks.activateGotoMode
map m Marks.activateCreateMode
map ,s enterFindMode
unmap `
unmap /
```

---

## 🔑 Keybindings Overview

### 🌟 Cheat Sheet

| Keybinding      | Category  | Action                                                                          |
| --------------- | --------- | ------------------------------------------------------------------------------- |
| **`,p`**        | 🔄 Tabs   | Switch to the **previously used tab** (like `Alt+Tab` for browser tabs)         |
| **`,s`**        | 🔍 Search | Enter **find mode** to search text on current page                             |
| **`m{letter}`** | 🏷️ Marks | Create a **mark** at the current position (local: lowercase, global: uppercase) |
| **`;{letter}`** | 🏷️ Marks | Jump to a mark (replaces the awkward backtick `` ` `` default)                  |
| **`ma`**        | 🏷️ Marks | Set a **local mark** `a` (same page only)                                       |
| **`mA`**        | 🏷️ Marks | Set a **global mark** `A` (across pages/tabs)                                   |
| **`;a`**        | 🏷️ Marks | Jump to local mark `a`                                                          |
| **`;A`**        | 🏷️ Marks | Jump to global mark `A`                                                         |

---

## 🧭 Usage Notes

* **Local marks** (lowercase letters) work only within the same page.
* **Global marks** (uppercase letters) let you return to a page & scroll position, even across sites.
* Marks are **session-based**: closing the browser clears them.

---

## 📌 Why These Mappings?

* **`,p`** → ergonomic and memorable for "previous tab."
* **`,s`** → convenient search activation (replaces the default `/` which can be awkward).
* **`;`** → much easier than backtick on Swiss QWERTZ keyboards.
* Keeps navigation **fast, consistent, and Vim-like**.

---

## 🚀 Installation

1. Open Vimium options in your browser.
2. Scroll to **Custom key mappings**.
3. Paste in the mappings from [Configuration](#-configuration).
4. **Save changes** (important!) and reload your tabs.

---

✨ With these custom mappings, Vimium becomes smoother, faster, and more intuitive on a Swiss QWERTZ keyboard.

