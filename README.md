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

## Layout (optional)

- Row
- Action

# Print styles

`print.scss` used to generate a print style sheet.

# Tinymce

`tinymce.scss` used to generate a style sheet for tinymce editor. (Some CMS use this)

# Wordpress

`wordpress.scss` used to generate a style sheet for Wordpress Login.

# Colours & Fonts

- Color vars are located `scss/settings/colors.scss`.
- Font vars are located `scss/settings/fonts.scss`.

These rely on CSS variables that are injected into the head via a CMS / Application.

They can be overriden with static values or you can add this to the SCSS / Head `<style>` tag.

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

These values will be picked up in the SCSS.

# Icons

Build an icon pack using [icomoon.io](https://icomoon.io/), download your icon pack.

## Process

1. Extract the zip
2. Rename the font files to **icons.{svg,ttf,woff}**

Place `selection.json` and `icons.{svg,ttf,woff}` into the folder `icons`. Copy values from the generated CSS, replace line **13** to **72** in `scss/utils/icons.scss` with copied CSS.

## MARKUP

`<i class="u-icon-arrow-left"><i>`

## Editing

Upload `selection.json` to [icomoon.io](https://icomoon.io/), edit your icons, repeate the above process.
