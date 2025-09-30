# Intro to SASS
Sass is a CSS preprocessor that extends CSS with programming features. It adds variables for reusable values, nesting for cleaner hierarchy, mixins for reusable style blocks, functions for calculations, and inheritance via `@extend`. This makes stylesheets more maintainable, DRY (Don't Repeat Yourself), and scalable. Sass compiles down to standard CSS that browsers understand. It helps developers write less code, organize styles better, and manage large projects more efficiently. Two syntaxes exist: SCSS (CSS-like with braces) and Sass (indented, no braces) - SCSS is more popular.

### Install
[pnpm|npm] add -D sass
npm install sass --save-dev

### Basic Command
[pnpm|npm] sass [input] [output]

### Watch (flag)
--watch

### Minification (flag)
--style=compressed

### Quiet depreciation messages (flag)
--quiet-deps