# VSCode Vim-Style Keybindings

This repository contains my custom VSCode keybindings that enhance productivity with Vim-like shortcuts and terminal management.

## 🎯 Features

### Terminal Management
- `Ctrl+Shift+A` - Focus next terminal
- `Ctrl+Shift+B` - Focus previous terminal
- `Ctrl+Shift+J` - Toggle terminal panel
- `Ctrl+Shift+N` - Create new terminal
- `Ctrl+Shift+W` - Kill current terminal

### File Explorer
- `Ctrl+E` - Toggle sidebar visibility / Focus file explorer
- `n` - Create new file (when file explorer is focused)
- `Shift+N` - Create new folder (when file explorer is focused)
- `Shift+N` - Open new window (when not in file explorer)
- `r` - Rename file (when file explorer is focused)
- `d` - Delete file (when file explorer is focused)

### Additional Features
- `Ctrl+Shift+5` - Match HTML/XML tag
- `Ctrl+Z` - Toggle Zen Mode
- `Ctrl+F` - Search in settings (when in settings editor and not in Insert mode)

## 🚀 Installation

1. Open VSCode
2. Press `Ctrl+Shift+P` to open the command palette
3. Type "Open Keyboard Shortcuts (JSON)"
4. Copy the contents of `keybindings.json` from this repository to your VSCode keybindings file

## 💡 Notes

- Some keybindings are context-sensitive and only work in specific situations (e.g., terminal focus, file explorer focus)
- These bindings are designed to work alongside Vim extension for VSCode
- All keybindings can be customized by modifying the `keybindings.json` file

## 🤝 Contributing

Feel free to fork this repository and adapt these keybindings to your workflow. If you have suggestions for improvements, please open an issue or submit a pull request.

## 📝 License

This project is open source and available under the MIT License. 