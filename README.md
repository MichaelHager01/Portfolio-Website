# Portfolio website

A one-page personal site with a home section, a services section, and a short about section.

## What it does

- The page is static HTML and CSS, with a nav toggle in `src/index.js`.
- It started from the Scrimba portfolio course and was restyled after that.
- `src/index.html` still points at `img/mhager.jpg` and `img/mbhhead2.jpeg`. Those image files are not in this repository, so the photos render as broken until you add an `src/img/` directory.

## Layout

- `src/index.html` — page structure
- `src/style.css` — layout and type
- `src/index.js` — opens and closes the navigation

## Run

Open `src/index.html` in a browser. From the repository root:

```bash
python -m http.server 8765
```

Then visit `http://127.0.0.1:8765/src/`.

## Stack

HTML, CSS, and JavaScript.
