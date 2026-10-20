# Install — my-game-design-director 1.0.0

```bash
npx skills add luaproxy1993/my-game-design-director -y
```

Update with the same command.

If this repo is cloned at `~/.grok/skills/my-game-design-director`:

```bash
git -C ~/.grok/skills/my-game-design-director pull
```

Manual copy:

```bash
./install.sh
./install.sh --all-agents --force
```

| Agent | Typical path |
|-------|----------------|
| Grok | `~/.grok/skills/my-game-design-director/` |
| Claude Code | `~/.claude/skills/my-game-design-director/` |
| Cursor | `~/.cursor/skills/my-game-design-director/` |
| Codex | `~/.codex/skills/my-game-design-director/` |

Verify:

```bash
test -f ~/.grok/skills/my-game-design-director/SKILL.md && echo grok-ok
cat ~/.grok/skills/my-game-design-director/VERSION
```

In the agent: `/my-game-design-director`.
