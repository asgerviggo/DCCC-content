---
title: "Markdown testpage"
footnotes: "References"
---

## 1. Headings

# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6


## 2. Text Formatting

**Bold Text**

*Italic Text*

***Bold and Italic Text***

~~Strikethrough Text~~

<u>Underlined Text</u> <!-- Note: Some renderers may not support underline -->

[This is a span text.]

## 3. Lists

### Unordered List

- Item One
- Item Two
  - Subitem Two Point One
  - Subitem Two Point Two
- Item Three

### Ordered List

1. First Item
2. Second Item
   1. Subitem Two Point One
   2. Subitem Two Point Two
3. Third Item

### Task List

- [x] Complete Task One
- [ ] Complete Task Two
- [ ] Complete Task Three


## 4. Links and Images

### Links

This is an [example link](https://www.example.com).

### Images

![Example Image](/dccc.jpg)


## 5. Code

### Inline Code

Here is an example of `print("Hello, World!")`.

### Code Blocks

```python
def greet():
    print("Hello, World!")

greet()
```

```javascript
function greet() {
    console.log("Hello, World!");
}

greet();
```


## 6. Blockquotes

> This is a blockquote.
>
> It can span multiple lines.


## 7. Tables

| Name  | Age |
| ----- | --- |
| Alice | 25  |
| Bob   | 30  |
| Carol | 22  |

| Product | Price | Stock |
| ------- | ----- | ----- |
| Apple   | $1    | 100   |
| Banana  | $0.5  | 200   |
| Grape   | $2    | 150   |



## 10. Horizontal Rules

***

---

___


## 11. Others

### Text Alignment

Some renderers support text alignment:

:div[Right Aligned]{.align-right} 

### Footnotes

This is a footnote example.[^1]
This is a named footnote example.[^footnote]

[^1]: This is the content of the footnote.
[^footnote]: This is the content of the named footnote.

### Emoji

This is a smiley emoji 😊.

### Shortcodes

- \:smile:
- \:heart:
- \:rocket:
