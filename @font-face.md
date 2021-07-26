---
Title: "text-transform"
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

Specifies how to capitalize an element's text. 

## Syntax

```css
text-overflow: <value>;
```

The following values can be be appplied to the `text-transform` property:

- `none`: Default. The text renders as is.

- `capitalize`: Transforms the first character of every word to uppercase. 

- `uppercase`: Transforms all characters to uppercase.

- `lowercase`: Transforms all characters to lowercase.

## Example 1

Tranforming every character of a text block to uppercase.

```css
p {
  text-transform: uppercase; 
}
```