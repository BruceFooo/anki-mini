# Anki mimi

- [中文](./README_cn.md)

## 🚀 Overview
A VS Code extension for Anki card review, built on [Anki‑Sidebar](https://github.com/tszones/Anki‑Sidebar).  
Supports dark mode, color inversion, and keyboard shortcuts for seamless Anki integration.

## ✅ Features
- 🖼️ Image color inversion for dark mode compatibility
- ⏱️ Timer and progress tracking with status bar
- 📝 Markdown export of Anki cards
- 🔄 Keyboard shortcuts for card navigation
- 📚 Deck management and review tracking

## 📦 Installation
1. [Install VS Code](https://code.visualstudio.com/)
2. [Install the extension from VS Marketplace](https://marketplace.visualstudio.com/items?itemName=frunoob.ankimini)
3. Configure AnkiConnect API and other options in `settings.json`:

   ```json
   {
     // AnkiConnect listen address
     "ankiview.api": "http://localhost:8765",

     // Font size used in the side‑view (px)
     "ankiview.fontSize": 11,

     // Show/hide the answer button (default false)
     "ankiview.showButton": false,

     // Warning time multiplier (needs reload)
     "ankiview.TimeBar.warnThreshold": 0.66
   }
   ```

## ⌨️ Keybindings
| Action | Default key (Windows/Linux) | macOS |
|--------|-----------------------------|-------|
| Show answer | Ctrl+Alt+` | `Space` |
| Undo | `Ctrl+Alt+Z` | `⌘+Z` |
| Ease 1 | `Ctrl+Alt+1` | `⌘+1` |
| Ease 2 | `Ctrl+Alt+2` | `⌘+2` |
| Ease 3 | `Ctrl+Alt+3` | `⌘+3` |
| Ease 4 | `Ctrl+Alt+4` | `⌘+4` |

> **Tip** – If you prefer custom keybindings, edit the `keybindings.json` file in VS Code.

## 🧪 Usage
- Press `Space` (macOS) or "ctrl+alt+`" (Win/Linux) to reveal the answer.
- Use `⌘+1/2/3/4` (macOS) or `Ctrl+Alt+1/2/3/4` (Win/Linux) to mark the card with the chosen ease.
- View statistics in the status bar.

## 🛠️ Contributing
1. Fork the repo  
2. Create a feature/bugfix branch  
3. Test changes locally  
4. Submit a PR

## 📄 License
[Apache 2.0](LICENSE)