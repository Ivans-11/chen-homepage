# Yu Chen Homepage - Minimal Light

This repository is the Minimal Light implementation of Yu Chen's personal homepage.

It is based on [`yaoyao-liu/minimal-light`](https://github.com/yaoyao-liu/minimal-light), keeping the theme's Jekyll layout, Sass styles, sidebar profile, dark-mode support, and YAML-based selected-publication list. The homepage content itself is kept in Markdown files so routine updates do not require editing HTML.

## Content Files

- Home page: `index.md`
- Full publications: `publications.md`
- Teaching: `teaching.md`
- Students: `students.md`
- Join/recruiting: `join.md`
- Selected publications on the homepage: `_data/publications.yml`
- Site profile, navigation, and metadata: `_config.yml`
- Small local style overrides: `assets/css/style.scss`

## Local Build

Install dependencies and build the site:

```bash
bundle install
bundle exec jekyll build
```

For local preview:

```bash
bundle exec jekyll serve
```

## GitHub Pages

Publish this repository with GitHub Pages from the repository root. GitHub Pages will run Jekyll and generate the static HTML site automatically.
