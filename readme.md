# Lingfeng Pan Personal Website

This repository contains the source code for Lingfeng Pan's personal academic website.
The site is built with Quarto and published via GitHub Pages.

## Website

- URL: <https://lingfeng2324.github.io>
- Repo: <https://github.com/Lingfeng2324/Lingfeng2324.github.io>

## Main Pages

- `index.qmd`: Home page
- `publications.qmd`: Publications
- `Chinese.qmd`: Chinese CV
- `about.qmd`: About page

## Project Structure

- `_quarto.yml`: Site configuration (navigation, footer, output settings)
- `styles.scss`: Website styles
- `images/`: Image assets
- `docs/`: Rendered static files for deployment

## Local Development

Run in project root:

```powershell
quarto preview
```

This starts a local preview server with live reload.

## Build for Deployment

```powershell
quarto render
```

Quarto renders the website to `docs/` (configured in `_quarto.yml`).

## Deployment

This repository deploys using GitHub Pages from the `docs/` output.
After updating content:

1. Edit `.qmd` files.
2. Run `quarto render`.
3. Commit and push changes.

## Maintenance Notes

- Keep Chinese files in UTF-8 encoding to avoid garbled text.
- Prefer editing source files (`.qmd`, `_quarto.yml`, `styles.scss`) instead of generated HTML in `docs/`.