# Nadine Berner — GitHub Pages

A Jekyll-based personal research and data science portfolio.

## 1. Create the repository

For a user site, GitHub requires the repository to be named:

`YOUR-USERNAME.github.io`

Replace `YOUR-USERNAME` with your GitHub username.

## 2. Replace placeholders

Search the repository for:

- `USERNAME`
- `YOUR-EMAIL@example.com`
- `REPOSITORY`

Update them with your actual links.

## 3. Enable GitHub Pages

On GitHub:

**Repository → Settings → Pages → Build and deployment → Source: GitHub Actions**

Push to `main`. The workflow in `.github/workflows/pages.yml` will build and deploy the site.

## 4. Local preview

Install Ruby and Bundler, then:

```bash
bundle install
bundle exec jekyll serve --baseurl=""
```

Open:

http://localhost:4000

## 5. Content roadmap

Recommended next steps:

1. Replace the placeholder bio with the final version.
2. Add 3–5 real project pages under `_projects/`.
3. Replace the sample publications with the complete publication record.
4. Add DOI / GitHub / preprint links.
5. Add real scientific visualisations to project pages.
6. Add your CV, ORCID and Google Scholar links.
7. Point `url` in `_config.yml` to your final domain.
8. If keeping `nadineberner.eu`, configure it as a custom domain in GitHub Pages.

## Design principle

The site is intentionally content-first: research credibility + real projects + restrained visual design, rather than a generic developer portfolio.
