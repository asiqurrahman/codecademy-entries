---
Title: "clear"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Clear"
  - "Float"
  - "Layout"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition 

The `clear` property species whether an element coming after a floated element should be moved down or not.

## Syntax

```css
clear: <value>;
```

The following values can be be appplied to the `clear` property: 

- `none`: Default. The element is not moved down to clear past floating elements
- `left`: The element is moved down to clear past *left* floated elements. 
- `right`: The element is moved down to clear past *right* floated elements.
- `both`: The element is moved down to clear past both *left* and *right* floated elements.


## Example 1

Making an `img` element move down a *left* floated `h1` element.

```css
.div1 h1 {
  float: left;
}

.div1 img {
  clear: left; 
}
```