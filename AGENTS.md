# AGENTS

## Purpose
This file helps AI coding agents understand the `MCI Companion AI` repository quickly and make productive changes.

## Project overview
- Small static web app with a single-page HTML interface.
- Japanese UI content and UX are primary.
- Current implementation is in `index.html` only.
- `README.md` describes the project goal: early detection of MCI (軽度認知障害) through conversational AI, history saving, facial analysis, comparison to past data, and family notification.

## Agent guidance
- Treat this as a vanilla HTML/JavaScript project; there is no build system, package manager, or framework configured.
- Preserve Japanese language in UI text and comments unless the user explicitly requests localization.
- When updating behavior, modify `index.html` and keep scripts simple and inline unless the user asks to refactor into separate files.
- Before making changes, inspect `index.html` and `README.md` for the current UX flow and feature expectations.
- If adding new functionality, ensure it matches the existing conversational/chat-focused design.

## Notes for future work
- There is currently no test setup, build commands, or `src/` folder.
- Add documentation links to `README.md` rather than duplicating content when possible.
