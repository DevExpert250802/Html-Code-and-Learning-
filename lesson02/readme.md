# HTML README

## Opening Tag, Content, and Closing Tag
An HTML element consists of:
- **Opening tag**
- **Content**
- **Closing tag**

Example:
```html
<html> ... </html>
```

## What is a Tag?
A **tag** is a markup entity used to:
- Provide **structure** to content
- Provide **meaning/semantics** to content (e.g., headings, paragraphs)
- **Format** content (e.g., underline, bold text)

## Semantic Tags
Semantic tags provide meaningful structure to web content.
Examples:
```html
<h1> to <h6>, <p>, <a>, <ul>, <ol>, <li>
<table>, <th>, <tr>, <td>
<img>, <form>, <input>
```

## Structure Tags
These tags define the main layout and sections of a webpage:
```html
<html>, <head>, <body>, <main>, <header>, <aside>, <footer>, <article>, <section>, <nav>
```

## Formatting Tags
Used for styling text:
```html
<b>, <u>, <i>, <strong>, <s>, <em>, <sup>, <sub>, <code>, <pre>
```

## Empty Elements
Some elements do not have a closing tag:
```html
<area>, <base>, <br>, <col>, <command>, <embed>, <hr>, <img>, <input>, <link>, <meta>
```

## HTML Shortcuts
### Ordered List with 3 Items:
Typing `ol>li*3` in Emmet expands to:
```html
<ol>
    <li></li>
    <li></li>
    <li></li>
</ol>
```

### Generate a Paragraph with Placeholder Text:
Typing `<p>lorem500</p>` generates a paragraph of 500 words.
```html
<p>Lorem ipsum dolor sit amet...</p>
```

