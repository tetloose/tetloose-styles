# Tetloose Styles

SCSS starter package. Used as a global template for projects. Components generate their own styles, this acts as a global stylesheet.

Component CSS changes but global stuff rarely does, so we can cache this on first load.

Cherry pick + add utils, per project etc.

Import `@import '../path-to-settings/settings/index.scss'` in a component to make use of variables + mixins.

CSS methodologie Based on BEM + SMACSS with Utility Classes.

## Reset (optional)

- Box Sizing
- Form Normalize
- Html Normalize

## Settings

- Variables
- Mixins
- Colors Global
- Font Sizes
- Typography Sizes

## Utils (optional)

- Utility Classes

## Global (optional)

- Global Html Style
- Selection Style
- Fonts Family

## Layout (optional)

- Container
- Row / Col
- Actions

# Print styles

`print.scss` used to generate a print style sheet.

# Tinymce

`tinymce.scss` used to generate a style sheet for tinymce editor. (Some CMS use this)
