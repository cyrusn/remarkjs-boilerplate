[//]: # (slide Markdown for remark)

class: center middle bg-primary text-light

# RemarkJS - CSS Guide

---

# Features

- Bootstrap + Font Awesome
- Centered List
- Scaled Image
- Scrolling
- Blockquote
- Columnar Layout
- Footnote

---

# Bootstrap + Font Awesome

Bootstrap 4 and Font Awesome 5 are available in slides.  

<button type="button" class="btn btn-primary">Bootstrap Button</button>
<i class="fab fa-font-awesome-flag"></i> <i class="far fa-kiss-wink-heart"></i>

---

# Centered List

.blockquote-info[
> ### Guide
> Use `.fit-content.mx-auto` to create a centered list
]

.center[
# Example
.fit-content.mx-auto[
- apple
- orange
- pear
]
]

---

class: center

# This is a normal image

But the image is too .text-danger[**big**]
![image][@1]

---

class: center

# `img-100` class to set max width to 100%

.img-100[![image][@1]]

---

class: center

# `img-75` class to set max width to 75%

.img-75[![image][@1]]

---

# Also available ...

- `img-50`
- `img-25`

---

class: center

# `scroll` to enable scrolling for long content

Use together with `.img-100` and `h-75` to produce a nice overflowed image

.img-100.h-75.scroll[
![image][@1]
]

---

# Blockquote

.blockquote-primary[
> ### blockquote
> This is primary blockquote's content.
]

## Syntax

```md
.blockquote-primary[
> #### blockquote
> This is primary blockquote's content.
]
```

Available styles:  
`primary`, `secondary`, `success`, `info`, `warning`, `danger`, `light`, `dark`

---

# Two Columns Layout

Use Bootstrap's `.row`, `.col` to create columnar layout

.row[
.col-6[
- This is column 1
  + apple
  + orange
]

.col-6[
- This is column 2
  + alpha
  + beta
  + see syntax on next slide
]
]

---

# Syntax

```md
.row[
.col-6[
- This is column 1
  + apple
  + orange
]

.col-6[
- This is column 2
  + alpha
  + beta
]
]
```
---

class: row

.col-3.bg-light.sidebar[
### Sidebar
- alpha
- beta
]

.col-9[
## Slide with sidebar 1

Note the last sidebar item will be ***bold italic***
]

---

class: row

.col-3.bg-light.sidebar[
### Sidebar
- alpha
- beta
- gamma
]

.col-9[
## Slide with sidebar 2

See syntax on next slide
]

---

class: row

.col-3.bg-light.sidebar[
### Sidebar
- alpha
- beta
- gamma
]

.col-9[
## Syntax

```md
class: row

.col-3.bg-light.sidebar[
### Sidebar
- alpha
- beta
- gamma
]

.col-9[
// This syntax block
...
]
```
]

---

# Footnote

This is an example.sup[1] of footnotes.sup[2], link to Google.sup[3]
.footnote[
1. Hello! World.
2. Footnoting is fun
3. https://google.com
]

## Syntax
``` md
This is an example.sup[1] of footnotes.sup[2], link to Google.sup[3]
.footnote[
1. Hello! World.
2. Footnoting is fun
3. https://google.com
]
```
 
---
class: center middle bg-info text-light

# .text-danger[♥] Thanks .text-danger[♥]

<!-- reference links -->

[@1]: ./static/1600x1000.jpg
[@2]: ./static/1600x1000.jpg
[@3]: ./static/1600x1000.jpg
[@4]: ./static/1600x1000.jpg
