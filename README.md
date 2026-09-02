# BA Notes Library (MkDocs site)

A searchable documentation site built from the 35 Word documents in the
[BA-Notes](https://github.com/tsrajpurohit/BA-Notes) repository — Agile Masterclass
modules, interview prep, resume guidance, a real BA project simulation, and roadmaps.

## Run locally

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000

## Deploy to GitHub Pages

1. Push this repository to GitHub (or copy these files into your existing `BA-Notes` repo).
2. In the repo settings, go to **Settings → Pages** and set the source to
   **GitHub Actions**.
3. Push to `main` — the included workflow (`.github/workflows/deploy.yml`) builds the
   site with `mkdocs-material` and publishes it automatically to the `gh-pages` branch.
4. Your site will be live at `https://<username>.github.io/<repo>/`.

You can also deploy manually any time with:

```bash
pip install -r requirements.txt
mkdocs gh-deploy --force
```
