# AGENTS.md - guide for AI coding agents

## Project context

technicaldiscussion is a documentation/practice repository centered on markdown and notebooks.
Start with `README.md` and `Practice-Markdown.ipynb`.

## Local setup

No dependency installation is required for the configured smoke check.

## Smoke test

```bash
test -f Practice-Markdown.ipynb && test -f README.md
```

## Agent notes

- Keep examples readable and beginner-friendly.
- Avoid editing notebook metadata unless the content change requires it.
- Preserve existing local user changes; stage only files you intentionally modify.

## Issue Tracking

This project uses **bd (beads)** for issue tracking. Run `bd prime` for workflow context, or install hooks with `bd hooks install` for automatic context injection.

Quick reference:

- `bd ready` - find unblocked work
- `bd create "Title" --type task --priority 2` - create an issue
- `bd close <id>` - close completed work
- `bd dolt push` - push Beads data when using a shared Beads remote

For full workflow details, run `bd prime`.
