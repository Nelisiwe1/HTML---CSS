# Introduction to HTML

## 1. What is HTML?

HTML stands for Hypertext Markup Language, and it uses a collection of elements to structure content on a web page and is designed to be displayed in a web browser. Each HTML element is represented by a tag, enclosed in angle brackets (< >). It allows us to structure our content and bridge the gap between human and computer languages.

The web consists of three different languages which are HTML, CSS, and JavaScript.
HTML is used for marking up the content of the website. The beauty of HTML lies in its simplicity, which gives it resilience and robustness.
CSS, short for Cascading Style Sheets, is used for styling the web page, responsible for color, fonts, and size.
JavaScript works behind the scenes, making it work smoothly for the users. It is like the superhero of programming languages.

## Formatting and Styling:

HTML provides various elements for formatting content. Some common ones are:

- Headings: `<h1>` to `<h6>` for different heading levels.
- Paragraph: `<p>` for paragraphs.
- Bold and Italic: `<strong>` for strong/bold text, and `<em>` for emphasized/italic text.
- Line Break: `<br>` for line breaks.
- Horizontal Line: `<hr>` for horizontal lines.
- Lists: `<ul>` for unordered lists and `<ol>` for ordered lists.

To add more styling and layout, you can use CSS (Cascading Style Sheets) either internally within the `<head>` or externally by linking to a CSS file.

## Text Formatting:

HTML documents are basically a bunch of nested elements nested within each other, creating tree structures like a family tree with parents and children. The browser pays attention to this structure and builds a big family tree showing how everything is related.

Document Object Interface (DOM) is a programming interface that represents the content of the HTML document as a tree structure. The DOM tree becomes important when you are working with CSS or JavaScript, or when your developers are.

## Headlines:

Headlines serve the purpose of dividing the content into smaller, more digestible chunks. The HTML elements used for marking up headlines come in six distinct types: h1, h2, h3, h4, h5, and h6. When viewed in a browser, each headline has a distinct visual effect. The h1 element is the largest and most prominent, while h6 is the smallest and least attention-grabbing. The choice of the headline level is not based on appearance but on its meaning. It makes sense to use h1 for the main title and h2 for the subheading right after the title.

## Bold and Italic:

In HTML, we have two different elements to convey this distinction. We use the `<i>` element to apply visual italics and the `<em>` element to add emphasis. It may seem like they look exactly the same visually, but they serve different purposes.

There are two elements to emphasize or make something bold in HTML. The first one is the `<strong>` element, which is used to show importance, seriousness, or urgency. It is like saying, "Hey, this needs to stand out!" This element adds meaning to the text. On the other hand, the `<b>` element is more generic and neutral. It does not carry any specific meaning; it simply allows us to make something bold visually and does not imply any alternative voice or mood.

To summarize, there are four elements in HTML that allow us to mark text as bold or italicized. Two of them, `<em>` and `<strong>`, convey meaning and serve a language-related purpose. The other two, `<i>` and `<b>`, do not carry any specific meaning and are used solely for visual styling.

## HTML Lists:

### Unordered List:

The `<li>` element represents the list items.
The `<ul>` element stands for unordered list.
`<ul>` is not used for appearance but for it to be readable, CSS is responsible for the appearances.

### Ordered List:

`<ol>` stands for ordered list, indicating that there is a specific order to the items on the list.
`<li>` lists the items.

### Definition List:

A definition list is used to create a list of terms and their corresponding definitions. It consists of `<dt>` (term) and `<dd>` (definition) elements within the `<dl>` element.

Here is an example:
```html
<dl>
  <dt>HTML</dt>
  <dd>Hypertext Markup Language - the standard markup language for creating web pages and web applications.</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets - a style sheet language used for describing the presentation of a document written in HTML.</dd>
</dl>
```

## HTML Quotes:

In HTML, you can include quotations or quoted content in your web page using the `<blockquote>` and `<q>` elements. These elements help provide semantic meaning to the quoted content and allow you to style the quotes appropriately.

### Blockquote (`<blockquote>`):

The `<blockquote>` element is used for longer quotes or block-level quotations. It typically represents content quoted from an external source or a longer portion of text that requires indentation. Here's an example:
```html
<blockquote>
  <p>This is a blockquote example. It represents a longer quotation from an external source or a significant portion of text.</p>
  <cite>- Source Name</cite>
</blockquote>
```
The `<cite>` element is used to indicate the source of the quote. Browsers usually italicize the content inside the `<cite>` element.

### Quote (`<q>`):

The `<q>` element is used for shorter, inline quotations within a paragraph. It is intended for brief quotes that are part of the surrounding text. Here's an example:
```html
<p>She said, <q>I'll be there soon.</q></p>
```

## Date and Time:

To format a specific moment or range in time in a way that computers can understand, we use the `<time>` element. It consists of an opening tag (`<time>`) and a closing tag (`</time>`).

The time format within the datetime attribute must be specific. Dates and times have a special format that machines can understand, and we need to use that format. We write it like this: `<time datetime="2025-05-08">May 8, 2025</time>`. The machine-readable version prefers numbers in the 24-hour clock format, and we can choose whether to include seconds and fractions of a second or not.

## HTML Code, `<pre>` and `<br>`

In HTML, the `<pre>` and `<br>` elements are used to control whitespace and line breaks within text content.

### `<pre>` Element:

The `<pre>` element stands for "preformatted text." It is used to display text exactly as it appears in the HTML code, preserving all spaces, line breaks, and formatting. It is often used for displaying code snippets, ASCII art, or any text that requires precise formatting.

Here is an example:
```html
<pre>
    This is an example
    of preformatted text.
 
    It keeps spaces,
    line breaks,
    and    indentation.
</pre>
```

### `<br>` Element:

The `<br>` element stands for "line break." It is a self-closing tag used to insert a line break within a block of text. Unlike other HTML elements

Code element:
•	Code element highlight the code and make it look like an actual code.
•	It is treated as an inline element, meaning it remains part of the element it is in.
•	HTML entity is another way of showcasing the code.
•	&it; h4&gt; is an example of HTML entity.
