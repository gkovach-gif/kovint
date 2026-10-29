# Kovint Concepts & Consulting

Static website for Kovint Concepts & Consulting LLC, hosted on GitHub Pages.

Edit `index.html` and push to `main`; GitHub Pages republishes automatically within a minute or two.

## Logos

`assets/logo/` holds the brand files. `kovint-wordmark.png` (nav) and `kovint-logo-full.png` (footer) are web-sized versions with the background removed so they sit on any dark color. The `-original` files are the source artwork; `kovint-logo-light.png` is the version for white backgrounds.

## Fonts

Brand type is Gotham Narrow Ultra Italic (primary headers) and Gotham Thin Italic (secondary headers). Gotham needs a web font license from Typography.com, so the site uses Montserrat (free, Google Fonts) as a stand-in. To switch, add the licensed Gotham web font CSS and change `--f-primary` / `--f-secondary` at the top of `index.html`. Don't commit the desktop `.otf` files: this repo is public.
