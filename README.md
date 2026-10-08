# vbeauzee.github.io

Personal portfolio of Vincent Beauzée, built with Jekyll for GitHub Pages.

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

## Edit content

- `_data/en/it.yml`, `_data/fr/it.yml`: IT engineering page
- `_data/en/gamedev.yml`, `_data/fr/gamedev.yml`: game development page
- `_data/i18n.yml`: interface text in English and French
- `_data/logos.yml`: technology logos, files in `img/logos/`
- `_config.yml`: contact links

English pages live at the root, French pages under `/fr/`. Keep both data files in sync when adding an experience.

Each experience accepts an `image` path. When it is empty, the card shows its `label` and `logos` instead.
