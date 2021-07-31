---
Title: "font"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Fonts"
  - "Typography"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition 

Shorthand property that sets different properties for an elements font in a single decleration.

## Syntax

```css
font: <values>; 
```

The `font` property can have the following properties as values:

*Required Values*
- font-family
- font-size

*Optional Values*
- line-height
- font-weight
- font-stretch
- font-style
- font-varient


**Note:** `font-style`, `font-variant`, and `font-weight` must come before `font-size`.
**Note:** `line-height` must be declared after `font-size` and only following a forward slash.  

## Example 1

Setting an `h1` elements font to `Georgia italic`, size of `10px`, and line height of `40px` in a single declaration.

```css
h1 {
  font: italic 10px/40px Georgia, sans-serif; 
}
```

The above would be the same as:

```css
h1 {
  font-style: italic;
  font-size: 10px;
  line-height: 40px;
  font-family: Georgia, sans-serif; 
}
```

## Example 2

Setting an `h2` font with all seven properties in one decleration.

```css
h2 {
  font: expanded italic small-caps bolder 20px/30px cursive;  
}
```
