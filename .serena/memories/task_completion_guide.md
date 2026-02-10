# Task Completion Guide

## Checklist
1.  **Code Quality**:
    - [ ] Run formatter (`ruff format` or `black`).
    - [ ] Run linter (`ruff check` or `pylint`).
    - [ ] Ensure type hints are correct (`mypy` if available).

2.  **Testing**:
    - [ ] Add unit tests for new functionality in `tests/`.
    - [ ] Run full test suite `pytest` to ensure no regressions.
    - [ ] Verify `headless` vs `headful` modes if touching browser logic.

3.  **Documentation**:
    - [ ] Update docstrings for modified functions/classes.
    - [ ] Update `docs/*.md` if features are user-facing.
    - [ ] Add example to `examples/` if it's a new capability.

4.  **Dependencies**:
    - [ ] If new deps added, update `pyproject.toml` and run `uv sync`.

5.  **Commit**:
    - [ ] Use conventional commit messages (e.g., `feat: ...`, `fix: ...`).
