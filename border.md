---
Title: "border"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Borders"
  - "Box Model"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition 

Shorthand property that sets different properties for an elements border in a single decleration.

## Syntax

```css
border: <values>; 
```

The `border` property accepts one or more of the following properties as values:

- border-style(*required*)
- border-color
- border-width
 
## Example 1

Setting a `div` elements border style to dashed.

```css
div {
  /*<border-style>*/  
  border: dashed; 
}
```

## Example 2

Setting an `img` elements border to dotted, red and a width of 20px.

```css
div {
  /*<border-width> | <border-style> | <border-color>*/
  border: 20px dotted red; 
}
```