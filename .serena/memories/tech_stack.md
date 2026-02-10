# Tech Stack

## Core Language
- **Python**: >= 3.10

## Key Libraries & Frameworks
- **Playwright**: For headless browser automation and rendering.
- **Asyncio**: For asynchronous concurrent crawling.
- **Pydantic**: For data validation and settings management.
- **LXML / BeautifulSoup4**: For HTML parsing and data extraction.
- **LiteLLM**: For LLM integration features.
- **Typer / Click**: For CLI implementation.

## Build & Dependency Management
- **UV**: Fast Python package installer and resolver.
- **Setuptools**: Standard packaging (via `setup.py`/`pyproject.toml`).
- **Pip**: Fallback package manager.

## Testing
- **Pytest**: Standard testing framework.
- **Pytest-Asyncio**: For testing async code.

## Documentation
- **MkDocs**: Documentation generator.
- **Material for MkDocs**: Theme for documentation.

## Linting & Formatting (Inferred)
- **Ruff**: Likely used for fast linting/formatting (common with UV users).
- **Black**: Standard Python formatter (if not using Ruff).
