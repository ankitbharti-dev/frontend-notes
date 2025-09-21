# HTML Basics

HTML stands for **HyperText Markup Language**.  
It is a technology developed by **Tim Berners-Lee** and is used to provide the **basic structure of a web page**.  
HTML uses **tags** to define elements and content that browsers can render.

---

## Tags

- A tag in HTML is like a label that tells the browser what something is and how it should be displayed.
- Tags are written inside **angle brackets `< >`**.  
- Anything written inside these brackets is treated as a **tag** by the browser.  
- Tags define **elements** such as headings, paragraphs, links, images, and more.  

**Example:**  
```html
<head></head>
<body></body>
```
### Types of Tags
There are two types of tags
1. Paired Tags
    - Require both an opening <tag> and a closing </tag>.
    - The closing tag always has a /.
    - Content is written between the tags.
    - Example: <p>This is a paragraph.</p>.
2. Self-closing Tags 
    - Do not need a separate closing tag.
    - Usually used for elements that don’t wrap content.
    - Examples: `<img />`, `<br />`, `<hr />`, `<input />`.

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

## Emmet

- Emmet is a **built-in functionality** in code editors that allows you to write code using **short abbreviations**.  
- After typing an abbreviation, the editor **expands it into full code** by pressing `Tab` or `Enter`.  
- **Supported languages:** HTML, CSS, JSX, etc.  
- **Example:**  
  - Typing `ul>li*3` in HTML and pressing `Tab` will generate:
    ```html
    <ul>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    ```
- **Tip:** Most modern editors like VSCode, Sublime Text, and Atom support Emmet by default.

## Basic Syntax for HTML Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

### Explanation of Each Part

```html
<!DOCTYPE html>
```
- This is the document type declaration.
- It tells the browser that this is an HTML5 document.

```html
<html lang="en">
```
- This is the root tag of an HTML file.
- Only one <html> tag is recommended per file; multiple tags are invalid and may cause page break.
- The lang attribute specifies the language of the document (en = English).

```html
<head></head>
```
- The head tag contains metadata and resources for the web page, such as:
    - Page <title> : Specifies the title of the web page displayed in the browser tab.
    - Meta tags (<meta>) : Provide information about the page, such as character encoding, viewport settings, and author.
- Links to CSS or JavaScript files
- Content inside <head> is not displayed on the screen but helps the browser understand the page.
- This is recommended to use one head tag per file.

```html
<body></body>
```
- The body tag contains all the main content of the web page.
- Anything written inside <body> is visible on the screen.
- There tow meta data added by emmet in vs cdoe and title.
- It is recommend to use single body tag per file.

### Meta Tags Added by Emmet (VS Code)

```html
<meta charset="UTF-8">
```
- Specifies the character encoding of the page.
- UTF-8 supports almost all characters worldwide.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
- Makes the page responsive.
- Sets the width of the page to match the device width.
- initial-scale=1.0 sets the initial zoom level.

```html
<title>Document</title>
```
- Sets the title of the web page.
- Displayed on the browser tab or window title bar.
