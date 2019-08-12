# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.1] - 2019-08-12

### Added

- Documented intro component
- Added overflow declarations to `<html>`

## [2.1.0] - 2019-08-12

(Some of these changes are technically breaking, but they're so small, I'm changing it so soon, and there's no current production usage.)

### Added

- Add photos to `layers/components/README.md`

### Changed

- Renamed `$accent` to `$accent-color`
- Numerous tweaks to `layers/components`

### Deleted

- Deleted `layers/components/sidebar`
- Deleted photo-set from `layers/components/art`
- Deleted `$highlight` from `layers/settings/colors`

## [2.0.0] - 2019-08-11

### Added

- Added variables `$background-color` and `$selection-color`
- Docs!
- Made the package easier to import by defining `sass` and `style` in `package.json`
- Added BGA icon mixin

### Changed

- Import from `_.scss` inside each layer directory instead of a file outside. (e.g. from `layers/components/_.scss` instead of `layers/_components.scss`)
- Renamed variable `$bga-light-background` to `$off-white`
- Significant overhaul of `layers/elements/link`
- Set html font-size using percentages
- Renamed lots of variables in `layers/settings`
- Renamed mixins in `layers/tools` to use camelCase
- Moved button and headings from `layers/objects` to `layers/elements`
- Moved alignment, width helpers to `layers/trumps`
- Moved several partials from `layers/objects` to `layers/components`
- Renamed lots of selectors, and therefore expected HTML, in `layers/components`
- Moved selectors around in `layers/trumps`

### Deleted

- Deleted typekit loading from `layers/settings/fonts`; this should be handled in the project itself
- Deleted `scss/webpack.scss` — redundant

## [1.1.0] - 2019-07-26

### Added

- Default styling and animations for details/summary elements: `elements/_details.scss`
- Add overridable variables for `$primary-text-color`, `$secondary-text-color`

### Changed

- Dropcap uses margin-right instead of padding-right
- Table styling is directly overridable now via variables `$table_border_dark`, `$table_border`, `$table_background`, `$table_text_color`
- Various uses of `$bga-alt-black`, `$bga-medium-gray` re: typography replaced with `$primary-text-color`, `$secondary-text-color`
