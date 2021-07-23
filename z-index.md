---
Title: "z-index"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Positioning"
  - "Layers"
  - "Layout"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition 

The `z-index` property sets the stack order of an element.

## Syntax

```css
z-index: <value>;
```
The `z-index` value can be specified with a positive or negative integer. An element with a larger `z-index` value will be higher on the stack then an element with a lower `z-index` value. Unless specified, the default value of an element on the stack is 0.

**Note:** The `z-index` property does not work with an element that has a `position` value of `static`.  


## Example 1

In the following example, we have a grey box and a black box. We can set the grey box above the black box by giving the grey box a higher `z-index` value. 

```css
.greybox {
  z-index: 2; 
}

.blackbox {
  z-index: 1; 
}
```
![grey box above black box](z-index.png)

## Example 2

If we wanted to have the black box above the grey box we can simply give the black box a higher `z-index` value.

```css
.greybox {
  z-index: 2; 
}

.blackbox {
  z-index: 3; 
}
```
![black box above grey box](z-index-2.png)