# BMAD Quick Setup

One command to create a project, install BMAD, and open Claude Code.

## Install via Homebrew

```bash
brew tap JakeOsmond/tap
brew install bmad-quick-setup
```

## Usage

```bash
bmad my-project-name
```

That's it. It will:

1. Create a folder called `my-project-name`
2. Install BMAD with sensible defaults (auto-detects your name)
3. Open Claude Code ready to go

## Prerequisites

Before using this tool, you need:

- **Homebrew** — [brew.sh](https://brew.sh)
- **Node.js** — `brew install node`
- **Claude Code** — `npm install -g @anthropic-ai/claude-code` (requires a [Claude account](https://claude.ai))

## Options

```
bmad <project-name>    Create and set up a new BMAD project
bmad --help            Show help
bmad --version         Show version
```

## What is BMAD?

BMAD (BMad Method — Agile AI-Driven Development) gives you a team of AI agents — a Business Analyst, Product Manager, UX Designer, Architect, Developer, QA Engineer, and more — all working together inside Claude Code to help you build software.

## Full Setup Guide

For a detailed walkthrough with screenshots and explanations, see the [BMAD Setup Guide](https://jakeosmond.github.io/bmad-setup-guide/).

## License

MIT
