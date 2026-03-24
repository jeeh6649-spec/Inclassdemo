# Portfolio GitHub Package

This folder is a clean GitHub-ready export of the current portfolio site.

It includes only:
- `index.html`
- the fonts used by the page
- the headshot
- the CV and reduced portfolio PDF
- the referenced project images and AI media
- the generated student preview images

## Structure

- `Fonts/`
- `Headshot/`
- `Portfolio/`
- `Projects/`
- `Resume/`
- `generated/student-previews/`
- `index.html`

## Notes

- This package is intentionally trimmed to only the assets referenced by the website.
- The smaller portfolio PDF is already being used.
- Two large AI videos are still included because the website references them directly.

## Publish

1. Clone your GitHub repository with GitHub Desktop.
2. Copy the contents of this folder into the cloned repository root.
3. Commit and push.
4. In GitHub, enable Pages from the `main` branch and the root folder.

## Local Preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.
