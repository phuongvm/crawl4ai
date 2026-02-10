# Coding Conventions

## Style
- **Python**: Follow **PEP 8**.
- **Type Hinting**: Strongly encouraged for all function signatures (using standard `typing` or newer `list[]`/`dict[]` syntax).
- **Docstrings**: Google style or NumPy style docstrings for classes and methods.
- **Imports**: Sorted and grouped (Standard Lib -> Third Party -> Local).

## naming
- **Variables/Functions**: `snake_case`
- **Classes**: `PascalCase`
- **Constants**: `UPPER_CASE`
- **Private/Internal**: `_leading_underscore`

## Async
- Prefer `async`/`await` patterns for I/O bound operations (crawling, file I/O).
- Use `aiofiles` for file operations.

## Error Handling
- Use specific exceptions where possible.
- Wrap external calls (network, browser) in try/except blocks to handle timeouts and failures gracefully.
