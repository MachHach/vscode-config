# VSCode config

Configuration for Visual Studio Code.

- [User level][vscode-settings]:
    - Linux: `$HOME/.config/Code/User/`
    - Mac OS: `$HOME/Library/Application Support/Code/User/`
    - Windows: `%APPDATA%\Code\User\`
- Workspace level: `./.vscode/`

```yaml
# User level
user:
    # Code snippets
    - snippets
    # Keyboard shortcuts
    - keybindings.json
    # Settings
    - settings.json

# Workspace level
workspace:
    # Extension recommendations (extensions.json)
    - extensions*.json
    # Settings (settings.json)
    - settings*.json
```

[vscode-settings]: https://code.visualstudio.com/docs/getstarted/settings#_settings-file-locations
