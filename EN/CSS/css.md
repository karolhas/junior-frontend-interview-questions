### 1. **What is CSS and why is it used?**

**CSS (Cascading Style Sheets)** is used to style and layout web pages by controlling the appearance of HTML elements.

---

### 2. **What are the elements of the CSS Box Model?**

The Box Model includes content, padding, border, and margin, defining the space an element occupies.

---

### 3. **What is the difference between class and ID in CSS?**

- **Classes** (`.class`) are reusable and can be applied to multiple elements
- **IDs** (`#id`) are unique to a single element

---

### 4. **How can CSS be integrated into an HTML page?**

There are three ways of integrating CSS into HTML:

- Using `<style>` tags in the `<head>` section
- Using an external `.css` file
- Linking via `<link>` in the HTML `<head>` to include an external stylesheet

---

### 5. **What is the difference between margin and padding?**

- **Margin**: External spacing outside the element's border
- **Padding**: Internal spacing inside the element's border

---

### 6. **How to center a div?**

There are several ways, but the simplest one is to make the parent element:

```css
div {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

---

### 7. **What are pseudo-classes and which ones do you know?**

A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). For example, the pseudo-class `:hover` can be used to select a button when a user's pointer hovers over it. Common pseudo-classes include `:hover`, `:focus`, `:visited`, `:active`, `:nth-child`, and others.

---

### 8. **What are pseudo-elements?**

A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s). The most popular pseudo-elements are `::before`, `::after`, and `::first-letter`.

---

### 9. **What are the values of the display property and how do they work?**

The CSS property `display` determines how a specific HTML element should be displayed.

- `display: none` - the element is not displayed at all
- `display: block` - elements are stacked vertically and try to expand to the full available width
- `display: inline` - elements are placed on the same line sequentially; width and height are determined by content and cannot be manually changed
- `display: inline-block` - the element is inline but its width and height can be changed
- `display: flex` - enables flexbox layout
- `display: grid` - enables grid layout

---

### 10. **What is the difference between display: none and visibility: hidden?**

- `display: none` - removes the element from the layout; the space it occupied is closed up
- `visibility: hidden` - hides the element but maintains its space in the layout

---

### 11. **How does the float property work in CSS?**

The `float` CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).

---

### 12. **What are media queries?**

Media queries are used in cases where different CSS styles need to be applied for different devices based on their display type (e.g., printer, monitor, or smartphone), as well as specific device characteristics (e.g., browser window width) or external environment conditions (e.g., ambient lighting). It uses the `@media` rule to include a block of CSS properties only if a certain condition is true.

---

### 13. **What is the position property? What values does it accept and how does each value behave?**

The `position` CSS property sets how an element is positioned in a document. The `top`, `right`, `bottom`, and `left` properties determine the final location of positioned elements.

- `static`: The element is positioned according to the Normal Flow of the document. The top, right, bottom, left, and z-index properties have no effect. This is the default value
- `relative`: The element is positioned according to the normal flow of the document, and then offset relative to itself based on the values of top, right, bottom, and left. The offset does not affect the position of any other elements
- `absolute`: The element is removed from the normal document flow, and no space is created for the element in the page layout. The element is positioned relative to its closest positioned ancestor (if any) or to the initial containing block
- `fixed`: Positioning freezes the block in place, so when the page is scrolled, the fixed element remains in its position and does not scroll with the page
- `sticky`: Positioning is similar to fixed positioning, but it is attached within a specific block rather than the entire document

---

### 14. **What is flexbox?**

Flexbox is a layout module that provides a flexible way to arrange and align elements within a container. It allows for easy manipulation of the size, position, and spacing of elements, making it ideal for creating responsive and dynamic layouts. With flexbox, you can easily create complex and multi-directional layouts without relying on floats or positioning hacks.

---

### 15. **What is grid?**

Grid is a layout system that allows you to create complex, grid-based designs for web pages. CSS Grid Layout provides a two-dimensional grid structure, where you can define rows and columns to position and align elements within the grid.

---

### 16. **What is a CSS preprocessor?**

CSS preprocessors are scripting languages that extend the default capabilities of CSS. They enable us to use logic in our CSS code, such as variables, nesting, inheritance, mixins, functions, and mathematical operations. The most popular preprocessors are: _Sass, Less_.

---

### 17. **Name some CSS frameworks.**

CSS frameworks are libraries that make web page styling easier. Some of them are: **TailwindCSS, Bootstrap, Bulma, Foundation**.

---

### 18. **How do you optimize CSS for better performance?**

- Minify and compress your files
- Reduce nesting
- Avoid the `@import` statement (use `<link>` in the `<head>` instead, e.g., to import fonts)
- Avoid unnecessary selectors
- Use efficient selectors

---

### 19. **What is the transition property?**

Transition allows you to define a transitional state between two states of an element. Different states can be defined using pseudo-classes such as :hover or :active, or dynamically set using JavaScript.

---

### 20. **What are keyframes?**

Keyframes are used to define specific animation steps or states during an animation. They allow you to specify the intermediate styles or property values that an element should have at various points in time during the animation.

---

### 21. **What is the difference between transitions and animations?**

- Transitions smoothly change properties over time.
- Animations create complex sequences using keyframes.

---

### 22. **How do you use inheritance in CSS?**

Child elements inherit certain styles from parent elements unless overridden.

---

### 23. **What are the different ways to specify colors in CSS?**

- Named colors
- HEX codes
- RGB/RGBA
- HSL/HSLA values

---

### 24. **How do you create and use CSS variables (custom properties)?**

Declare with `--var-name: value;` and use with: `var(--var-name);`

---

### 25. **What do you understand about the universal selector?**

A universal selector is a `*` selector that matches any element type's name instead of selecting elements of a particular type.

Example:

```css
* {
  color: blue;
  font-size: 10px;
}
```

---

### 26. **What is box-sizing?**

The CSS property `box-sizing` determines how the total width and height of an element are calculated. When set to `border-box`, the width and height properties include the content, padding, and borders but do not include the margin.

---

### 27. **Define z-index.**

`z-index` is used to specify the stack order of elements that overlap each other. Its default value is zero and can take both negative and positive values. A higher `z-index` value is stacked above the lower index element. It takes the following values: auto, number, initial, and inherit.

---

### 28. **What are vendor prefixes, and why are they used in CSS?**

Browser-specific prefixes (e.g., `-webkit-`) for experimental features not yet standardized.

---

### 29. **What is the difference between em and rem units?**

- `em` is relative to the parent font size
- `rem` is relative to the root (`html`) font size

---

### 30. **What is the calc() function in CSS, and how do you use it?**

The `calc()` CSS function lets you perform calculations when specifying CSS property values. It can be used with: `<length>`, `<frequency>`, `<angle>`, `<time>`, `<percentage>`, `<number>`, `<integer>`, and `<color-function>` values.

---

### 31. **What are inline styles?**

These are styles that are written directly in HTML, and they have the highest priority (excluding `!important`).

---

### 32. **What is !important and how do you feel about it?**

The `!important` declaration is used to give a style rule the highest priority, overriding any other rules that conflict with it. When applied to a CSS property, `!important` ensures that the specified value will be used, regardless of specificity or order of other rules.

---

### 33. **What is the difference between border and outline?**

- `outline` does not affect the position of the element or its dimensions
- `outline` does not allow setting a border on a specific side of the element (only on all sides at once)
- `outline` does not apply corner rounding set by the `border-radius` property

---

### 34. **What do you know about responsive web design?**

Responsive web design allows websites to adapt and respond to various screen sizes and devices. It involves creating flexible layouts, using grids, and employing media queries to ensure optimal viewing experiences across different devices and resolutions.

---

### 35. **What is meant by RGB stream?**

RGB represents colors in CSS. The three streams are Red, Green, and Blue. The intensity of colors is represented using numbers from 0 to 256, allowing CSS to display a wide spectrum of visible colors.

---

### 36. **What is BEM (Block Element Modifier)?**

BEM (Block, Element, Modifier) is a component-based approach to web development. It is based on the principle of dividing the interface into independent blocks. It allows for easy and fast development of interfaces of any complexity and reusing existing code, avoiding "copy-paste".

![bem](/docs/css_bem_structure.png)

---

### 37. **Explain a few advantages of CSS.**

With CSS, different documents can be controlled using a single site, styles can be grouped in complex situations using selectors and grouping methods, and multiple HTML elements can have classes.

---

### 38. **How can you use CSS to control image repetition?**

The `background-repeat: none` property is used to control the image.

---

### 39. **What is the purpose of the overflow property and when should it be used?**

The CSS property `overflow` determines whether the content of an overflowing block element should be clipped, provide scroll bars, or simply be displayed.

---

### 40. **How to create a custom checkbox?**

Before the checkbox, a label is created and attached to the input. Then the input is hidden, and the label is styled as needed.

---

### 41. **What are vh and vw units?**

`vh` and `vw` are relative units and represent:

- `vh` - 1% of the browser window's height
- `vw` - 1% of the browser window's width

---

### 42. **How to change the appearance of a cursor?**

The CSS property `cursor` is used to change the appearance of the cursor.

---

### 43. **What determines the size of an element?**

The size of an element is constructed from the width and height of its content, inner padding, border, and outer margin.

![element_size](/docs/css_element_size.png)

---

### 44. **How to position one element relative to another?**

To control the positioning of a child element, set the `position` property to `relative` and use `top`, `right`, `bottom`, and `left` to adjust its placement.

---

### 45. **How to remove the bullet point from a list?**

Set the property `list-style-type: none` for the corresponding list element.

---

### 46. **Which CSS styles are most performance-heavy for browsers?**

A large number of connected fonts, shadows, animations, and transparency.

---

### 47. **How do you select elements with a specific attribute in CSS?**

Use attribute selectors like:

```css
a[type="text"] {
  color: red;
}
```

---

### 48. **What is the aspect-ratio property in CSS?**

It sets a preferred width-to-height ratio for an element.

---

### 49. **Can you explain the concept of CSS specificity hierarchy?**

It determines which styles apply based on the selector's specificity:

- inline styles > IDs > classes > elements.

---

### 50. **Explain how to style checkboxes and radio buttons using CSS.**

Hide the default input and style a custom element or label.

---

### 51. **What is the purpose of the line-height property in CSS?**

It sets the space between lines of text.

---

### 52. **Explain what elements will match each of the following CSS selectors:**

- `div, p` - selects all `<div>` elements and all `<p>` elements.
- `div p` - selects all `<p>` elements that are anywhere inside a `<div>` element.
- `div > p` - selects all `<p>` elements where the immediate parent is a `<div>` element.
- `div + p` - selects all `<p>` elements that are placed immediately after a `<div>` element.
- `div ~ p` - selects all `<p>` elements that are anywhere preceded by a `<div>` element.

---
