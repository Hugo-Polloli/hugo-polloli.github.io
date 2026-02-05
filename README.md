# Typing conformance graph

Static GitHub Pages site that visualizes `typing_conformance.json`.

## Update the data

Replace `typing_conformance.json` with a new JSON list, then push to `main`.

## Local preview

From this repo directory:

```bash
uv run -p 3.12 -- python -m http.server 8000
```

Then open <http://localhost:8000>.
