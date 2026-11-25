# Personal website

Static site for GitHub Pages: `index.html`, `style.css`, `images/`, `files/`. No build step.

## Publish

1. Create a public GitHub repository named exactly `raybal007.github.io` (your GitHub username).
2. Push this folder to it. GitHub serves it at `https://raybal007.github.io` within a few minutes
   (Settings → Pages, source "Deploy from a branch", branch `main`, folder `/`).

## Update

- New CV: replace `files/Raybal_Ahmad_CV.pdf` (keep the name so the links still work).
- New paper draft: replace `files/Ahmad_Pediatric_Exclusivity.pdf`.
- New project: copy the commented-out block at the end of the Research section in `index.html`.

## Preview locally

```bash
python3 -m http.server 8765
```
then open http://localhost:8765.
