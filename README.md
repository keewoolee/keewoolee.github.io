# keewoolee.github.io

Source for my personal homepage, <https://keewoolee.github.io>.

A hand-written static site: a single `index.html` plus `style.css`, with no
build step. The only runtime dependency is [KaTeX](https://katex.org/) (via CDN)
for rendering LaTeX in publication titles.

## Structure

```
index.html        # the whole page
style.css         # all styling
.nojekyll         # tells GitHub Pages to serve files as-is (no Jekyll build)
assets/
  favicon.svg
  img/            # profile photos
  pdf/            # CV and talk slides
```

## Local preview

Any static file server works, e.g.:

```sh
python3 -m http.server 8910
```

then open <http://localhost:8910>.

## Deploy

GitHub Pages serves the `master` branch root directly. Pushing to `master`
publishes the site.
