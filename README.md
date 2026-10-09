# InteriorPainting.co

This repository is the static website for [InteriorPainting.co](https://interiorpainting.co). It will be hosted on GitHub Pages.

Interior Painting Co provides professional interior painting and decorating throughout Bristol and surrounding areas, for homes and businesses.

## Preview

From this folder:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Publish

In the GitHub repository, open Settings → Pages, set the source to the `main` branch and the `/` folder, and save. GitHub will serve the site from this repository.

To use the interiorpainting.co domain, add a `CNAME` file containing `interiorpainting.co` and point the domain’s DNS at GitHub Pages.
