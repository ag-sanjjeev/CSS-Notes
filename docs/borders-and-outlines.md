## &#9873; Borders and Outlines
These properties is used for displaying edges of the elements based on usage.

*Border property will draw the lines on the element whenever the page gets loaded. But outline property will highlights the element when it gets focused by keyboard navigations.*

*To apply borders or outlines to specific sides of an element, use the corresponding properties (e.g., `border-top`, `border-right`, `border-bottom`, `border-left`*

### &#9780; Overview:
1. [Border width](#-border-width)
2. [Border style](#-border-style)
3. [Border color](#-border-color)
4. [Outlines](#-outlines)

### &#10022; Border Width:
It sets the width of the border.

*Syntax: `border-width: value;`*

```css
div {
  border-width: 2px;
}
```

### &#10022; Border Style:
It sets the style of the border. Such as `dashed, dotted, double, inset, outset, ridge, solid`. To hide border for the element use the value `none`.

*Syntax: `border-style: value;`*

```css
div {
  border-style: solid;
}
```
### &#10022; Border Color:
It sets the color of the border.

*Syntax: `border-color: value;`*

```css
div {
  border-color: blue;
}
```

### &#10022; Outlines:
This will drawn a line around the outside of an element, without affecting its layout or size.

*Syntax: `outline: value;` or `outline: width style color;`*

```css
input {
  outline: 2px dotted green;
}
```

---
[&#8682; To Top](#-borders-and-outlines)

[&#10094; Previous Topic](../docs/layouts.md) &emsp; [Next Topic &#10095;](../docs/responsive-design.md)

[&#8962; Goto Home Page](../README.md)
