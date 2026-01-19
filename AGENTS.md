# Project Context

This repo is a personal "About me" website for Ganesh Raman. It is a
Jekyll site configured as a resume-style single-page profile using a
remote theme.

## Stack and Theme
- Jekyll site using the `sproogen/resume-theme` remote theme.
- Gem dependencies via `Gemfile` (GitHub Pages bundle).
- Most content is driven from `_config.yml`.

## Key Files and Folders
- `_config.yml`: primary content source (name, title, links, about text,
  and experience/education sections).
- `index.md`: Jekyll front matter for the home page layout.
- `images/`: profile image and favicon.
- `assets/`: static assets (if needed for custom styling or scripts).

## Content Editing Notes
- Update `about_content`, `content` sections, and social links in
  `_config.yml`.
- `about_profile_image` should point to an image under `images/`.
- Keep YAML indentation consistent and avoid tabs.

## Local Preview
- Install dependencies: `bundle install`.
- Run locally: `bundle exec jekyll serve`.

