# Extra Commands

Additional useful commands for VS Code.

## Features

### Save All Without Format

Saves all dirty files without running save participants (formatters, organizers, etc.).

- **Command**: `File: Save All Without Format`
- **Command ID**: `vscode-extra-commands.saveAllWithoutFormat`

This is useful when you want to save all files quickly without triggering automatic formatting.

### Create and Open Folder

Creates a new folder and opens it in VS Code.

- **Command**: `Create and Open Folder`
- **Command ID**: `vscode-extra-commands.createAndOpenFolder`

This command allows you to quickly create a new folder and open it in VS Code. You can choose to open it in the current window, a new window, or add it to the current workspace.

## Usage

1. Open the Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Windows/Linux)
2. Type "Save All Without Format"
3. Press Enter

You can also assign a keyboard shortcut to this command in your keybindings.json:

```json
{
  "key": "cmd+k s",
  "command": "vscode-extra-commands.saveAllWithoutFormat"
}
```
