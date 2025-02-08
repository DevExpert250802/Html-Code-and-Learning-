# HTML Basics

## What is HTML?
HTML (Hypertext Markup Language) is a language used for defining the structure and labeling of a webpage.

## Additional Technologies
- **CSS**: Used for styling and appearance.
- **JavaScript (JS)**: Used for defining logic and functionality in a webpage.

## Boilerplate Code
To quickly generate an HTML boilerplate in VS Code, type `!` and press `ENTER`.

```html
<!DOCTYPE html> <!-- HTML5 -->
<html lang="en"> <!-- Root element -->
<head> <!-- Meta data, title, linking JS/CSS files -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body> <!-- Structure and content of the webpage -->
    
</body>
</html>
```

## Comments in HTML
Use `CTRL + /` to add comments in HTML:
```html
<!-- This is a comment -->
```

## Common HTML Tags
### Basic Structure
| Tag | Description |
|------|------------|
| `<!DOCTYPE>` | Defines the document type |
| `<html>` | Defines an HTML document |
| `<head>` | Contains metadata about the document |
| `<title>` | Defines a title for the document |
| `<body>` | Defines the document's body |

### Headings and Text Formatting
| Tag | Description |
|------|------------|
| `<h1>` to `<h6>` | Defines headings |
| `<p>` | Defines a paragraph |
| `<b>` | Defines bold text |
| `<i>` | Defines italicized text |
| `<u>` | Defines underlined text |
| `<strong>` | Defines important text |
| `<em>` | Defines emphasized text |
| `<mark>` | Highlights text |
| `<small>` | Defines smaller text |

### Lists
| Tag | Description |
|------|------------|
| `<ul>` | Defines an unordered list |
| `<ol>` | Defines an ordered list |
| `<li>` | Defines a list item |
| `<dl>` | Defines a description list |
| `<dt>` | Defines a term/name in a description list |
| `<dd>` | Defines a description of a term |

### Links and Navigation
| Tag | Description |
|------|------------|
| `<a>` | Defines a hyperlink |
| `<nav>` | Defines navigation links |

### Images and Media
| Tag | Description |
|------|------------|
| `<img>` | Defines an image |
| `<video>` | Embeds a video |
| `<audio>` | Embeds audio content |

### Tables
| Tag | Description |
|------|------------|
| `<table>` | Defines a table |
| `<tr>` | Defines a row in a table |
| `<th>` | Defines a header cell |
| `<td>` | Defines a cell in a table |

### Forms and Inputs
| Tag | Description |
|------|------------|
| `<form>` | Defines an HTML form |
| `<input>` | Defines an input control |
| `<button>` | Defines a clickable button |
| `<select>` | Defines a drop-down list |
| `<textarea>` | Defines a multi-line text input |

### Semantic Elements
| Tag | Description |
|------|------------|
| `<header>` | Defines a header section |
| `<footer>` | Defines a footer section |
| `<section>` | Defines a section in a document |
| `<article>` | Defines an independent article |
| `<aside>` | Defines sidebar content |
| `<main>` | Defines the main content |

### Empty Elements (Self-closing)
Some HTML elements have no closing tag:
```html
<img />
<br />
<hr />
<input />
<meta />
<link />
```

## Conclusion
HTML provides the fundamental structure of a webpage, with CSS handling design and JavaScript adding interactivity. Mastering these elements is key to effective web development.

