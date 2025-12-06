# Coderack Personal Site

This repository hosts the `coderack.com` site built with [Jekyll](https://jekyllrb.com/) and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

## Deployment

GitHub Pages is deployed with the workflow defined in `.github/workflows/pages.yml`. The action runs on every push to `main`, builds the site with Ruby 3.3, and publishes the `_site` artifact via `actions/deploy-pages@v4`.

If you make dependency or configuration changes, push them to `main` and the workflow will rebuild and redeploy automatically. You can also trigger it manually from the **Actions** tab using the “Run workflow” button.
