# Change Log

All notable changes to the "styco" extension will be documented in this file.

## [0.1.1]

- Added a CodeAction to lines that have a `style`-Attribute. This can be disabled by setting `disableCodeAction` to `true`.

## [0.1.0]

- Full rewrite with the Babel-Parser. (Fixes at least #9)

## [0.0.8]

### Features

- Added a logo.
- Add an option to sort the generated styled components. (#7 - Thanks to @chengjo0)

## [0.0.7]

### Bugfixes

- Fixed a bug, where the corresponding closing tag couldn't be found.

## [0.0.6]

### Features

- Create a empty styled component if no style prop is found. (#6)
- Command is now executable not only in the line of the tag-name, but also on the lines below. (#3)

### Bugfixes

- If Cursor is placed on style-prop in the same line, the style-prop is now found. (#5)
