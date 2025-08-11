# YAPL (Yet Another Prompt Language) – VS Code Extension

Features:
- Syntax highlighting for `*.md.yapl`, `*.json.yapl`, `*.yaml|yml.yapl`, `*.txt.yapl`.
- Custom file icon for `.yapl` (across all host syntaxes).
- Extension icon included.

## Install (dev)
1. Open this folder in VS Code.
2. Press F5 to run Extension Development Host.
3. Open files in `samples/`.

## Use the file icon
- Go to **Preferences → File Icon Theme** and select **“YAPL File Icons”**.

If you prefer to keep your current icon theme, ask it to support the `.yapl` extension (most themes map based on the last extension segment).

## Packaging
```bash
npm i -g vsce
vsce package
```
