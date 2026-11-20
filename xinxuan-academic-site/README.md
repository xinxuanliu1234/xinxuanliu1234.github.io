# Xinxuan Liu — Academic Website

A Quarto academic website designed for GitHub Pages.

## Edit
- `index.qmd`: homepage biography and selected research
- `research.qmd`: working papers
- `presentations.qmd`: talks
- `cv.qmd`: CV link
- `styles.css`: colours and typography
- `assets/portrait-placeholder.svg`: placeholder; replace its reference in `index.qmd` with `assets/portrait.jpg` after adding your actual portrait

## Preview
Install Quarto (https://quarto.org), then run `quarto preview` in this folder.

## Publish to GitHub Pages
1. Create a public repository named `YOURUSERNAME.github.io` on GitHub.
2. Upload all project files to its `main` branch.
3. Run `quarto render` locally; this creates `docs/`.
4. Commit and push `docs/` and other project files.
5. In GitHub Settings > Pages, choose Deploy from a branch, `main`, `/docs`.
6. Visit `https://YOURUSERNAME.github.io`.

Optional: add an empty `.nojekyll` file at the repository root (already included).

Before publishing, replace the placeholder photograph, add a verified email address and current CV, and confirm titles and publication statuses.
