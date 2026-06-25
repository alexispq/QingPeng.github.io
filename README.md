# Qing Peng Academic Website

This repository contains a static GitHub Pages-ready academic website for Qing Peng.

The site is currently built as plain HTML and CSS in the style of a concise one-page academic CV site. It can be previewed locally without installing Hugo, Node packages, or any deployment tooling. Nothing is public until the local changes are committed and pushed to GitHub.

## Local Preview

From the repository root:

```powershell
python -m http.server 4173
```

Then open <http://127.0.0.1:4173/>.

## Main Files

- `index.html`: the public website.
- `assets/css/styles.css`: visual design and responsive layout.
- `assets/images/qing-peng.jpg`: optimized portrait used on the homepage.
- `assets/files/qing-peng-cv.pdf`: local copy of the C.V.
- `data/writings.json`: structured research metadata for future maintenance.

## Publication

The included GitHub Actions workflow deploys the static site to GitHub Pages after a push to `main`. Do not push until Qing has approved the local preview.
