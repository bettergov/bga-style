# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Added variables `$background-color` and `$selection-color`
- Docs!

### Changed

- Import from `_.scss` inside each layer directory instead of a file outside. (e.g. from `layers/components/_.scss` instead of `layers/_components.scss`)
- Renamed variable `$bga-light-background` to `$bga-off-white`
- Significant overhaul of `layers/elements/link`
- Set html font-size using percentages

### Deleted

- Deleted typekit loading from `layers/settings/fonts`; this should be handled in the project itself

## [1.1.0] - 2019-07-26

### Added

- Default styling and animations for details/summary elements: `elements/_details.scss`
- Add overridable variables for `$primary-text-color`, `$secondary-text-color`

### Changed

- Dropcap uses margin-right instead of padding-right
- Table styling is directly overridable now via variables `$table_border_dark`, `$table_border`, `$table_background`, `$table_text_color`
- Various uses of `$bga-alt-black`, `$bga-medium-gray` re: typography replaced with `$primary-text-color`, `$secondary-text-color`
