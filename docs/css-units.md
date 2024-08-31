## &#9873; CSS Units
The CSS Units are used to specify the unit of measurements for value of the properties.

*There are almost 5 type of Units in CSS.*

### &#9780; Overview:
1. [Pixels (px)](#-pixels)
2. [Percentages (%)](#-percentages)
3. [Ems (em)](#-ems)
4. [Rems (rem)](#-rems)
5. [Viewport units (vw, vh, vmax, vmin)](#-viewport-units)

### &#10022; Pixels:
It is a fixed unit of measurement that represents one pixel on the screen.

*Syntax: `value px`*

```css
p {
  font-size: 16px;
}
```

### &#10022; Percentages:
It is a relative unit of measurement that represents a percentage of the parent element's size.

*Syntax: `value %`*

```css
div {
  width: 50%;
}
```

### &#10022; Ems:
It is a relative unit of measurement that represents the font size of the element's parent

*Syntax: `value em`*

```css
p {
  font-size: 1.2em;
}
```

### &#10022; Rems:
It is a relative unit of measurement that represents the font size of the root element (usually the `<html>` element).

*Syntax: `value rem`*

```css
p {
  font-size: 1.5rem;
}
```

### &#10022; Viewport Units:
It is a relative units of measurement based on the viewport size (the visible area of the browser window)

*Syntax:*
- `vw`: Viewport width,
- `vh`: Viewport height,
- `vmax`: Maximum of viewport width and height,
- `vmin`: Minimum of viewport width and height.

```css
div {
  font-size: 2vw;
  height: 100vh;
}
```

---
[&#8682; To Top](#-css-units)

[&#10094; Previous Topic](../docs/properties-and-values.md) &emsp; [Next Topic &#10095;](./topic.md)

[&#8962; Goto Home Page](../README.md)
