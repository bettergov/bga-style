# 7. Trumps

From [Manage large CSS projects with ITCSS](https://www.creativebloq.com/web-design/manage-large-css-projects-itcss-101517528#layers), Harry Roberts:

> This layer beats – or 'trumps' – all other layers, and has the power to override anything at all that has gone before it. It is inelegant and heavy-handed, and contains utility and helper classes, hacks and overrides.
>
> A lot of the declarations in this layer will carry !important (e.g. .text-center { text-align: centre !important; }). This is the highest specificity layer – it includes the most explicit types of rule, with the most narrow focus. This layer forms the point of the Triangle.

## In this layer

### Align

- `.align-left`: Floats left tablet up, center-aligned on mobile.
- `.align-left-mobile`: Floats left on all screens, including mobile.
- `.align-right`: Floats right tablet up, center-aligned on mobile.
- `.align-right-mobile`: Floats right on all screens, including mobile.
- `.align-center`

### Typography

- Font families: `.serif`, `.sans`, `.condensed`
- Emphasis: `.bold`, `.italic`, `.caps`/`.uppercase`, `.underline`
- Text alignment: `.text-left`, `.text-center`, `.text-right`
- Overflow: `.nowrap`, `.truncate`
- Lists: `.list-unstyled`

### Widths

- `.is-full`/`.full-width`
- `.is-jumbo`
- `.is-large`
- `.is-medium`
- `.is-small`
- `.fit-outer`
- `.fit-inner`

---

_[Table of contents](../../../README.md#structure)_

[← Previous layer: Components](../components)
