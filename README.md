# Coderack Personal Site

This repository hosts the `coderack.com` site built with [Jekyll](https://jekyllrb.com/) and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

## Deployment

GitHub Pages is deployed with the workflow defined in `.github/workflows/pages.yml`. It follows the official [Actions starter workflow](https://github.com/actions/starter-workflows/blob/main/pages/jekyll.yml), using `actions/jekyll-build-pages@v1` plus `actions/deploy-pages@v4` whenever you push to `main` (or dispatch manually from the **Actions** tab).

Any dependency or configuration change committed to `main` is automatically rebuilt and published through that workflow—no local build artifacts need to be checked in.
