---
Title: "colspan"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Tables"
  - "Elements"
  - "Web Development"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition 

Defines the number of columns a cell should span. 

## Syntax
```html
<table>
  <tr>
    <th>Devs</th>
    <th>Name</th>
  </tr>
  <tr>
    <td>Dev 1</td>
    <td>Sonny</td>
  </tr>
  <tr>
    <td>Dev 2 </td>
    <td>Nomnom</td>
  </tr>
  <tr>
    <td colspan="2"><!-- Takes up two rows--></td>
  </tr>
</table>
```
| Devs | Name |
| :------: | :------: | 
| Dev 1  | Sonny   | 
| Dev 2   | Nomnom   |
| :------:           |


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