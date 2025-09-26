# Tetloose Styles

SCSS starter package. Used as a global template for projects. Components generate their own styles, this acts as a global stylesheet.

Component CSS changes but global stuff rarely does, so we can cache this on first load.

Cherry pick + add utils, per project etc.

Use `@use '@styles/settings' as *;` in a component to make use of variables + mixins.

CSS methodologies based on BEM + SMACSS with Utility Classes.
