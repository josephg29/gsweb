# gsweb

Landing page for **[Codebase Grader](https://github.com/josephg29/gradeskill)** — a Claude Code skill that grades your codebase like a report card.

A single self-contained `index.html` (no build step), styled in an OpenCode-inspired terminal aesthetic: monospace type, sharp-cornered TUI panels, grayscale UI with letter grades as the only color (green-to-red by grade).

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Designed to be served as a static site (e.g. GitHub Pages). The page is a single file with no dependencies beyond the Tailwind Play CDN.
