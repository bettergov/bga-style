# 4. Elements

From [Manage large CSS projects with ITCSS](https://www.creativebloq.com/web-design/manage-large-css-projects-itcss-101517528#layers), Harry Roberts:

> These are bare, unclassed HTML elements. What does an h1 look like without a class on it? What does an a look like without a class on it? The Elements layer binds onto bare HTML element (or 'type') selectors only. It is slightly more explicit than the previous layer in that we are now saying 'make every h1 this big', or 'make every a be a certain colour'. It is still a very low-specificity layer, but affects slightly less of the DOM, and is slightly more opinionated, hence its location in the Triangle.
>
> The Elements layer is typically the last one in which we'd find bare, element-based selectors, and is very rarely added to or changed after initial setup. Once we have defined element-level styles, all additions and deviations should be implemented using classes.

## In this layer

### Button

The [`<button>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details) element.

### Details

The [`<details>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details) and [`<summary>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/summary) elements.

#### Usage

```html
<details>
  <summary
    >I have keys but no doors. I have space but no room. You can enter but can’t
    leave. What am I?</summary
  >
  A keyboard.
</details>
```

### Figure

Styles for [`<figure>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure) and [`<figcaption>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figcaption).

### Headings

Heading elements `<h1>` through `<h6>`.

### Link

The [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a) element, [`:link`](https://developer.mozilla.org/en-US/docs/Web/CSS/:link) and [`:visited`](https://developer.mozilla.org/en-US/docs/Web/CSS/:visited) variants.

### Table

The [`<table>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table) element and its children.

#### Usage

```html
<table>
  <thead>
    <tr>
      <th colspan="2">The table header</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>The table body</td>
      <td>with two columns</td>
    </tr>
  </tbody>
</table>
```

### Typography

Typographic elements, including paragraphs, lists and blockquotes.

---

_[Table of contents](../../../README.md#structure)_

[← Previous layer: Generic](../generic)

[Next layer: Objects →](../objects)
