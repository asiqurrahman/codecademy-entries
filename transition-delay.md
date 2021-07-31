---
Title: "transition-delay"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Transitions"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition 

Specifies how long an element should wait before beginning a transition. 

## Syntax

```css
transition-delay: <value>;
```

The `transition-delay` value can be specified by one of the folllowing:
- Seconds: `2s`
- Milliseconds: `125ms`

**Note**: We can give a comma-separated list of values to set different delays for properties of the same element. The delay of all properties of the element will be the same if a single value is provided. 

## Example 1

Setting a `h1` element to wait `3.5` seconds before beginning a transition.

```css
h1 {
  transition-delay: 3.5s; 
}
```

## Example 2

Setting a `div` elements left margin transition to wait `200` milliseconds and width transition to wait `1` second before transitioning.

```css
div {
  transition-delay: 200ms, 1s;
  transition-property: margin-left, width; 
}
```