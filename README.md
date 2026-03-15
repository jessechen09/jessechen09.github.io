# Personal academic website

A simple, static template for a researcher personal page. Works on GitHub Pages with no build step.

## Edit your content

- **index.html** — Update name, title, affiliation, about text, research interests, publications, education, and contact. Replace the `.avatar-placeholder` div with an `<img>` tag if you want a profile photo.
- **styles.css** — Optional: tweak `:root` colors (e.g. `--accent`, `--bg`) to match your preference.

## Run locally

Open `index.html` in a browser, or use a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deploy on GitHub Pages

Push to the `main` branch. GitHub Pages will serve the site from the repo root. Your site will be at `https://jessechen09.github.io`.
