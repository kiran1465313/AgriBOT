# Contributing to AgriBot 🌾

First off, thank you for considering contributing to AgriBot! It's people like you that make open source such a great community. We welcome any and all contributions, from bug reports to new features.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

## 📋 Table of Contents
- [Code of Conduct](#-code-of-conduct)
- [How Can I Contribute?](#-how-can-i-contribute)
  - [🐛 Reporting Bugs](#-reporting-bugs)
  - [✨ Suggesting Enhancements](#-suggesting-enhancements)
  - [🚀 Pull Requests](#-pull-requests)
- [Development Setup](#-development-setup)
- [Styleguides](#-styleguides)
  - [Git Commit Messages](#git-commit-messages)
  - [Python Styleguide](#python-styleguide)

## 🤝 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior.

## 🤔 How Can I Contribute?

### 🐛 Reporting Bugs

Bugs are tracked as [GitHub Issues](https://github.com/yourusername/agribot/issues). Before creating a bug report, please check the existing issues to see if someone has already reported it.

When you are creating a bug report, please include as many details as possible. Fill out the required template, which will help us resolve issues faster. Key information includes:

- **A clear and descriptive title.**
- **A detailed description of the problem.**
- **Steps to reproduce the bug.**
- **Expected behavior vs. actual behavior.**
- **Screenshots or logs** if applicable.
- **Your environment details** (e.g., OS, Python version, browser).

### ✨ Suggesting Enhancements

Enhancement suggestions are also tracked as [GitHub Issues](https://github.com/yourusername/agribot/issues).

- **Use a clear and descriptive title** for the issue to identify the suggestion.
- **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
- **Explain why this enhancement would be useful** to most AgriBot users.
- **Provide code examples or mockups** if you have them.

### 🚀 Pull Requests

We love pull requests! To submit one, please follow these steps:

1.  **Fork the repository** to your own GitHub account.
2.  **Clone the project** to your machine: `git clone https://github.com/YOUR_USERNAME/agribot.git`
3.  **Create a new branch** for your changes. Use a descriptive name:
    ```bash
    git checkout -b feature/new-language-support
    # or for a bug fix
    git checkout -b bugfix/mandi-api-timeout
    ```
4.  **Make your changes.** Write clean, readable code and add comments where necessary.
5.  **Test your changes** to ensure they work as expected and don't break existing functionality.
6.  **Commit your changes** using a descriptive commit message (see our styleguide).
    ```bash
    git add .
    git commit -m "feat: Add support for Punjabi language"
    ```
7.  **Push your branch** to your fork on GitHub:
    ```bash
    git push origin feature/new-language-support
    ```
8.  **Open a Pull Request** to the `main` branch of the original repository.
9.  **Provide a clear description** of your changes in the PR description. Link to any relevant issues.

## 🛠️ Development Setup

To get the development environment running, please follow the instructions in the README.md file under Quick Start. This will guide you through installing dependencies and configuring the necessary API keys.

## 🎨 Styleguides

### Git Commit Messages

We use a conventional commit message format to keep the history clean and easy to read.

- **`feat:`**: A new feature for the user.
- **`fix:`**: A bug fix for the user.
- **`docs:`**: Changes to the documentation.
- **`style:`**: Formatting, missing semi-colons, etc.; no production code change.
- **`refactor:`**: Refactoring production code, e.g. renaming a variable.
- **`test:`**: Adding missing tests, refactoring tests; no production code change.
- **`chore:`**: Updating build tasks, package manager configs, etc; no production code change.

**Example:** `feat: Add real-time weather alerts for pest prediction`

### Python Styleguide

All Python code should adhere to the PEP 8 style guide. We recommend using a linter like `flake8` or an auto-formatter like `black` to ensure your code is compliant.

---

Thank you again for your interest in contributing to AgriBot! We look forward to your contributions.
