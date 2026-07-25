# Public Dashboard Commons

This is a plain-Markdown Material for MkDocs site designed for GitHub Pages.

- Live site: <https://sumitchandraagarwal.github.io/dashboard-commons/>
- Repository: <https://github.com/sumitchandraagarwal/dashboard-commons>

## Edit

- Main page: `docs/index.md`
- Styling: `docs/stylesheets/extra.css`
- Images: `docs/assets/places/`

## Build

```bash
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/mkdocs serve
```

Pushing `main` runs the Pages workflow. Public content must never contain local file paths, email addresses, reservation identifiers, payment details, or identity documents.

## Publish an update

1. Edit `docs/index.md` or a public asset.
2. Run the shared `dashboardctl.py render europe-trip-2026` and `check europe-trip-2026` commands from the Drive workspace.
3. Review the built page.
4. Commit and push `main`; GitHub Pages rebuilds automatically.
