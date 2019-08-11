# 2. Tools

From [Manage large CSS projects with ITCSS](https://www.creativebloq.com/web-design/manage-large-css-projects-itcss-101517528#layers), Harry Roberts:

> The next layer houses your globally available tooling – namely mixins and functions. Any mixin or function that does not need accessing globally should belong in the partial to which it relates. The Tools layer comes after the Settings layer because a mixin may require one of the global settings as a default parameter. Examples of global tools might be gradient mixins, font-sizing mixins and so on.

## In this layer

### Vendor

Vendor tools, including [`include-media`](https://include-media.com/).

### Mixins

Mixin utilities for global reuse.

---

_[Table of contents](../../../README.md#structure)_

[← Previous layer: Settings](../settings)

[Next layer: Generic →](../generic)
