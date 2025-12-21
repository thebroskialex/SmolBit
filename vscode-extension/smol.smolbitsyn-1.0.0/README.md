# SmolBit Syntax Highlighting

You can change the colors of the syntax highlighting by changing the `"editor.tokenColorCustomizations": {"textMateRules": ...}` section of your settings.json file.
The scopes for the language are as follows:
Comments: comment.smolbit
Hex values: constants.numeric.smolbit
Registers/Addresses: support.variable.smolbit
The `f` register: support.variable.global.smolbit
Errors: invalid.illegal.smolbit
Comparison Operators: keyword.operator.comparison.smolbit
Control (Functions, If statements, loops, etc.): keyword.control.smolbit
Page Switches: storage.type.smolbit
Function identifiers: entity.name.function.smolbit

EX.
```json
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": "support.variable.global.smolbit",
            "settings": {
                "foreground": "#7733ff"
            }
        }
    ]
}
```

# Installation

1. Copy the smolbitsyn-1.0.0 folder to your VS Code extensions directory:

- Windows: %USERPROFILE%\.vscode\extensions

- macOS/Linux: ~/.vscode/extensions

2. Restart VS Code