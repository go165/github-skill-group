# GitHub skill-group

GitHub skill-group, GitHub skills group, github+skill-group, and
GitHub agent-skill-group search entry for `agent-skill-groups`.

This repository is a transparent search and navigation entry point for
`agent-skill-groups`.

Canonical project:

<https://github.com/go165/agent-skill-groups>

Documentation:

<https://go165.github.io/agent-skill-groups/>

Search phrases page:

<https://go165.github.io/agent-skill-groups/search-phrases.html>

Search landing page:

<https://go165.github.io/github-skill-group/>

Related search alias:

<https://github.com/go165/github-agent-skill-group>

## What This Points To

`agent-skill-groups` is a GitHub skill-group and GitHub agent-skill-group
manager for local Agent Skills repositories. It helps Codex, Claude Code,
OpenCode, and generic `SKILL.md` users organize large local skill libraries into
runtime-aware scenario profiles.

If you searched GitHub for `github+skill-group`, `github skill-group`,
`github skill group`, `github skills group`, `github agent-skill-group`,
`skill manager`, or `skills manager`, this repository points to the maintained
manager instead of a study-group or practice repository.

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
agent-skill-groups demo --json
```

## Core Commands

```bash
agent-skill-groups init --runtime codex --output groups.json
agent-skill-groups status --config groups.json --runtime codex --json --details
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
