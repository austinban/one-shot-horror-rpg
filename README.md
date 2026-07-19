# One-Shot Horror RPG

Reference sheets for tabletop one-shots, hosted on GitHub Pages.

## Adding a new reference sheet

1. Drop a new `.html` file into [`sheets/`](./sheets).
2. Commit and push to `main`.
3. GitHub Actions rebuilds the index automatically — no manual linking needed.

The index page pulls each file's `<title>` tag for its link text, so give new sheets a meaningful `<title>`.

## Local preview

Open any file in `sheets/` directly in a browser, or run:

```sh
python3 -m http.server -d sheets
```
