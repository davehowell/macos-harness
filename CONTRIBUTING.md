# Contributing

macOS Harness is intentionally small. Prefer exposing a raw macOS primitive over
adding an app-specific helper or workflow.

```bash
uv sync
uv run ruff check .
uv run pytest
```

Pull requests should preserve two invariants: never move the physical pointer and
never activate or raise a target app.
