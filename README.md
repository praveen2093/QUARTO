# QUARTO

This repository now includes a Quarto website project with an interactive tutorial.

## Files added

- `_quarto.yml` — website configuration and navigation
- `index.qmd` — home page for the website
- `tutorial.qmd` — interactive tutorial content
- `about.qmd` — about page
- `styles.css` — custom styling for the website

## Run the website

Render the full site with:

```bash
quarto render
```

Then open `_site/index.html` in your browser.

If you only want to render one page, run:

```bash
quarto render index.qmd
```

## Publish for free with GitHub Pages

This repository now includes a GitHub Actions workflow at `.github/workflows/quarto-deploy.yml`.

When you push to `main`, GitHub will:
- install Quarto
- render the website into `_site`
- publish the site to the `gh-pages` branch

After the workflow succeeds, your site will be available at:

`https://<your-github-username>.github.io/<repository-name>/`

If needed, enable GitHub Pages in your repository Settings > Pages and choose `gh-pages` as the source.
