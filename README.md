# VSCode Vim-Style Keybindings

This repository contains my custom VSCode keybindings that enhance productivity with Vim-like shortcuts and terminal management.

## 🎯 Features

### Space Key (Leader) Bindings
The Space key is configured as the leader key (`vim.leader`). Here are the available commands:

#### Navigation
- `Space + v` - Split vertically
- `Space + s` - Split horizontally
- `Space + h` - Focus left pane
- `Space + j` - Focus pane below
- `Space + k` - Focus pane above
- `Space + l` - Focus right pane
- `Space + n + e` - Open file explorer
- `Shift + h` - Previous buffer
- `Shift + l` - Next buffer

#### File Operations
- `Space + w` - Save file
- `Space + q` - Quit
- `Space + x` - Save and quit
- `Space + f` - Quick open file
- `Space + p` - Format document

#### Code Actions
- `Space + c + a` - Quick fix
- `[ + d` - Go to previous error/warning
- `] + d` - Go to next error/warning
- `g + h` - Show definition preview hover

#### Visual Mode
- `<` - Outdent lines (stays in visual mode)
- `>` - Indent lines (stays in visual mode)
- `J` - Move lines down
- `K` - Move lines up
- `Space + c` - Toggle comment

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