# Design For Impact

This is a Quarto website that renders to `docs/` for GitHub Pages. Open `design-for-impact.Rproj` in RStudio or Positron, then use **Build > Render Website** to refresh the site locally.

## Publishing after review

1. Render the site so `docs/index.html` is current.
2. Commit and push the reviewed source and `docs/` output to `main`.
3. In GitHub, open **Settings > Pages** and set the source to **Deploy from a branch**, then choose **main** and **/docs**.

The root `.nojekyll` file is copied into `docs/` during rendering so GitHub Pages serves Quarto's static output without attempting a Jekyll build. The expected published URL is `https://jettpalmer.github.io/design-for-impact/`.
