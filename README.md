# Puku CLI — Issues

> **The AI coding assistant that lives in your terminal.**

## Introduction

Puku CLI is an AI-powered coding assistant that runs entirely in your terminal. It combines a rich React/Ink UI, a 45-tool execution engine, 94+ slash commands, and support for multiple AI providers — local and cloud — into a single `npm install -g` command.

### What is Puku CLI?

Puku CLI is a terminal-first agent: it reads and edits your files, runs shell commands, searches the web, manages Git, calls MCP servers, and spawns sub-agents — all under a fine-grained permission system you control. It works with Anthropic Claude, OpenAI, Ollama, LM Studio, DeepSeek, and other OpenAI-compatible endpoints, switching providers via a single profile command.

---

## About this repository

This repository is the **public issue tracker** for [Puku CLI](https://puku.sh). The source code lives in private repositories — **this repo exists so you can file bugs, request features, and tell us what's broken.** Every issue is read by the team.

---

## Reporting a Bug

Before opening a new issue, please:

1. **Search existing issues** — your bug may already be tracked.
2. **Update to the latest version** — run `npm install -g @puku/puku-cli` and confirm with `puku-cli --version`.
3. **Reproduce with a fresh session** — start a new terminal session and try again to rule out stale state.

Then [open a new issue](../../issues/new/choose) and include:

- **Puku CLI version** — `puku-cli --version` or type `/version` inside a session
- **OS + version** (e.g. macOS 15.3, Ubuntu 24.04, Windows 11)
- **Node.js version** — `node --version`
- **Steps to reproduce** — numbered, minimal, copy-pasteable
- **What you expected** vs **what happened**
- **Relevant output or logs:**
  - Run `puku-cli --debug` to enable verbose logging
  - Copy the terminal output around the failure
  - For tool errors, include the tool name and the exact error message shown
- **Screenshots or recordings** for UI/rendering bugs — they save hours

> **Do not include API keys, access tokens, auth cookies, file contents you can't share publicly, or any other sensitive data. Sanitize all output before pasting.**

---

## ✨ Requesting a Feature

We want Puku CLI to be the most capable terminal agent available. To make your request land:

- **One feature per issue.** Don't bundle unrelated asks.
- **Lead with the problem, not the solution.** "I can't easily refactor across multiple files" beats "Add a multi-file edit button."
- **Tell us who it helps and how often you hit it.** Frequency matters when we prioritize.
- **Link prior art** if another tool does this well — screenshots or recordings welcome.
- **Call out provider specifics** if the request only applies to certain providers or models.

---

## 🔒 Security Issues

**Do not file security vulnerabilities as public issues.** Use GitHub's private vulnerability reporting on this repo. We respond within 48 hours.

---

## Other Channels

- **Website** → [puku.sh](https://puku.sh)
- **npm package** → [@puku/puku-cli](https://www.npmjs.com/package/@puku/puku-cli)
- **Docs** → quick-start guides in [docs/](./docs/) for Windows, macOS, and Linux

## 📋 Issue Labels — what they mean

| Label | Meaning |
|---|---|
| `bug` | Something is broken |
| `enhancement` | New feature or improvement |
| `agent` | Sub-agent spawning or coordination issues |
| `tools` | Built-in tool failures (Bash, FileEdit, Glob, Grep, etc.) |
| `slash-commands` | `/plan`, `/compact`, `/skills`, and other slash commands |
| `provider` | Provider connection, auth, or model-specific issues |
| `mcp` | Model Context Protocol server integration |
| `permissions` | Tool permission prompts, allow/deny rules |
| `session` | Session history, compaction, memory persistence |
| `performance` | Slowness, high latency, excessive token usage |
| `ide-bridge` | VS Code extension or MCP/SSE bridge issues |
| `windows` | Windows-specific behavior |
| `needs-repro` | Cannot reproduce — please add steps |
| `good first issue` | Friendly entry point if you'd like to contribute |

---

## Code of Conduct

Constructive feedback — including harsh criticism — is welcome; personal attacks, harassment, or hostility toward other users are not. Issues that violate this will be closed without discussion.

---

**Thanks for using Puku CLI.** Every issue you file makes it better for everyone.