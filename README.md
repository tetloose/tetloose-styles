# Tetloose Styles

SCSS starter package. Used as a global template for projects. Components generate their own styles, this acts as a global stylesheet.

Component CSS changes but global stuff rarely does, so we can cache this on first load.

Cherry pick + add utils, per project etc.

Import `@import '../path-to-settings/settings/index.scss'` in a component to make use of variables + mixins.

CSS methodologie Based on BEM + SMACSS with Utility Classes.

## CSS Colours and Fonts

Add this to your css file / head, the values will be passed into the scss.

```
:root {
    --f-body: 'Roboto Mono', monospace;
    --f-body-light: 400;
    --f-body-regular: 400;
    --f-body-medium: 700;
    --f-body-bold: 700;
    --f-heading: 'Roboto Mono', monospace;
    --f-heading-light: 400;
    --f-heading-regular: 400;
    --f-heading-medium: 700;
    --f-heading-bold: 700;
    --light: #ffffff;
    --dark: #010101;
    --color-1: #d0fd80;
    --color-2: #fe557e;
    --color-3: #590d82;
    --color-4: #94c5da;
}
```

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

## Layout (optional)

- Row
- Action

# Print styles

`print.scss` used to generate a print style sheet.

# Tinymce

`tinymce.scss` used to generate a style sheet for tinymce editor. (Some CMS use this)
