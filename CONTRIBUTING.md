# Contributing to Docker Port Forwarder

🎉 Thanks for your interest in contributing! This project welcomes contributions of all kinds: bug reports, feature requests, documentation improvements, and code patches.

## 📌 Table of Contents

- [Getting Started](#getting-started)
- [Code Guidelines](#code-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Submitting Changes](#submitting-changes)
- [Running Tests](#running-tests)
- [Style and Conventions](#style-and-conventions)
- [Code of Conduct](#code-of-conduct)

---

## 🏁 Getting Started

1. **Fork the repository** on GitHub.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/your-username/docker-port-forwarder.git
   cd docker-port-forwarder
   ```

## 📋 Code Style

    - Keep the Bash code POSIX-compliant where possible, but Bash 4+ is required.
    - Use 2-space or 4-space indentation consistently.
    - Use meaningful variable names and comments.
    - Prefer set -euo pipefail for script safety.
    - Include echo -e with ANSI colors for logs, using predefined color variables.

## 💡 Feature Proposals

If you want to suggest a new feature:

    - Open an issue with a clear description
    - Explain the use case and why it fits this project

## 🐞 Bug Reports

When reporting a bug:

    - Specify your OS and Docker version
    - Include a reproducible example if possible
    - Share error logs with full context

## ✅ Submitting a Pull Request

    - Fork the repository
    - Create a new branch (feature/my-new-feature)
    - Commit your changes with clear messages
    - Ensure your code is clean and tested
    - Open a pull request and describe your changes

## 🧪 Tests

Tests are Bash scripts under the test/ folder. They should:

    - Be idempotent and clean up after themselves
    - Avoid using privileged containers unless necessary
    - Verify socat redirection works as expected

## 🙌 Code of Conduct

This project follows the Contributor Covenant. Be respectful and inclusive.
