# One-Shot Horror RPG

Reference sheets for tabletop one-shots, hosted on GitHub Pages.

## Categories

- [`sheets/`](./sheets) — player-facing character sheets
- [`dm-materials/`](./dm-materials) — GM-only reference material (statuses, NPCs, etc.)

## Adding a new reference sheet

1. Drop a new `.html` file into an existing category folder, or create a new top-level folder for a new category.
2. Commit and push to `main`.
3. GitHub Actions rebuilds the index automatically — no manual linking needed.

The index page pulls each file's `<title>` tag for its link text, and groups files by their top-level folder name, so give new sheets a meaningful `<title>`.

## Local preview

Open any `.html` file directly in a browser, or serve the repo root:

```sh
python3 -m http.server
```
