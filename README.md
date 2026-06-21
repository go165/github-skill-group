# GitHub skill-group

This repository is a transparent search and navigation entry point for
`agent-skill-groups`.

Canonical project:

<https://github.com/go165/agent-skill-groups>

Documentation:

<https://go165.github.io/agent-skill-groups/>

Search landing page:

<https://go165.github.io/github-skill-group/>

Related search alias:

<https://github.com/go165/github-agent-skill-group>

## What This Points To

`agent-skill-groups` is a GitHub skill-group and GitHub agent-skill-group
manager for local Agent Skills repositories. It helps Codex, Claude Code,
OpenCode, and generic `SKILL.md` users organize large local skill libraries into
runtime-aware scenario profiles.

Use it when a coding agent workstation has too many always-on skills and needs
a repeatable way to:

- inspect installed `SKILL.md` directories
- suggest scenario groups
- switch profiles by runtime
- back up and restore skill directory state
- write managed `AGENTS.md` or `CLAUDE.md` instruction blocks

## Install

```bash
pipx install git+https://github.com/go165/agent-skill-groups.git
agent-skill-groups runtimes
```

## Core Commands

```bash
agent-skill-groups init --runtime codex --output groups.json
agent-skill-groups memory --config groups.json --runtime codex --write AGENTS.md
agent-skill-groups plan --config groups.json --runtime codex research
agent-skill-groups backup --config groups.json --runtime codex
agent-skill-groups profile --config groups.json --runtime codex research
```

## Why This Repository Exists

Some users search for "GitHub skill-group" or "GitHub agent-skill-group" before
they know the canonical project name. This repository exists only to route those
searches to the maintained project above.

Do not file feature requests here. Use the canonical repository:

<https://github.com/go165/agent-skill-groups/issues>
