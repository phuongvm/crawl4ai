# Project Overview: Crawl4AI

## Purpose
**Crawl4AI** is an open-source, LLM-friendly web crawler and scraper designed to simplify the extraction of data from websites for use in AI applications. It focuses on speed, efficiency, and providing clean, structured data (Markdown, JSON) ready for LLM consumption.

## Key Features
- **LLM-Friendly Output**: Generates clean Markdown, JSON, and HTML.
- **headless Browsing**: Uses Playwright for rendering JavaScript-heavy sites.
- **Anti-Bot Detection**: Includes stealth mode to bypass bot detection.
- **Performance**: Asynchronous architecture for high-speed crawling.
- **Extraction**: Supports CSS/XPath selectors and heuristic extraction.
- **Multi-Modality**: Can extract images and screenshots.

## Architecture
- **Core**: Python-based crawler using `asyncio` and `playwright`.
- **API**: Provides both specific crawling functions and a CLI (`crwl`).
- **Dependencies**: Managed via `uv` or `pip`. Key deps: `playwright`, `lxml`, `beautifulsoup4`, `pydantic`.
- **Docs**: Comprehensive documentation built with `mkdocs` (Material theme).

## Project Structure
- `crawl4ai/`: Main source code package.
- `docs/`: Markdown documentation source.
- `tests/`: Pytest test suite.
- `scripts/`: Utility scripts.
- `examples/`: Usage examples (implied).
