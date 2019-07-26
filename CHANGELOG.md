# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2019-07-26

### Added

- Default styling and animations for details/summary elements: `elements/_details.scss`
- Add overridable variables for `$primary-text-color`, `$secondary-text-color`

### Changed

- Dropcap uses margin-right instead of padding-right
- Table styling is directly overridable now via variables `$table_border_dark`, `$table_border`, `$table_background`, `$table_text_color`
- Various uses of `$bga-alt-black`, `$bga-medium-gray` re: typography replaced with `$primary-text-color`, `$secondary-text-color`
