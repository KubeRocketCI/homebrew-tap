# KubeRocketCI Homebrew Tap

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Homebrew](https://img.shields.io/badge/homebrew-tap-orange)](https://brew.sh/)

Official Homebrew tap for KubeRocketCI — a curated collection of CLI tools, frameworks, and utilities for modern AI-driven and DevOps workflows on Kubernetes.

## Overview

This Homebrew tap provides easy installation and updates for KubeRocketCI tools. Currently available:

- **krci-ai**: KubeRocketAI CLI - AI-as-Code framework for Kubernetes development

## Installation

### Add the Tap

First, add the KubeRocketCI tap to your Homebrew installation:

```bash
brew tap KubeRocketCI/homebrew-tap
```

### Install Tools

After adding the tap, you can install any available formula:

```bash
# Install krci-ai
brew install krci-ai
```

## Available Formulas

### krci-ai

KubeRocketAI CLI - AI-as-Code framework for Kubernetes development.

**Installation:**

```bash
brew install krci-ai
```

**Usage:**

```bash
krci-ai --version
krci-ai --help
```

**Links:**

- [GitHub Repository](https://github.com/KubeRocketCI/kuberocketai)
- [Documentation](https://github.com/KubeRocketCI/kuberocketai#readme)

## Updating

To update all installed formulas from this tap:

```bash
brew update
brew upgrade
```

To update a specific formula:

```bash
brew upgrade krci-ai
```

## Uninstalling

To remove a formula:

```bash
brew uninstall krci-ai
```

To remove the tap entirely:

```bash
brew untap KubeRocketCI/homebrew-tap
```

## Support

- **Issues**: Report issues with specific tools in their respective repositories
- **Tap Issues**: Report issues with this tap on the [homebrew-tap repository](https://github.com/KubeRocketCI/homebrew-tap/issues)
- **Documentation**: Visit [KubeRocketCI Documentation](https://github.com/KubeRocketCI)

## Contributing

We welcome contributions! Please see the individual tool repositories for contribution guidelines.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

**Note**: This tap is maintained by the KubeRocketCI team. For the latest updates and announcements, follow the [KubeRocketCI organization](https://github.com/KubeRocketCI) on GitHub.
