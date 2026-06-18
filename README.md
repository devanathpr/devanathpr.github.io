# devanathpr.github.io

Personal academic website for Devanath P R — Scientific Assistant (Library) at ICTS-TIFR, Bangalore, and doctoral researcher in research evaluation.

## Structure

```
index.html         Home
about.html          About / bio / timeline
research.html       Publications, talks, distinctions
contact.html        Contact details
assets/css/style.css  Shared stylesheet
```

## Publishing on GitHub Pages

1. Create (or reuse) a repository named `<your-username>.github.io`.
2. Push these files to the `main` branch, at the repository root (not inside a subfolder).
3. In the repo settings → **Pages**, set the source to `main` / `root`.
4. The site will be live at `https://<your-username>.github.io/` within a few minutes.

No build step is required — this is plain HTML/CSS, so GitHub Pages serves it as-is.

## Editing content later

- **New publication or talk:** open `research.html` and copy one `<div class="index-card">…</div>` block, then edit the year, title, venue, and DOI/link.
- **New job or degree:** open `about.html` and copy one `<div class="timeline-entry">…</div>` block.
- **Bio text:** edit the paragraphs directly inside `about.html` and `index.html`.
- **Colors/fonts:** all defined as CSS variables at the top of `assets/css/style.css` under `:root`.

## Last updated

June 2026
