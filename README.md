# nathanielb2025.github.io

**Live site: https://nathanielb2025.github.io**

This is my personal website. It's plain static HTML, CSS, and a tiny bit of JavaScript, with no framework and no build step, so what's in this repo is exactly what gets served. It's hosted on GitHub Pages.

I wrote the site to show how I work: one page that leads with my best technical projects (a from-scratch quantum simulator and qubit router, plus a live-streaming system I deployed) and keeps everything else short.

## What's here

- `index.html` is the whole site: intro, projects, other work, experience, and contact.
- `css/style.css` holds all the styling. It's responsive and follows the viewer's light or dark preference.
- `js/main.js` only sets the year in the footer.
- `assets/img/` has the project figures and my photos, resized for the web.
- `assets/resume.pdf` is my current resume.
- `assets/favicon.svg` is the site icon.

## Run it locally

```
python -m http.server
```

Then open `http://localhost:8000`.

## Deploying

I push to `main`, and GitHub Pages serves the repo root (Settings → Pages → Source: `main` / root).

## Updating my resume

I replace `assets/resume.pdf` with the new PDF and push.
