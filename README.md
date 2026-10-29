# Giotto Frean — Personal Webpage

Single-page personal website for showcasing research and projects, built for
hosting on GitHub Pages.

## Structure

- `index.html` — all content (single page with tabbed project sections)
- `style.css` — styling
- `main.js` — accessible tab navigation
- `assets/` — figures from my notebooks (Energy-Efficient Marine Inference,
  Multiagent Systems, Decision-Making)

## Before publishing

1. Replace the SVG avatar placeholder in `index.html` with a photo:
   `<img src="assets/photo.jpg" alt="Portrait of Giotto Frean" />`
2. Add your LinkedIn URL (marked with a TODO comment in `index.html`).
3. Export your CV as `assets/Giotto_Frean_CV.pdf` (or update the link).
4. Check the GitHub repository links match your actual repo names.

## Local preview

Just open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

and visit http://localhost:8000.
