# GAIA & ECO Workshop Website

Simple Jekyll site for:
- 1st Workshop for Green AI Application (GAIA Workshop)
- 6th Workshop for Next-generation Software Ecosystems (ECO Workshop)

This repository contains the site source used to build the workshop website.

## Contents (important files)
- [index.markdown](index.markdown) — main page content
- [_config.yml](_config.yml) — Jekyll configuration (uses remote_theme `pages-themes/cayman@v0.2.0`)
- [Gemfile](Gemfile) — Ruby/Jekyll dependencies
- [assets/css/style.scss](assets/css/style.scss) — custom styles

## Quick start (Linux)

1. Install Bundler and project gems:
   ```
   gem install bundler
   bundle install
   ```

2. Run the site locally:
   ```
   bundle exec jekyll serve
   ```
   Open http://127.0.0.1:4000 in your browser.

3. Build for production:
   bundle exec jekyll build
   Output is written to the _site directory (see .gitignore).

## Local editing
- Edit page content in [index.markdown](index.markdown).
- Change styles in [assets/css/style.scss](assets/css/style.scss).
- Add images under assets/img/.

## Notes
- This repo uses a remote theme defined in [_config.yml](_config.yml). To override theme defaults, add/modify files in the repository (layouts, includes, assets).
- Use `bundle exec` to ensure the versions in the Gemfile are respected.
