# HTML Basics

HTML stands for **HyperText Markup Language**.  
It is a technology developed by **Tim Berners-Lee** and is used to provide the **basic structure of a web page**.  
HTML uses **tags** to define elements and content that browsers can render.

---

## Tags

- Tags are written inside **angle brackets `< >`**.  
- Anything written inside these brackets is treated as a **tag** by the browser.  
- Tags define **elements** such as headings, paragraphs, links, images, and more.  

**Example:**  
```html
<head></head>
<body></body>
```

## Elements

- An element = opening tag + content + closing tag

**Example:**
```html
<p>This is a paragraph.</p>
```

### <p> → tag
- This is a paragraph. → content

## Attributes

- Attributes = extra information for tags
- Written in opening tag
- Tell browser how to behave or display the element

Example:

```html
<a href="https://example.com" target="_blank">Visit Example</a>
<img src="image.jpg" alt="Example Image">
```

***Common Attributes:***

href → Link URL
src → Image source
alt → Alternative text
id → Unique identifier
class → CSS styling
style → Inline CSS

## How HTML Works

- Browser reads HTML top to bottom
- Interprets tags + attributes
- Renders structure and content
- CSS + JS enhance design and interactivity