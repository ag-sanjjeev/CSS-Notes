## &#9873; Responsive Design
These properties is used for displaying edges of the elements based on usage.

*Border property will draw the lines on the element whenever the page gets loaded. But outline property will highlights the element when it gets focused by keyboard navigations.*

*To apply borders or outlines to specific sides of an element, use the corresponding properties (e.g., `border-top`, `border-right`, `border-bottom`, `border-left`*

### &#9780; Overview:
1. [Media queries](#-media-queries)
2. [Flexible layouts](#-flexible-layouts)
3. [Responsive images](#-responsive-images)
4. [Fluid typography](#-fluid-typography)

### &#10022; Media queries:
The conditional statements that allow to apply styles based on the screen size or other device characteristics

*Syntax:*
```css 
@media screen and (min-width: 768px) {
  /* Styles for screens wider than 768 pixels */
}
```

*Example:*
```css
@media screen and (max-width: 600px) {
  h1 {
    font-size: 24px;
  }
}
```

### &#10022; Flexible layouts:
The layouts that adapt to different screen sizes by using [relative units](./css-units.md) and flexible properties.

```css
div {
  max-width: 100%;
  height: auto;
}
```

### &#10022; Responsive images:
This will automatically adjust the size of the images to fit the screen by applying [relative units](./css-units.md) or using [source tags](https://github.com/ag-sanjjeev/HTML-Notes/tags/source-tag.md).

```xml
<img src="image.jpg" alt="Image" width="100%">
```

```xml
<picture>
  <source media="(min-width: 768px)" srcset="image-large.jpg">
  <source media="(min-width: 480px)" srcset="image-medium.jpg">
  <img src="image-small.jpg" alt="Image">
</picture>
```

### &#10022; Fluid typography:
This will adjusts the text font size based on the screen width.

```css
body {
  font-size: calc(16px + (20 - 16) * ((100vw - 320px) / (1280 - 320)));
}
```
```css
@media screen and (max-width: 768px) {
  body {
    font-size: 18px;
  }
}
```

---
[&#8682; To Top](#-responsive-design)

[&#10094; Previous Topic](../docs/borders-and-outlines.md) &emsp; [Next Topic &#10095;](../docs/css-animations.md)

[&#8962; Goto Home Page](../README.md)
