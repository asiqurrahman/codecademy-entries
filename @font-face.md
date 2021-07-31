---
Title: "@font-face"
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

Specifies a custom font to be used to display text. 

## Syntax

The `@font-face` rule allows us to use custom fonts instead of just "web-safe" fonts. We can give the font a name then point to the file in which the font is stored.

```css
@font-face {
  font-family: /*Font Name */;
  src: url(" ") /*Link To Font*/;
}
```

**Note:** The name of the file in which the font is stored, must end in a supported font format(e.g. *custom_font.woff2*, *custom_font.ttf*). 

## Example 1

Specifying a font called "uniqueFont" then linking the url to the font folder.

```css
@font-face {
  font-family: uniqueFont;
  src: url("unique_font.woff") 
}
```

## Example 2

Creating a custom font called "superFont" then applying the font to a `div`.

```css
@font-face {
  font-family: superFont;
  src: url("super_font.ttf") 
}

div {
  font-family: superFont;
}
```