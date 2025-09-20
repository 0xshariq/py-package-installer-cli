# 📦 Package Installer CLI

[![PyPI version](https://img.shields.io/pypi/v/package-installer-cli.svg)](https://pypi.org/project/package-installer-cli/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-%3E%3D3.8-brightgreen.svg)](https://python.org/)
[![Node.js](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg)](https://nodejs.org/)

A **cross-platform, interactive CLI** to scaffold modern web application templates with support for multiple frameworks, languages, and development tools. Create production-ready projects in seconds!

## 🚀 Quick Features

- **🎨 Multiple Frameworks**: React, Next.js, Express, Angular, Vue, Rust
- **🔤 Language Support**: TypeScript & JavaScript variants
- **🎭 UI Libraries**: Tailwind CSS, Material-UI, shadcn/ui
- **📦 Smart Package Management**: Auto-detects npm, yarn, pnpm
- **⚡ Lightning Fast**: Optimized template generation with intelligent caching
- **🌈 Beautiful CLI**: Gorgeous terminal interface with real-time analytics
- **🔍 Project Analysis**: Advanced dependency analysis and project insights

## ✨ New Features

- **📊 Enhanced Analytics Dashboard**: Real-time usage analytics with detailed insights
- **🎯 Smart Dependency Updates**: Project-specific dependency management for JS, Python, Rust, Go, Ruby, PHP
- **🚀 Intelligent CLI Upgrades**: Separate upgrade system with breaking change detection
- **💾 .package-installer-cli Folder**: All cache and history stored in dedicated folder
- **📈 Usage Tracking**: Comprehensive command and feature usage tracking
- **⚡ Performance Insights**: Productivity scoring and usage patterns

## 📥 Installation

```bash
# Using pip
pip install package-installer-cli

# Using pip3
pip3 install package-installer-cli
```

## 🎯 Quick Start

```bash
# Create new project interactively
package-installer create

# Analyze project with enhanced dashboard
package-installer analyze

# Update project dependencies only
package-installer update

# Upgrade CLI to latest version
package-installer upgrade-cli
```

## 📚 Documentation

| Document | Description |
|----------|-------------|
| [📋 Commands](docs/commands.md) | Complete command reference with examples |
| [⚡ Features](docs/features.md) | Detailed feature documentation and usage |
| [🎨 Templates](docs/templates.md) | Available templates and customization options |
| [🚀 Deployment](docs/deploy.md) | Deployment options and platform integration |

## 🛠️ Command Overview

| Command | Description | Usage |
|---------|-------------|-------|
| `package-installer create` | Create new project from templates | `package-installer create [name]` |
| `package-installer analyze` | Enhanced project analytics dashboard | `package-installer analyze [--detailed]` |
| `package-installer update` | Update project dependencies | `package-installer update [--latest]` |
| `package-installer upgrade-cli` | Upgrade CLI to latest version | `package-installer upgrade-cli` |
| `package-installer add` | Add features to existing projects | `package-installer add [feature]` |
| `package-installer doctor` | Diagnose and fix project issues | `package-installer doctor` |
| `package-installer clean` | Clean development artifacts | `package-installer clean [--all]` |

*For complete command documentation, see [docs/commands.md](docs/commands.md)*

## 🏗️ Supported Project Types

| Language/Framework | Templates | Package Managers |
|-------------------|-----------|------------------|
| **JavaScript/TypeScript** | React, Next.js, Express, Angular, Vue | npm, yarn, pnpm |
| **Python** | Django, Flask, FastAPI | pip, poetry |
| **Rust** | Basic, Advanced, Web | cargo |
| **Go** | CLI, Web, API | go mod |
| **Ruby** | Rails, Sinatra | bundler |
| **PHP** | Laravel, Symfony | composer |

*For detailed template information, see [docs/templates.md](docs/templates.md)*

## 🎯 System Requirements

- **Python**: 3.8 or higher
- **Node.js**: 18.0.0 or higher (required for the underlying CLI)
- **Operating Systems**: Windows, macOS, Linux
- **Package Managers**: npm, yarn, or pnpm
- **Git**: Required for project initialization

## 🐛 Troubleshooting

### Quick Fixes

```bash
# Clear cache and reinstall
pip uninstall package-installer-cli
pip install package-installer-cli

# Use pip with --user if global installation fails
pip install --user package-installer-cli

# Check CLI status
package-installer doctor
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **PyPI Package**: [package-installer-cli](https://pypi.org/project/package-installer-cli/)
- **GitHub Repository**: [py_package_installer_cli](https://github.com/0xshariq/py_package_installer_cli)
- **Issues & Feedback**: [GitHub Issues](https://github.com/0xshariq/py_package_installer_cli/issues)

---

**Happy coding! 🚀** Create something amazing with Package Installer CLI.
