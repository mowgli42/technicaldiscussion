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
