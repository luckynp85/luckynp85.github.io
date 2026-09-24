# Reliability, Visually

Interactive reliability engineering explainers, hosted on GitHub Pages.

## Files

- `index.html`: home page listing the articles
- `mle/index.html`: "The likeliest curve" (MLE and rank regression)
- `mle/preview.png`: the image shown when the link is shared on LinkedIn
- `.nojekyll`: tells GitHub to serve the files as-is

## Publish (first time)

1. (Done: your username is already filled in.)
2. On GitHub, create a **public** repository named exactly `luckynp85.github.io`.
3. Click **Add file → Upload files** and drag everything *inside* this folder (not the folder itself) into the page. Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
5. After a minute or two the site is live at `https://luckynp85.github.io/` and the article at `https://luckynp85.github.io/mle/`.

## Add a new article

1. Make a new folder, e.g. `weibull-vs-lognormal/`, containing an `index.html`.
2. Add a card for it in the home page's `index.html`.
3. Upload both and commit. The site updates automatically.

## Custom domain (optional)

Buy a domain, then enter it under **Settings → Pages → Custom domain** and follow GitHub's DNS instructions. Tick **Enforce HTTPS** once it's available.
