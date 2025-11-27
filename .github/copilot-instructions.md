# Copilot Instructions for GitHub Copilot CLI Repository

## Repository Overview

This repository contains documentation and public resources for GitHub Copilot CLI - a terminal-native AI-powered coding assistant. The CLI brings GitHub Copilot's capabilities directly to your command line.

## Key Concepts

- **GitHub Copilot CLI**: A command-line interface that provides AI-powered coding assistance in your terminal
- **MCP (Model Context Protocol)**: Extensibility protocol that allows custom server integrations
- **Custom Agents**: User-defined agent configurations stored in `~/.copilot/agents` or `.github/agents`

## Documentation Guidelines

When contributing to this repository:

1. **README.md**: Contains the main user-facing documentation for installation, usage, and features
2. **changelog.md**: Contains release notes organized by version number (newest first)
3. **Issue Templates**: Located in `.github/ISSUE_TEMPLATE/` for bug reports and feature requests

## Writing Style

- Use clear, concise language accessible to developers of all skill levels
- Include code examples where helpful
- Document both interactive and non-interactive (`-p`) modes when applicable
- Mention platform-specific considerations (Linux, macOS, Windows) when relevant

## Technical Context

- The CLI requires Node.js v22+ and npm v10+
- Default model is Claude Sonnet 4.5 (configurable via `/model` command)
- MCP server configuration is stored in `~/.copilot/mcp-config.json`
- Session data is stored in `~/.copilot/session-state`

## Common Features to Reference

- Slash commands (`/model`, `/mcp`, `/usage`, `/share`, `/delegate`, etc.)
- File mentioning with `@` syntax
- Shell command execution with `!` prefix
- Image support via drag-and-drop or file paths
- Multi-line input support via Kitty protocol or `/terminal-setup`
