# AgentsInFlow

Desktop app to orchestrate multiple CLI coding agents (Codex/Claude) across many git projects.

**Download latest:** https://github.com/AgentsInFlow/AgentsInFlow/releases/latest  
**All versions + changelog:** https://github.com/AgentsInFlow/AgentsInFlow/releases

## What problem it solves

Running agentic coding workflows across multiple repos gets messy fast:
- too many terminals, no shared context
- hard to track what ran, where, and why
- easy to lose “what changed” between attempts

AgentsInFlow gives you a single place to manage work (tickets) and run/track agents against real repos.

## Editions

- Free (Limited): up to 2 projects
- Pro: not published yet

## Core workflow

1. Add a project (a local git repo)
2. Create a ticket (feature/bug/task)
3. Run an agent on the ticket/subtasks
4. Track progress, review output, iterate

## Key features

- Projects + tickets (Kanban + list)
- Per-ticket execution config (engine/model/permissions)
- Multiple concurrent runs + history
- Built-in terminals per project
- Packaged-app auto-update (release notes → download → restart)

## Install

Grab your OS installer from the latest release:
- macOS: `.dmg`
- Windows: `.exe`
- Linux: `.AppImage` (and/or `.deb`, depending on release)

## Auto-update

Packaged builds periodically check for updates and let you:
- view release notes
- download the update
- restart to apply

## Supported engines

- OpenAI Codex CLI
- Anthropic Claude Code CLI

## Requirements (for agent runs)

- Codex CLI installed + authenticated
- Claude Code CLI installed + authenticated

## Screenshots

_(coming soon)_

## Notes

This repo hosts public releases (installers + update metadata). Source code is not published here.
