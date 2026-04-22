# Growing LLMs Beyond Boundaries

This repository contains the Jekyll site for the GLB² project landing page.

## Local development

1. Install Ruby 3.x and Bundler.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve`.
4. Open `http://127.0.0.1:4000`.

## Main files

- `_config.yml`: site-wide title, navigation, colors, and Jekyll settings.
- `index.html`: homepage content.
- `core-knowledge.md`, `vlm-gaze.md`, `babysit-llm.md`, `not-just-scaling.md`, `world-to-words.md`: section pages.
- `_layouts/` and `_includes/`: shared Jekyll templates.
- `assets/css/` and `assets/js/`: shared styling and client-side behavior.

## Deployment

GitHub Actions builds the site with Jekyll using `.github/workflows/ci.yml`.
