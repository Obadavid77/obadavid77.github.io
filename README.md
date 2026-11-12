# obadavid77.github.io

Source for Oba Adelore's portfolio, published with GitHub Pages at <https://obadavid77.github.io/>.

It is a single static page written in plain HTML and CSS. There is no build step, framework, tracking script or backend.

## Files

- `index.html`: the portfolio page, with its styles inline
- `404.html`: the page shown for unknown addresses
- `assets/`: the portrait, two project images and the favicon
- `.nojekyll`: tells GitHub Pages to serve the files as they are
- `robots.txt` and `sitemap.xml`: search engine hints

## Updating the site

1. Edit `index.html` (or replace an image in `assets/` with the same file name).
2. Open `index.html` in a browser and check the change at phone and desktop widths.
3. Commit to `main`. GitHub Pages republishes automatically, usually within a few minutes.

To undo a change, revert the commit (`git revert <commit>`) and push. Avoid force pushes so the history stays intact.
