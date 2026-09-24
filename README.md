# AMX Mod X Pawn Syntax

Sublime Text syntax highlighting for **AMX Mod X Pawn** (`.sma` and `.inc` files), with dedicated support for ReAPI, standard natives, preprocessor directives, and Pawn constructs.

## ✨ Features

- **AMX Mod X & ReAPI Highlight:** Recognizes Pawn 3.2 keywords, types, tags (`Float:`, `bool:`, `any:`), and ReAPI natives.
- **File Extensions:** Automatically applies to `.sma`, `.inc`, and `.pwn` files.
- **Scope:** Provides `source.pawn` (standard scope compatible with linters and LSP).
- **Sublime Text 4:** Built using modern `.sublime-syntax` (compatible with Build 4000+).

## 🚀 Installation

### Via Package Control (Recommended)
1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`).
2. Select **Package Control: Install Package**.
3. Search for **`AMX Mod X Pawn Syntax`** and press Enter.

### Manual Installation
1. Clone this repository into your Sublime Text `Packages` directory:
   ```bash
   # Windows
   git clone https://github.com/NiceFeatures/sublime-pawn-syntax.git "%APPDATA%\Sublime Text\Packages\sublime-pawn-syntax"
   
   # Linux
   git clone https://github.com/NiceFeatures/sublime-pawn-syntax.git ~/.config/sublime-text/Packages/sublime-pawn-syntax
   ```
2. Restart Sublime Text.

## 🔌 Language Server & Autocomplete
For complete IDE features including autocompletion with parameter documentation, Go to Definition (`F12`), hover tooltips, and 1-click `amxxpc` compilation, install **[LSP-pawnforge](https://github.com/NiceFeatures/LSP-pawnforge)**.

## 📜 License
GPL-3.0 License. See [LICENSE.txt](LICENSE.txt) for details.
