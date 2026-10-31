# Shixiong Zhou — academic homepage

Personal academic website based on [al-folio](https://github.com/alshedivat/al-folio).

## Content

- `_pages/about.md`: introduction and research interests
- `_bibliography/papers.bib`: published papers only
- `_data/socials.yml`: contact links

The original CV PDF is intentionally not included because it contains in-progress manuscripts.

## Preview

With Ruby 3.3+ installed:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

## GitHub Pages

Use the `ATMSaxon/atmsaxon.github.io` repository and choose GitHub Actions as the Pages source. The included workflow builds and deploys the website when changes are pushed to `main`.

The canonical site URL is `https://atczhou.ac`. GitHub Pages serves the site; DNS is managed in Spaceship.
