# Missing Semester — Lectures & Code

Personal workspace for working through [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) (MIT). Lecture notes, exercise solutions, and code experiments land here as I go through the course.

## Contents

| Path | What it is |
|---|---|
| [`my-agent-project/`](my-agent-project/) | A [uv](https://docs.astral.sh/uv/)-managed Python starter project built on [NVIDIA OO Agents (`nooa`)](https://pypi.org/project/nooa/) |

Lecture-by-lecture notes and exercises will be added as separate directories.

## my-agent-project

A minimal Python 3.14 project scaffolded with `uv init`, with `nooa >= 0.0.8` as its only dependency.

```bash
cd my-agent-project
uv sync          # create the venv and install dependencies
uv run main.py   # prints a hello message
```

## Requirements

- [uv](https://docs.astral.sh/uv/) (Python package manager)
- Python 3.14+ (uv will fetch it if missing)

## License

[MIT](LICENSE) © 2026 Jeremy Gracey
