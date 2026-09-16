# eufrezza.github.io

Personal academic website of Eugenia Frezza, served by GitHub Pages at
<https://eufrezza.github.io>.

## Layout

- `index.html` — home page (About Me, photo, contact links)
- `research.html` — working papers and work in progress
- `teaching.html` — courses taught
- `style.css` — shared stylesheet for all pages
- `files/` — CV and portrait

## Editing

Edit the HTML directly and push to `main`. The workflow in
`.github/workflows/deploy.yml` copies the pages, the stylesheet and `files/`
to GitHub Pages on every push.

To preview locally:

```bash
python3 -m http.server 8765
```

then open <http://localhost:8765>.
