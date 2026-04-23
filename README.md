# Aniket Supe — Design Educator Portfolio

**Live Portfolio:** Open `index.html` in any browser, or deploy to GitHub Pages.

## Setup for GitHub Pages

1. Push this folder to a GitHub repository
2. Go to Settings → Pages
3. Set Source to `main` branch, `/ (root)`
4. Your portfolio will be live at `https://yourusername.github.io/repo-name`

## File Structure

```
index.html                              ← Main portfolio (open this)
Aniket.png                              ← Profile photo (590×788, portrait)
Empathetic Social Media UI Screens1.png ← Hero case study screens
Empathetic Social Media UI Screens2.png
Empathetic Social Media UI Screens3.png
Handloom Wiever Ergonomic Study.png     ← Student outcome — Solapur weavers
LPG Regulator Interaction Design.png    ← Student outcome — LPG module
Productmanagement dashboard (1).png     ← Dashboard / industry work
Screenshot 2026-04-22 231338.png        ← Field study documentation
Screenshot 2026-04-22 231338 (1).png
Screenshot 2026-04-22 231347.png
```

## Image Handling Notes

| Image | Dimensions | Treatment |
|-------|-----------|-----------|
| Aniket.png | 590×788 (portrait) | `aspect-ratio: 3/4`, `object-fit: cover`, face preserved via `object-position: top` |
| Social media screens | 786×1704 (tall portrait) | `aspect-ratio: 9/19`, shown as phone mockups |
| Handloom / LPG | ~800×460 (landscape) | `aspect-ratio: 16/9`, `object-fit: cover` |
| Dashboard | 2880×2728 (square) | `aspect-ratio: 4/3`, `object-fit: contain`, dark bg |
| Screenshots | ~200×200 (small) | Square grid thumbnails, `object-fit: cover` |
