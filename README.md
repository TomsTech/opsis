# Opsis

> **ὄψις** (opsis) — Greek for "sight, view, appearance"

A lightweight, zero-dependency universal document viewer. Drop any file and view it instantly in your browser.

## Features

- **Markdown** with GitHub-flavored styling
- **Mermaid diagrams** rendered inline
- **Syntax highlighting** for code blocks
- **PDF viewing** with zoom and page navigation
- **HTML** rendered in sandboxed iframe
- **JSON** pretty-printed with syntax highlighting
- **Plain text** files

## Usage

1. Open `index.html` in any modern browser
2. Drag and drop a file, or click "Open" to browse
3. Use keyboard shortcuts:
   - `Ctrl+O` — Open file
   - `Esc` — Close/reset
   - `←` `→` — PDF page navigation

## Supported Formats

| Format | Extensions | Features |
|--------|------------|----------|
| Markdown | `.md`, `.markdown` | GFM, Mermaid, code highlighting |
| HTML | `.html`, `.htm` | Sandboxed rendering |
| PDF | `.pdf` | Zoom, pagination |
| JSON | `.json` | Pretty-print, syntax highlighting |
| Text | `.txt`, `.csv`, `.xml` | Plain text display |

## Dependencies

All dependencies are loaded via CDN (no installation required):

- [marked.js](https://marked.js.org/) — Markdown parser
- [highlight.js](https://highlightjs.org/) — Syntax highlighting
- [mermaid](https://mermaid.js.org/) — Diagrams
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF rendering

## Local Development

Just open `index.html` in a browser. No build step needed.

For local file:// access, some browsers may require a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

## License

MIT License - see [LICENSE](LICENSE)
