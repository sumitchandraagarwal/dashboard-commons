# Public Dashboard Commons

This is a plain-Markdown Material for MkDocs site designed for GitHub Pages.

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

