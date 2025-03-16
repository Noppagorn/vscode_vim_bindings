# VSCode Vim Bindings

A collection of Vim keybindings and settings for Visual Studio Code, VSCode Insiders, and Cursor IDE.

## Features

- Vim-style navigation and editing
- Optimized for Windows
- Compatible with VSCode, VSCode Insiders, and Cursor IDE
- Preserves existing settings while adding Vim functionality

## Installation

### Manual Installation

1. **Backup your current settings** (recommended):
   - Copy your existing `settings.json` and `keybindings.json` from your IDE's user settings directory
   - Store them in a safe location

2. **Install the Vim extension**:
   - Open VSCode/Cursor
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "Vim"
   - Install "Vim" by vscodevim

3. **Copy the configuration files**:
   - Copy `settings.json` to your IDE's user settings directory:
     - VSCode: `%APPDATA%\Code\User\settings.json`
     - VSCode Insiders: `%APPDATA%\Code - Insiders\User\settings.json`
     - Cursor: `%APPDATA%\Cursor\User\settings.json`
   - Copy `keybindings.json` to your IDE's user settings directory:
     - VSCode: `%APPDATA%\Code\User\keybindings.json`
     - VSCode Insiders: `%APPDATA%\Code - Insiders\User\keybindings.json`
     - Cursor: `%APPDATA%\Cursor\User\keybindings.json`

4. **Restart your IDE** for the changes to take effect

## Key Features

- **Normal Mode Navigation**:
  - `h`, `j`, `k`, `l` for movement
  - `w`, `b` for word navigation
  - `0`, `$` for line start/end
  - `gg`, `G` for file start/end

- **Visual Mode**:
  - `v` for character-wise selection
  - `V` for line-wise selection
  - `Ctrl+v` for block selection

- **Insert Mode**:
  - `i` for insert before cursor
  - `a` for insert after cursor
  - `o` for new line below
  - `O` for new line above

- **Command Mode**:
  - `:` for command mode
  - `w` to save
  - `q` to quit
  - `wq` to save and quit

## Customization

Feel free to modify the `settings.json` and `keybindings.json` files to suit your preferences. The current configuration is optimized for Windows users but can be adapted for other operating systems.

## Troubleshooting

If you experience any issues:

1. Make sure the Vim extension is installed and enabled
2. Check if there are any conflicting keybindings in your IDE
3. Verify that the configuration files are in the correct location
4. Try restarting your IDE

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details. 