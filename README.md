# Software Factory Skills

A collection of [Claude](https://claude.com) skills and personas for building software with AI agents.

> **Status:** early days. The structure below is a starting point and will change as the collection grows.

## What's in here

- **Skills** – reusable, task-focused instructions that Claude loads when a task calls for them (for example planning, reviewing or testing).
- **Personas** – role definitions (for example product owner, architect, engineer, QA) that give an agent a consistent point of view, responsibilities and way of working.

## Layout

```
skills/      # one folder per skill, each with a SKILL.md
personas/    # one file or folder per persona
```

## Using a skill

Copy or symlink a skill folder into one of the places Claude Code looks for skills:

- `~/.claude/skills/` – available in every project
- `<project>/.claude/skills/` – available in that project only

## Contributing

1. Create a folder under `skills/` or `personas/`.
2. Add a `SKILL.md` (or persona file) with a clear `name` and `description` in its frontmatter.
3. Keep each skill focused on one job, and describe when it should be used.

## License

TBD.
