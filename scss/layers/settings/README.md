# 1. Settings

From [Manage large CSS projects with ITCSS](https://www.creativebloq.com/web-design/manage-large-css-projects-itcss-101517528#layers), Harry Roberts:

> If you are using a preprocessor, start here. This holds any global settings for your project. I'd like to stress the word global – this layer should only house settings that need to be accessed from anywhere. Settings like \$heading-size-1 should be defined in the Headings partial. This ensures this layer stays nice and slim, and means that most settings can be found alongside the code that uses them, making finding things far simpler.
>
> Examples of global settings might be things like the base font size, colour palettes, config (for example, \$environment: dev;) and so on.

## In this layer

### Breakpoints

Defines breakpoints for use with [`include-media`](https://include-media.com/).

### Colors

Defines global colors.

### Layout

Define variables for use with layout, including:

- `$max-content-width`
- `$desktop-max-content-width`
- `$spacing-standard`

### Typography

Define variables for use with typography, including:

- Font families:
  - `$font-family-condensed`
  - `$font-family-sans`
  - `$font-family-serif`
- Font sizes:
  - `$font-size-large`
  - `$font-size-normal`
- Paragraph properties:
  - `$paragraph-line-height`
  - `$paragraph-width-tablet`
  - `$paragraph-width-desktop`

---

_[Table of contents](../../../README.md#structure)_

[Next layer: Tools →](../tools)
