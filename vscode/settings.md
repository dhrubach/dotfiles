# IDE Setup Configurations

## Editor Flags

---

```json
    "editor.formatOnSave": true,
    "editor.formatOnSaveMode": "file",
    "editor.find.cursorMoveOnType": false,
    "workbench.editor.decorations.colors": true,
    "workbench.editor.decorations.badges": true,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "workbench.editor.enablePreview": false,
    "workbench.startupEditor": "newUntitledFile",
```

## Integrated Terminal

---

```json
 "terminal.integrated.profiles.windows": {
    "PowerShell": {
        "source": "PowerShell",
        "icon": "terminal-powershell"
    },
    "Command Prompt": {
        "path": [
        "${env:windir}\\Sysnative\\cmd.exe",
        "${env:windir}\\System32\\cmd.exe"
    ],
        "args": [],
        "icon": "terminal-cmd"
    },
    "Git Bash": {
        "source": "Git Bash"
    }
 },
 "terminal.integrated.defaultProfile.windows": "Git Bash",
 "terminal.external.windowsExec": "C:\\Program Files\\Git\\git-bash.exe",
```

## Misc IDE Settings

---

```json
    "files.eol": "\n",
    "git.suggestSmartCommit": false,
    "git.autofetch": true,
    "scm.alwaysShowRepositories": true,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "always",
    "diffEditor.ignoreTrimWhitespace": false,
    "window.zoomLevel": 0,
    "explorer.confirmDragAndDrop": false
```

## Extensions

---

### Peacock

```json
    "peacock.favoriteColors": [
        {
            "name": "Angular Red",
            "value": "#b52e31"
        },
        {
            "name": "Auth0 Orange",
            "value": "#eb5424"
        },
        {
            "name": "Azure Blue",
            "value": "#007fff"
        },
        {
            "name": "C# Purple",
            "value": "#68217A"
        },
        {
            "name": "Gatsby Purple",
            "value": "#639"
        },
        {
            "name": "Go Cyan",
            "value": "#5dc9e2"
        },
        {
            "name": "Java Blue-Gray",
            "value": "#557c9b"
        },
        {
            "name": "JavaScript Yellow",
            "value": "#f9e64f"
        },
        {
            "name": "Mandalorian Blue",
            "value": "#1857a4"
        },
        {
            "name": "Node Green",
            "value": "#215732"
        },
        {
            "name": "React Blue",
            "value": "#00b3e6"
        },
        {
            "name": "Something Different",
            "value": "#832561"
        },
        {
            "name": "Vue Green",
            "value": "#42b883"
        }
    ],
    "peacock.affectAccentBorders": true,
    "peacock.surpriseMeFromFavoritesOnly": true,
```

### Prettier

Register language types with Prettier

```json
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
   "[markdown]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
```

Formatting rules applicable across projects

```json
    "prettier.useTabs": true,
    "prettier.tabWidth": 4,
    "prettier.singleQuote": true,
    "prettier.quoteProps": "consistent",
```

> Formatting HTML Files

I use _VSCode Native Formatter_ based on [js-beautify](https://www.npmjs.com/package/js-beautify) for formatting html files.

Corresponding settings are as follows:

```json
   "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "html.format.indentHandlebars": true,
    "html.format.indentInnerHtml": true,
    "html.format.maxPreserveNewLines": 1,
    "html.format.wrapAttributes": "aligned-multiple",
    "html.format.endWithNewline": true
```

### Python

```json
    "python.languageServer": "Pylance",
    "python.showStartPage": false,
    "python.formatting.provider": "black",
    "python.testing.pytestEnabled": true,
    "python.testing.nosetestsEnabled": false,
    "python.testing.unittestEnabled": true,
    "python.testing.pytestArgs": ["."],
    "python.pythonPath": "<path to python interpreter>",
    "[python]": {
        "editor.defaultFormatter": "ms-python.python"
    },
    "python.linting.flake8Enabled": true,
```

### Better Comments

```json
    "better-comments.tags": [
        {
            "tag": "!",
            "color": "#FF2D00",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "?",
            "color": "#3498DB",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "//",
            "color": "#474747",
            "strikethrough": true,
            "backgroundColor": "transparent"
        },
        {
            "tag": "todo",
            "color": "#FF8C00",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "*",
            "color": "#98C379",
            "strikethrough": false,
            "backgroundColor": "transparent"
        }
    ],
    "better-comments.multilineComments": true,
    "better-comments.highlightPlainText": true,
```
