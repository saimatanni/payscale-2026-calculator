# Pay Scale 2026 salary calculator

A single-file, bilingual (English / বাংলা) salary calculator for the 2026 pay scale.

- No build step, no dependencies, no network calls — everything is in `index.html`
- Bengali webfonts (Hind Siliguri, Tiro Bangla) are embedded as base64, so it works fully offline
- Light and dark themes, with a manual toggle and `prefers-color-scheme` as the default

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy

Static site — Vercel serves `index.html` from the repo root with no configuration.
