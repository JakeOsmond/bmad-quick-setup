# BMAD Quick Setup

One command to create a BMAD project, install everything, and launch straight into Party Mode with your AI team.

## What Does It Do?

```bash
bmad my-project-name
```

That single command will:

1. Create a project folder
2. Install BMAD (Agile AI-Driven Development) with sensible defaults
3. Auto-detect your name from your Mac username
4. Open Claude Code and launch Party Mode automatically

You'll be greeted by a full team of AI agents ready to help you build software — a Business Analyst, Product Manager, UX Designer, Architect, Developer, QA Engineer, and more.

## Prerequisites

You need three things installed before using this tool:

### 1. Homebrew (macOS package manager)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

More info: [brew.sh](https://brew.sh)

### 2. Node.js

```bash
brew install node
```

### 3. Claude Code CLI

You need a [Claude account](https://claude.ai) with an active subscription, then:

```bash
npm install -g @anthropic-ai/claude-code
```

## Install

```bash
brew tap JakeOsmond/tap
brew install bmad-quick-setup
```

## Usage

```bash
bmad my-project-name
```

The first time Claude opens in a new folder, it will ask if you trust the directory. Select **Yes** — this only happens once per folder. After that, Party Mode launches automatically.

## Options

```
bmad <project-name>    Create and set up a new BMAD project
bmad --help            Show help
bmad --version         Show version
```

## What is BMAD?

BMAD (BMad Method — Agile AI-Driven Development) gives you a team of AI agents — a Business Analyst, Product Manager, UX Designer, Architect, Developer, QA Engineer, Scrum Master, and more — all working together inside Claude Code to help you plan and build software.

## Full Setup Guide

For a detailed manual walkthrough, see the [BMAD Setup Guide](https://jakeosmond.github.io/bmad-setup-guide/).

## License

MIT
