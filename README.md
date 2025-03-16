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

## Detailed Key Bindings and Settings

### Vim Settings
- `vim.leader`: Set to `<Space>` (Space key)
- `vim.hlsearch`: Enabled for better search highlighting
- `vim.handleKeys`: Custom handling for Ctrl+F

### Normal Mode Key Bindings
#### Navigation
- `<Space>h`: Focus left group
- `<Space>j`: Focus below group
- `<Space>k`: Focus above group
- `<Space>l`: Focus right group
- `<Space>ne`: Open file explorer
- `Shift+h`: Previous buffer
- `Shift+l`: Next buffer

#### Window Management
- `<Space>v`: Vertical split
- `<Space>s`: Horizontal split

#### File Operations
- `<Space>w`: Save file
- `<Space>q`: Quit
- `<Space>x`: Save and quit

#### Code Navigation
- `[d`: Previous diagnostic
- `]d`: Next diagnostic
- `gh`: Show definition preview hover

#### Quick Actions
- `<Space>ca`: Quick fix
- `<Space>f`: Quick open
- `<Space>p`: Format document

### Visual Mode Key Bindings
- `<`: Outdent lines
- `>`: Indent lines
- `J`: Move lines down
- `K`: Move lines up
- `<Space>c`: Toggle comment

### Terminal Key Bindings
- `Ctrl+Shift+a`: Focus next terminal
- `Ctrl+Shift+b`: Focus previous terminal
- `Ctrl+Shift+j`: Toggle panel
- `Ctrl+Shift+n`: New terminal
- `Ctrl+Shift+w`: Kill terminal

### File Explorer Key Bindings
- `Ctrl+e`: Toggle sidebar visibility
- `n`: New file
- `r`: Rename file
- `Shift+n`: New folder
- `d`: Delete file

### Editor Settings
- `editor.formatOnSave`: Enabled
- `editor.inlineSuggest.enabled`: Enabled
- `editor.linkedEditing`: Enabled
- `editor.lineNumbers`: Relative
- `editor.minimap.enabled`: Disabled
- `editor.suggest.insertMode`: Replace

### UI Settings
- `workbench.statusBar.visible`: Hidden
- `workbench.activityBar.location`: Hidden
- `breadcrumbs.enabled`: Disabled
- `window.zoomLevel`: 0.5
- `workbench.iconTheme`: material-icon-theme

### Language-Specific Settings
- Python: Format on type enabled
- TypeScript/TSX: Prettier as default formatter
- JSON: Prettier as default formatter
- JavaScript: Auto-update imports on file move

### Git Settings
- `git.autofetch`: Enabled

### Zen Mode
- `Ctrl+z`: Toggle zen mode
- `zenMode.hideLineNumbers`: Disabled 