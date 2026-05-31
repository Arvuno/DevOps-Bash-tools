# Contributing to DevOps Bash Tools

Thank you for your interest in contributing!

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USER/DevOps-Bash-tools.git`
3. Run `./setup.sh` to configure your environment
4. Explore the `scripts/` directory

## Making Changes

* Follow the existing code style
* Use shellcheck for linting: `shellcheck scripts/**/*.sh`
* Make sure all scripts are executable
* Test your changes thoroughly

## Pull Request Process

1. Create a feature branch from `master`
2. Make your changes and commit them
3. Ensure `./lint.sh` passes
4. Push to your fork and open a pull request

## Coding Standards

* Use `set -euo pipefail` in all scripts
* Include shebang: `#!/usr/bin/env bash`
* Document functions with comments
* Keep lines under 120 characters

## Attribution

Thank you to all contributors!
