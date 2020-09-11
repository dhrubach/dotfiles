# IDE Setup Configurations

## Editor Flags

---

```json
    "editor.formatOnSave": true,
    "editor.formatOnSaveMode": "modifications",
    "editor.renameOnType": true,
    "editor.find.cursorMoveOnType": false,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "workbench.editor.enablePreview": false,
    "workbench.startupEditor": "newUntitledFile",
```

## Integrated Terminal

---

```json
    "terminal.integrated.copyOnSelection": true,
    "terminal.integrated.shell.windows": "<path to Git Bash exe>",
```

## Misc IDE Settings

---

```json
    "files.eol": "\n",
    "git.suggestSmartCommit": false,
    "git.autofetch": true,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "diffEditor.ignoreTrimWhitespace": false,
    "window.zoomLevel": 0
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
    "python.languageServer": "Microsoft",
    "python.showStartPage": false,
    "python.formatting.provider": "black",
    "python.testing.pytestEnabled": false,
    "python.testing.nosetestsEnabled": false,
    "python.testing.unittestEnabled": true,
    "python.pythonPath": "<path to python interpreter>",
    "[python]": {
        "editor.defaultFormatter": "ms-python.python"
    }
```
