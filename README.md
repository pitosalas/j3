# j3

A package of Claude instructions that institutes a method for developing programs with Claude. Copy the `.j3/` directory into any new project to enable the full development methodology.

## Usage

To bootstrap a new project with j3:

1. Copy the `.j3/` directory into your new project
2. Copy CLAUDE.md into your new project
2. Ask Claude to "bootstrap this project with j3"
3. Fill in `process/spec.md` with your app description
4. Start defining features and tasks

## What's included

- `.j3/method.md` — development workflow and feature/task tracking rules
- `.j3/coding.md` — coding standards and style rules
- `.j3/bootstrap.md` — scaffold instructions for new projects
- `.j3/CLAUDE.md.template` — CLAUDE.md template for new projects
- `.j3/LICENSE.template` — MIT license template
- `.j3/README.md.template` — README template
- `.j3/.gitignore.template` — Python/uv gitignore template

## Development

```bash
uv sync
uv run pytest
```

## License

MIT — see [LICENSE](LICENSE)
