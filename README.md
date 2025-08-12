# CS 6300 — Artificial Intelligence (Spring 2024)

This is a GitHub Pages (Jekyll) site that ports the original HTML class website to Markdown pages.

## Local preview

```bash
gem install bundler jekyll
bundle init
# add `gem "jekyll", "~> 4.3.3"` and the plugins used in _config.yml to your Gemfile if needed
bundle add jekyll jekyll-seo-tag jekyll-sitemap jekyll-feed minima
bundle exec jekyll serve
```

Then open http://localhost:4000

## Deploy on GitHub Pages

- Create a new repository (public) named e.g. `cs6300-site`.
- Push these files to the default branch.
- In **Settings → Pages**, set **Build and deployment** to *GitHub Actions* or *Deploy from a branch*.
- If using Actions, add the standard Jekyll Pages workflow.
- Your site will be available at `https://<username>.github.io/<repo>/`.