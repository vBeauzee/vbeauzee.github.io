# vbeauzee.github.io

Personal portfolio of Vincent Beauzée, built with Jekyll for GitHub Pages.

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

## Edit content

- `_data/it.yml`: IT engineering page
- `_data/gamedev.yml`: game development page
- `_data/logos.yml`: technology logos, files in `img/logos/`
- `_config.yml`: contact links and CV files

Each experience accepts an `image` path. When it is empty, the card shows its `label` and `logos` instead.
