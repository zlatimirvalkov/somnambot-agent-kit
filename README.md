# Somnambot agent kit

Hooks, an MCP server and setup snippets that let coding agents work with
[Somnambot](https://somnambot.app), the safe keep-awake app for macOS for the
agent era: present at the desk, locked when you walk away, agents keep running,
the Mac sleeps when they finish.

**Status:** work in progress, nothing to install yet.

## Planned contents
- A Claude Code plugin: hooks, the `somnambot` MCP server and a skill that tells
  the agent when to keep the Mac awake and when to let it sleep.
- Setup snippets for Codex, Gemini CLI, Cursor, GitHub Copilot and Aider.

Hooks always exit 0 silently and never launch the app, so an agent never
breaks or slows down because of this kit.

## License
MIT, see [LICENSE](LICENSE).
