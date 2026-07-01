# Repository Guidelines

## Project Structure & Module Organization

This is a Jekyll-based personal site using the al-folio theme. Site configuration lives in `_config.yml`, reusable Liquid components are in `_includes/`, page templates are in `_layouts/`, and custom Ruby plugins are in `_plugins/`. Content collections live in `_pages/`, `_posts/`, `_projects/`, `_news/`, and `_teaching/`; name dated posts as `YYYY-MM-DD-title.md`. Structured data belongs in `_data/`, bibliography entries in `_bibliography/papers.bib`, Sass in `_sass/`, and static files in `assets/` by media type such as `assets/img/`, `assets/pdf/`, and `assets/js/`.

## Build, Test, and Development Commands

- `bundle install`: install Ruby gems from `Gemfile`.
- `npm install`: install Prettier and the Liquid plugin from `package.json`.
- `bundle exec jekyll serve`: run the site locally with live rebuilds.
- `bundle exec jekyll build`: build the static site into `_site/`; this is the core CI build.
- `bin/cibuild`: wrapper for the CI Jekyll build.
- `npx prettier . --check`: verify formatting for Markdown, YAML, Liquid, HTML, CSS, and JavaScript.
- `npx prettier . --write`: apply formatting before committing.
- Docker local run: use the Ruby 3.2 container command below; the stock al-folio `latest` image currently uses Ruby 4 and fails on this repo.

## Local Docker Runbook

Make sure Docker Desktop is running, then start the site with Ruby 3.2.2, matching `.github/workflows/deploy.yml`:

```bash
docker run --rm --name shashmehta-alfolio-local \
  -p 8080:8080 -p 35729:35729 \
  -v "$PWD:/srv/jekyll" -w /srv/jekyll \
  -e JEKYLL_ENV=development -e BUNDLE_PATH=/tmp/bundle \
  ruby:3.2.2-bookworm \
  bash -lc 'apt-get update -qq && apt-get install -y --no-install-recommends imagemagick python3-pip inotify-tools procps >/tmp/apt-install.log && pip3 install nbconvert --break-system-packages >/tmp/pip-install.log && gem install bundler -v 2.5.7 --no-document >/tmp/bundler-install.log && bundle _2.5.7_ install && bundle _2.5.7_ exec jekyll serve --host 0.0.0.0 --port 8080 --livereload --livereload-port 35729'
```

Open `http://localhost:8080`. Stop the server with `docker stop shashmehta-alfolio-local`. If Docker socket access is denied from the sandbox, rerun Docker commands with escalated tool permissions.

## Coding Style & Naming Conventions

Use Prettier as the source of truth for formatting. Keep Markdown front matter valid YAML, prefer lowercase kebab-case filenames for posts and content pages, and keep Liquid includes small and reusable. Follow existing indentation in Ruby, Liquid, YAML, and Sass files; avoid broad theme refactors when editing personal content.

## Testing Guidelines

There is no unit test suite in this repository. Validate changes by running `bundle exec jekyll build` and `npx prettier . --check` before opening a PR. For visual or accessibility-sensitive changes, preview with `bundle exec jekyll serve` and inspect affected pages in a browser. CI also includes deploy builds, broken-link checks, accessibility checks, Lighthouse reporting, and Prettier checks.

## Commit & Pull Request Guidelines

Recent local commits use short, imperative summaries such as `Updated CV` or `Removed sync from template from INSTALL.md`. Keep commits focused and describe the user-visible change. PRs should include a concise description, linked issue when applicable, screenshots for layout or asset changes, and notes on local validation commands run. Do not commit generated `_site/` output.
