# Heyang Yu — Academic homepage

Personalized from [Tsuruko04/academic-homepage](https://github.com/Tsuruko04/academic-homepage), based on [luost26/academic-homepage](https://github.com/luost26/academic-homepage). The original Jekyll structure, two-column layout, Bootstrap styling, publication cards, license, and template attribution are retained.

## Edit your information

- **`_data/profile.yml`**: name, affiliation, biography, Scholar ID, optional contact links, research interests, education, and experience. Commented examples show how to fill in the reserved sections. Empty research and education lists display placeholders.
- **`_publications/*.md`**: one Markdown file per publication, with authors, venue, year, and links in YAML front matter.
- **`assets/images/photos/portrait.jpg`**: replace this file to update your portrait.
- **`_data/navigation.yml`**: navigation links.
- **`_config.yml`**: site description and hosting path.

## Run locally

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 5173 --baseurl ""
```

Open http://localhost:5173. Jekyll rebuilds when content changes; restart it after editing `_config.yml`.

## Build and host

```sh
bundle exec jekyll build
```

The generated `_site/` directory is ready for static hosting. The `baseurl` in `_config.yml` is set to `/academic-homepage` for this GitHub Pages project repository. For a root site such as `username.github.io`, leave it empty. Use a Jekyll build workflow to build and upload `_site/`; the template includes the `jekyll-email-protect` plugin. Nothing has been published automatically.

## Content source

Profile, portrait, and publication metadata came from [Heyang Yu’s Google Scholar profile](https://scholar.google.com/citations?user=GVI6jVsAAAAJ&hl=en), retrieved September 28, 2026. Duplicate AgentVerse and Thinking in 360 listings were consolidated. Abbreviated author lists follow Scholar; publication dates use January 1 only to group by year. Education and research interests are intentionally left for you to fill in.

The previous custom homepage was backed up outside this repository at `/tmp/heyang-original-homepage`.
