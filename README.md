# VS Code config

Configuration for Visual Studio Code.

## User level

Settings that apply to the user.

VS Code finds them at [either of the following directories, based on the OS][vscode-settings]:

- Linux: `$HOME/.config/Code/User/`
- Mac OS: `$HOME/Library/Application Support/Code/User/`
- Windows: `%APPDATA%\Code\User\`

In this repository, the **user** directory mimics the directory structure that VS Code expects. For example, the content of `settings.json` file in this directory can be used in the actual user level `settings.json` file.

- `snippets` directory (language-specific code snippets)
- `keybindings.json` file (keyboard shortcuts)
- `settings.json` file (settings)

## Workspace level

Settings that apply to the workspace (higher priority than user level settings).

VS Code finds them at `${workspaceFolder}/.vscode/`

In this repository, the **workspace** directory contains example settings. For example, the content of `settings_python.json` file in this directory can be used in the actual workspace level `settings.json` file.

- `extensions*.json` files (extension recommendations, for `extensions.json` file)
- `settings*.json` files (settings, for `settings.json` file)

[vscode-settings]: https://code.visualstudio.com/docs/getstarted/settings#_settings-file-locations
