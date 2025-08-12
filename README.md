# YAPL VS Code Extension

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/yapl.yapl-vscode)](https://marketplace.visualstudio.com/items?itemName=yapl.yapl-vscode)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/yapl.yapl-vscode)](https://marketplace.visualstudio.com/items?itemName=yapl.yapl-vscode)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/yapl.yapl-vscode)](https://marketplace.visualstudio.com/items?itemName=yapl.yapl-vscode)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Official VS Code extension for YAPL (Yet Another Prompt Language) - a tiny, composable prompt templating language designed for AI agents.

## ✨ Features

- **Syntax Highlighting**: Full syntax highlighting for all YAPL file types:
  - `*.md.yapl` - Markdown-based templates
  - `*.json.yapl` - JSON-based templates  
  - `*.yaml.yapl` / `*.yml.yapl` - YAML-based templates
  - `*.txt.yapl` - Plain text templates
- **Custom File Icons**: Beautiful YAPL-themed icons for all `.yapl` files
- **IntelliSense**: Smart completions for YAPL syntax
- **Error Detection**: Real-time syntax validation
- **Code Folding**: Collapse blocks and sections for better navigation

## 🚀 Installation

Install directly from the VS Code Marketplace:

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "YAPL"
4. Click Install

Or install via command line:
```bash
code --install-extension yapl.yapl-vscode
```

## 🎨 File Icons

To use the custom YAPL file icons:

1. Go to **File → Preferences → File Icon Theme** (or **Code → Preferences → File Icon Theme** on macOS)
2. Select **"YAPL File Icons"**

The icons will automatically apply to all `.yapl` files regardless of the base file type.

## 📝 Usage

Create a new file with a `.yapl` extension and start writing YAPL templates:

```yapl
{# hello.md.yapl #}
{% block system %}
You are a helpful AI assistant.
{% endblock %}

{% block prompt %}
Hello {{ name | default("there") }}!
How can I help you with {{ topic }}?
{% endblock %}
```

## 🔧 Development

To contribute to this extension:

1. Clone the repository
2. Open in VS Code
3. Press F5 to launch Extension Development Host
4. Test with files in the `samples/` directory

### Building

```bash
# Install dependencies
npm install

# Package extension
npm install -g vsce
vsce package
```

## 📚 YAPL Resources

- [YAPL Website](https://yapl.dev)
- [YAPL Documentation](https://yapl.dev/docs)
- [YAPL GitHub Repository](https://github.com/yapl-lang/yapl)
- [NPM Package](https://www.npmjs.com/package/@yapl/yapl-ts)

## 🤝 Contributing

Contributions are welcome! Please see our [Contributing Guide](https://github.com/yapl-lang/yapl-vscode/blob/main/CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Issues & Support

- [Report Issues](https://github.com/yapl-lang/yapl-vscode/issues)
- [Feature Requests](https://github.com/yapl-lang/yapl-vscode/issues/new?template=feature_request.md)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=yapl.yapl-vscode)

---

Made with 💖 for the YAPL community