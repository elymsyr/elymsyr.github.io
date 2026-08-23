# elymsyr.github.io

The official website for **Dungeon Master Tool** — a portable, offline-first tabletop RPG companion built with Flutter. Live at **[https://elymsyr.github.io](https://elymsyr.github.io)**.

This repository only hosts the site. The app itself (Flutter source, builds, releases) lives in the **[dungeon-master-tool](https://github.com/elymsyr/dungeon-master-tool)** repository.

## Structure

| Path | What |
|---|---|
| `index.html` | Landing page (single-page, HTML + CSS, no build step) |
| `style.css` | Styles |
| `media/` | Screenshots, logo and assets |
| `confirm/` | Email confirmation page |

## Run locally

Serve the folder with any static server:

```bash
python -m http.server 8000
# or
npx serve .
```

Open http://localhost:8000.

## Deploy

Push to `main` — GitHub Pages serves the repository automatically. Download links and the version badge are resolved at runtime from the [GitHub releases API](https://docs.github.com/rest/releases/releases) of `dungeon-master-tool`, so they always point at the latest build.

## License

Site content © Dungeon Master Tool — [CC BY-NC 4.0](https://github.com/elymsyr/dungeon-master-tool/blob/main/LICENSE).