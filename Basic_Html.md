# Structure of a HTML Document

All Html Document must start with a **document type declaration** : `<!DOCUMENT html>`
The Html document itself begins with the `<html>` and ends with `</html>`
The visible part of the Html is between `<body>` and `</body>`

## Example of a Basic HTML Document 

```html
<!DOCTYPE html>
<html>
<head>
<title> Example Document</title>
</head>
<body>
<h1>Example Document</h1>

</body>
</html>
```

# Html Element

An Html Element is defined by a start tag, some content and an end tag.

`<tagname>` content `</tagname>`

 # Important HTML Elements

---

## 1. Structural Elements
- **`<html>`**: The root element of an HTML document.
  `<html>` element is the root element of an Html Document, it represent the top level container for all the html elements and content in the document.
- **`<head>`**: Contains metadata, links, and scripts.
- **`<body>`**: Contains the visible content of the webpage.
- **`<title>`**: Specifies the title of the webpage.
- **`<main>`**: Represents the main content of the document.
- **`<header>`**: Defines a header section for the document or a section.
- **`<footer>`**: Defines a footer section for the document or a section.
- **`<section>`**: Represents a thematic grouping of content.
- **`<article>`**: Represents a standalone piece of content.
- **`<nav>`**: Defines navigation links.
- **`<aside>`**: Represents content related to the main content, such as a sidebar.

---

## 2. Text Content
- **`<h1>` to `<h6>`**: Headings, `<h1>` being the largest.
- **`<p>`**: Defines a paragraph.
- **`<br>`**: Inserts a line break.
- **`<hr>`**: Defines a horizontal rule.
- **`<blockquote>`**: Represents a block of quoted text.
- **`<pre>`**: Displays preformatted text.
- **`<span>`**: Used for inline grouping and styling.
- **`<strong>`**: Represents strong importance (bold text).
- **`<em>`**: Represents emphasized text (italicized).
- **`<mark>`**: Highlights text.
- **`<small>`**: Represents small or fine print.
- **`<b>`**: Bold text (without importance).
- **`<i>`**: Italic text (without emphasis).

---

## 3. List Elements
- **`<ul>`**: Unordered list.
- **`<ol>`**: Ordered list.
- **`<li>`**: List item.
- **`<dl>`**: Definition list.
- **`<dt>`**: Definition term.
- **`<dd>`**: Definition description.

---

## 4. Link and Media Elements
- **`<a>`**: Hyperlink.
- **`<img>`**: Embeds an image.
- **`<figure>`**: Groups an image and a caption.
- **`<figcaption>`**: Provides a caption for a `<figure>`.
- **`<audio>`**: Embeds audio content.
- **`<video>`**: Embeds video content.
- **`<source>`**: Specifies media sources (used with `<video>` and `<audio>`).
- **`<iframe>`**: Embeds another webpage.

---

## 5. Table Elements
- **`<table>`**: Creates a table.
- **`<tr>`**: Defines a table row.
- **`<td>`**: Defines a table cell.
- **`<th>`**: Defines a table header cell.
- **`<thead>`**: Groups table header content.
- **`<tbody>`**: Groups table body content.
- **`<tfoot>`**: Groups table footer content.
- **`<caption>`**: Provides a title for the table.

---

## 6. Form Elements
- **`<form>`**: Creates an interactive form.
- **`<input>`**: Defines input fields.
- **`<label>`**: Associates labels with form controls.
- **`<textarea>`**: Defines a multiline text input.
- **`<select>`**: Creates a dropdown list.
- **`<option>`**: Defines options within a dropdown.
- **`<button>`**: Represents a clickable button.
- **`<fieldset>`**: Groups related elements in a form.
- **`<legend>`**: Provides a title for a `<fieldset>`.

---

## 7. Metadata and Scripting
- **`<meta>`**: Provides metadata about the document.
- **`<link>`**: Links external resources like CSS.
- **`<style>`**: Embeds internal CSS.
- **`<script>`**: Embeds or links to JavaScript.
- **`<noscript>`**: Provides content when JavaScript is disabled.

---

## 8. Semantic Elements
- **`<div>`**: A block-level container (generic).
- **`<span>`**: An inline container (generic).
- **`<code>`**: Represents code snippets.
- **`<kbd>`**: Represents user keyboard input.
- **`<samp>`**: Represents sample output.

---

## 9. Interactive Elements
- **`<details>`**: Creates a collapsible disclosure widget.
- **`<summary>`**: Defines a summary for `<details>`.
- **`<dialog>`**: Represents a dialog box or interactive component.

---

## 10. Accessibility and SEO Elements
- **`<alt>`**: Provides alternative text for images.
- **`<aria-*>`**: Attributes for accessibility.
- **`<title>`**: Describes the document or individual elements.

# Html Attributes

Html Attributes provides additional information about the html element, all html element can have attributes.
Attributes are always specified in the Start tag and they are usually come with key value pairs 

## Example 

```html

<a href="https://example.com"> Example Website Link </a>
<img src="img.jpg" width="400" height="400" alt="example image">

```
 in the `<a>` ttag href is an attribute similarly in the `<img>` tag src, width, height and alt all are attributes

