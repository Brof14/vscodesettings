#  VS Code Professional Setup (Windows)

> **Stack:** Go, Python, JavaScript/HTML
> **OS:** Windows
> **Philosophy:** Minimalist Interface, Keyboard-Centric, Eye-Friendly

This configuration is designed for senior-level productivity. It removes visual clutter, enforces strict code formatting per language, and provides ergonomic keybindings for Windows users.

##  Quick Start

1. Install VS Code.
2. Install the required extensions (see below).
3. Copy `settings.json` and `keybindings.json` into your VS Code user settings folder:
   - Windows: `%APPDATA%\Code\User\`
   - Or use `Ctrl+Shift+P` -> `Open User Settings (JSON)`.
4. Reload Window (`Ctrl+Shift+P` -> `Reload Window`).

## 📦 Required Extensions

| Extension | Publisher | Purpose |
|-----------|-----------|---------|
| **One Dark Pro** | binaryify | Best-in-class dark theme for eye comfort |
| **Material Icon Theme** | Philipp Kief | Clear, colorful file icons |
| **Go** | Google | IntelliSense, debugging, linting for Go |
| **Python** | Microsoft | IntelliSense, linting for Python |
| **Black Formatter** | Microsoft | Standard Python formatting |
| **Prettier** | Esben Petersen | Standard JS/HTML formatting |
| **JetBrains Mono Font** | Narasima Pandiyan | Best ligatures for coding |

## ⌨️ Keybindings Cheat Sheet

### Navigation
| Key | Action |
|-----|--------|
| `Ctrl + Tab` | Next Editor Tab |
| `Ctrl + Shift + Tab` | Previous Editor Tab |
| `Ctrl + B` | Go to Definition (Jump to source) |
| `Alt + Left/Right` | Navigate Back/Forward in history |

### File Management
| Key | Action |
|-----|--------|
| `A` | Create New File (in Explorer) |
| `Shift + A` | Create New Folder (in Explorer) |
| `Ctrl + Shift + E` | Toggle Sidebar / Focus Explorer |

### Editing
| Key | Action |
|-----|--------|
| `Alt + Enter` | Quick Fix / Auto-Import (Crucial for Go/Py) |
| `F2` | Rename Symbol (Refactor) |
| `Ctrl + D` (x2) | Delete Current Line |
| `Shift + Alt + Up/Down` | Copy Line Up/Down |

### System
| Key | Action |
|-----|--------|
| `Ctrl + `` ` | Toggle Terminal |
| `Ctrl + Shift + G` | Open Source Control (Git) |

## ⚙️ Language Specifics

- **Go:** Uses `gofmt` with Tabs. Auto-organizes imports on save.
- **Python:** Uses `Black` with 4 Spaces. PEP 8 compliant.
- **JavaScript/HTML:** Uses `Prettier` with 2 Spaces, no semicolons, single quotes.

## 🎨 Why this setup?

1. **Hidden Distractions:** Activity bar, status bar, and minimap are hidden to maximize code screen real estate.
2. **Smart Indentation:** Each language gets its native indentation style (Tabs for Go, Spaces for Python/JS).
3. **Windows Optimized:** All macOS `cmd` keys are replaced with `ctrl` or `alt` for natural Windows usage.