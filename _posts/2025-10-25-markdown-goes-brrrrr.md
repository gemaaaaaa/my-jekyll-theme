---
layout: post
title: "Markdown Goes Brrrrr"
date: 2025-10-25 00:00:01 +0700
excerpt: "A comprehensive showcase of markdown syntax including headings, text formatting, lists, code blocks, tables, and advanced features."
---

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6


---

## Paragraphs and Line Breaks

This is a paragraph with multiple sentences. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

This is another paragraph separated by a blank line.

This line ends with two spaces for a hard break.  
This line appears on a new line.


---

## Text Formatting

**Bold text** or __bold text__

*Italic text* or _italic text_

***Bold and italic*** or ___bold and italic___

~~Strikethrough text~~

`Inline code` with backticks


---

## Lists

### Unordered List

- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
    - Deeply nested item 2.2.1
- Item 3

* Alternative bullet
* Another item


### Ordered List

1. First item
2. Second item
   1. Nested item 2.1
   2. Nested item 2.2
3. Third item


### Task List

- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task


---

## Links

[Link text](https://example.com)

[Link with title](https://example.com "Link Title")

<https://example.com>

[Reference-style link][reference]

[reference]: https://example.com "Reference Link"


---

## Images

![Alt text](https://placehold.co/150)

![Alt text with title](https://placehold.co/150 "Image Title")


---

## Blockquotes

> This is a blockquote.
> It can span multiple lines.

> Blockquotes can be nested
>> Like this
>>> And even deeper

> **Blockquotes** can contain *other* `markdown` elements.


---

## Code Blocks

### Inline Code

Use `console.log()` to print in JavaScript.


### Fenced Code Blocks

```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}

greet("World");
```

```python
def factorial(n):
    if n <= 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))
```

```ruby
def fibonacci(n)
  return n if n <= 1
  fibonacci(n - 1) + fibonacci(n - 2)
end

puts fibonacci(10)
```

```html
<!DOCTYPE html>
<html>
<head>
    <title>Test Page</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```

```css
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
}
```

```bash
#!/bin/bash
echo "Hello from bash"
ls -la
cd /home/user
```


### Indented Code Block

    This is an indented code block
    Created with 4 spaces
    No syntax highlighting


---

## Horizontal Rules

---

***

___


---

## Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |


### Aligned Tables

| Left Aligned | Center Aligned | Right Aligned |
|:-------------|:--------------:|--------------:|
| Left         | Center         | Right         |
| Text         | Text           | Text          |


---

## Footnotes

Here's a sentence with a footnote[^1].

Another sentence with a footnote[^2].

[^1]: This is the first footnote.
[^2]: This is the second footnote with more details.


---

## Definition Lists

Term 1
: Definition 1

Term 2
: Definition 2a
: Definition 2b


---

## Abbreviations

The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium


---

## Escaping Characters

\*Not italic\*

\**Not bold\**

\# Not a heading

\[Not a link\](https://example.com)


---

## HTML Elements

<div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px;">
    This is raw HTML inside markdown.
</div>

<details>
<summary>Click to expand</summary>

This content is hidden by default.

</details>

<kbd>Ctrl</kbd> + <kbd>C</kbd>

<mark>Highlighted text</mark>

<sup>Superscript</sup> and <sub>subscript</sub>


---

## Emojis

:smile: :heart: :thumbsup: :rocket: :fire:

😀 😃 😄 😁 🚀 ❤️ 👍


---

## Special Characters

Copyright: &copy;  
Registered: &reg;  
Trademark: &trade;  
Less than: &lt;  
Greater than: &gt;  
Ampersand: &amp;


---

## Math (if supported)

Inline math: $E = mc^2$

Block math:

$$
\int_{0}^{\infty} e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$


---

## Combination Examples

### Code with Description

Here's how to create a function in Python:

```python
def calculate_sum(a, b):
    """
    Calculate the sum of two numbers.
    
    Args:
        a (int): First number
        b (int): Second number
    
    Returns:
        int: Sum of a and b
    """
    return a + b

result = calculate_sum(5, 3)
print(f"Result: {result}")
```


### Blockquote with Code

> **Note:** Always validate user input
> ```javascript
> const sanitize = (input) => {
>     return input.trim().replace(/[<>]/g, '');
> };
> ```


### List with Code

1. Install dependencies:
   ```bash
   npm install
   ```
2. Run the development server:
   ```bash
   npm run dev
   ```
3. Build for production:
   ```bash
   npm run build
   ```


---

## Conclusion

This document tests all major markdown elements including headings, text formatting, lists, links, images, code blocks, tables, and more. Use this to verify your markdown rendering functionality.