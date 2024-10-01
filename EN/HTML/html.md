### 1. **What is HTML?**

HTML stands for HyperText Markup Language and is the language of the internet. It is the standard text formatting language used for creating and displaying pages on the Internet

HTML documents are made up of the elements and the tags that format it for proper display on pages.

HTML5 is the most recent and most advanced version of HTML. This includes animations, audio, images, and text, among many other things, and all without the need for additional software.

---

### 2. **What are HTML tags?**

We use HTML tags for placing the elements in the proper and appropriate format. Tags use the symbols `<`, and `>` to set them apart from the HTML content.

The HTML tags need not be closed always. **For example**: in the case of images, the closing tags are not required as `<img>` tag.

---

### 3. **What are attributes in HTML?**

Attributes are the properties that can be added to an HTML tag. These attributes change the way the tag behaves or is displayed. **For example:** a `<img>` tag has an `src` attribute, which you use to add the source from which the image should be displayed.

We add attributes right after the name of the HTML tag, inside the brackets. We can only add the attributes to opening or self-closing tags, but never be in closing tags.

---

### 4. **What is the `class` attribute in HTML?**

The `class` attribute is used to specify the class name for an HTML element. Multiple elements in HTML can have the same class value. Also, it is mainly used to associate the styles written in the stylesheet with the HTML elements.

---

### 5. **How do you separate a section of texts in HTML?**

We separate a section of texts in HTML using the below tags:

- `<br>` – it is used to separate the line of text. It breaks the current line and shifts the flow of the text to a new line.
- `<p>` – this tag is used to write a paragraph of text.
- `<blockquote>` – this tag is used to define large quoted sections.

---

### 6. **Define the list types in HTML?**

The list types in HTML are as below:

- Ordered list – the ordered list uses `<ol>` tag and displays elements in a numbered format.
- Unordered list – the unordered list uses `<ul>` tag and displays elements in a bulleted format.
- Definition list – the definition list uses `<dl>, <dt>, <dd>` tags and displays elements in definition form like in a dictionary.

---

### 7. **How do you align list elements in an HTML file?**

We can align the list elements in an HTML file by using indents. If you indent each nested list in further than the parent list, you can easily align and determine the various lists and the elements that it contains.

---

### 8. **The difference between an Ordered list and an Unordered list?**

An unordered list uses `<ul> </ul>` tags and each element of the list is written between `<li> </li>` tags. The list items are displayed as bullets rather than numbers.

An ordered list uses `<ol> </ol>` tags and each element of the list is written between `<li> </li>` tags. The list items are displayed as numbers rather than bullet points.

---

### 9. **What is an element in HTML?**

An element in HTML is a set of tags that define a specific part of a web page. It consists of a start tag, content, and an end tag.

---

### 10. **What is the difference between HTML and CSS?**

HTML is used to create the structure and content of a web page, while CSS is used to define the appearance and layout of the page.

---

### 11. **Are the HTML tags and elements the same thing?**

No, HTML tags are used to define the **structure** of a web page, while HTML elements are made up of a set of tags that define a **specific part** of a web page.

---

### 12. **What are void elements in HTML?**

Void elements in HTML are tags that do not require a closing tag. They are used to insert images, line breaks, and other content that does not require additional information. **For example:**

- `<area>`
- `base`
- `br`
- `col`
- `command`
- `embed`
- `hr`
- `img`
- `input`
- `keygen`
- `link`
- `meta`

---

### 13. **How do we insert a comment in HTML?**

We can insert a comment in HTML by beginning with a lesser than sign and ending with a greater than sign.

**For example:** `<!-- comment between -->`

---

### 14. **What is the advantage of collapsing white space?**

Collapsing white space in HTML can help to reduce the size of web pages and make them load faster. It involves removing unnecessary white space between HTML elements.

---

### 15. **What is white space in HTML?**

An empty sequence of space characters is called the white space in HTML. This white space is considered as a single space character in the HTML.

White space helps the browser to merge multiple spaces into one single space, and so taking care of indentation becomes easier. White space helps in better organizing the content and tags, making them readable and easy to understand.

---

### 16. **How do you create links to different sections within the same HTML web page?**

We use the `<a href="#">` tag, along with referencing through the use of the # symbol, to create several links to different sections within the same web page.

---

### 17. **What is semantic HTML?**

Semantic HTML is a coding style. It is the use of HTML markup to reinforce the semantics or meaning of the content.

**For example:** In semantic HTML `<b> </b>` tag is not used for bold statement as well as `<i> </i>` tag is not used for italic. Instead of these we use `<strong> </strong>` and `<em> </em>` tags.

---

### 18. **How do you add buttons in HTML?**

We can use the built-in `<button></button>` tag in HTML to add buttons to an HTML web page.

---

### 19. **What are the different types of headings in HTML?**

There are six types of heading tags in HTML which are defined with the `<h1>` to `<h6>` tags. Each type of heading tag displays a different text size from another. `<h1>` is the largest heading tag and `<h6>` is the smallest.

---

### 20. **What is the `alt` attribute in HTML?**

The alt attribute is used for displaying a text in place of an image whenever the image cannot be loaded due to any technical issue.

---

### 21. **How do you add color to the text in HTML?**

You can add color to the text in HTML by using the `style` attribute to the element and specify it's color.

**For example:** `<p style:"color: red;"> This text is red </p>`

---

### 22. **How do you add CSS styling in HTML?**

There are three ways to include the CSS with HTML:

1. Inline CSS - it is used when less amount of styling is needed or in cases where only a single element has to be styled. To use inline styles add the `style` attribute in the relevant tag.

![inline css](/docs/html_inline_style_sheet.png)

2. External Style Sheet - this is used when the style is applied to many elements or HTML pages. Each page must link to the style sheet using the `<link>` tag:

![external css](/docs/html_external_style_sheet.png)

3. Internal Style Sheet - it is used when a single HTML document has a unique style and several elements need to be styled to follow the format. Internal styles sheet is added in the head section of an HTML page, by using the `<style>` tag:

![internal css](/docs/html_internal_style_sheet.png)

---

### 23. **What hierarchy do the style sheets follow?**

If a single selector includes three different style definitions, the definition that is closest to the actual tag takes precedence. Inline style takes priority over embedded style sheets, which takes priority over external style sheets.

---

### 24. **What is meant by web storage in HTML5?**

Web storage refers to HTML5’s new storage features. Previous HTML versions relied on cookies for storage in the server, but web storage now means data can be stored locally within the user’s browser. Web storage also offers a larger storage limit and is more secure.

---

### 25. **What is the role of formatting tags in HTML5?**

Formatting tags allow text to be stylized in HTML5 without the need for CSS. There are a number of HTML5 formatting tags, and the most popular ones include:

- `<b>` - bold text
- `<strong>` - makes text bold but with strong importance
- `<i>` - italic text
- `<em>` - makes text italic but with added semantics importance
- `<mark>` - highlights text
- `<big>` - increases the font size of the text by one unit
- `<small>` - decreases the font size of the text by one unit
- `<del>` - displays as strike out text
- `<ins>` - displays as added text
- `<sub>` - makes the text a subscript
- `<sup>` - makes the text a superscript

---

### 26. **What are the different types of storage in HTML5?**

HTML5 supports two types of web storage. These are:

- `sessionStorage` - temporary storage available for the duration of the page session
- `localStorage` - permanent storage available until data is deleted by the user

---

### 27. **What is metadata in HTML5 and how is it specified?**

1. The `<meta>` tag defines metadata about an HTML document. Metadata is information about data.

2. `<meta>` tags always go inside the `<head>` element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

3. Metadata will not be displayed on the page, but is machine parsable.

4. Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.

---

### 28. **What is a `marquee` in HTML?**

Marquee is used for scrolling text on a web page. It allows content to move horizontally or vertically across the screen, providing a simple way to add dynamic movement to elements. To apply for a marquee, you have to use `<marquee> </marquee>` tags.

---

### 29. **What is the difference between the `id` attribute and the `class` attribute of HTML elements?**

Multiple elements in HTML can have the same `class` value, whereas a value of `id` attribute of one element cannot be associated with another HTML element.

---

### 30. **Describe HTML layout structure**

Every web page has different components to display the intended content and a specific UI. But still, there are few things which are templated and are globally accepted way to structure the web page, such as:

- `<header>` - stores the starting information about the web page.
- `<footer>` - represents the last section of the page.
- `<nav>` - the navigation menu of the HTML page.
- `<article>` - it is a set of information.
- `<section>` - it is used inside the article block to define the basic structure of a page.
- `<aside>` - sidebar content of the page.

---

### 31. **What is the significance of `<head>` and `<body>` tag in HTML?**

- `<head>` tag provides the information about the document. It should always be enclosed in the `<html>` tag. This tag contains the metadata about the webpage and the tags which are enclosed by head tag like `<link>`, `<meta>`, `<style>`, `<script>`, etc. are not displayed on the web page. Also, there can be only one `<head>` tag in the entire HTML document and will always be before the `<body>` tag.

- `<body>` tag defines the body of the HTML document. It should always be enclosed in the `<html>` tag. All the contents which needs to be displayed on the web page like images, text, audio, video, contents, using elements like `<p>`, `<img>`, `<audio>`, `<heading>`, `<video>`, `<div>`, etc. will always be enclosed by the `<body>` tag. Also, there can be only one body element in an HTML document and will always be after the `<head>` tag.

---

### 32. **What is `div` element?**

1. The `<div>` tag defines a division or a section in an HTML document.

2. The `<div>` tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript.

3. The `<div>` tag is easily styled by using the class or id attribute.

Any sort of content can be put inside the `<div>` tag!

---

### 33. **Difference between link tag `<link>` and anchor tag `<a>` in HTML?**

The anchor tag `<a>` is used to create a hyperlink to another webpage or to a certain part of the webpage and these links are clickable, whereas, link tag `<link>` defines a link between a document and an external resource and these are not clickable.

---

### 34. **How to include javascript code in HTML?**

HTML provides a `<script>` tag using which we can run the javascript code and make our HTML page more dynamic.

---

### 35. **What is the difference between `<figure>` tag and `<img>` tag?**

The `<figure>` tag specifies the self-contained content, like diagrams, images, code snippets, etc. `<figure>` tag is used to semantically organize the contents of an image like image, image caption, etc., whereas the `<img>` tag is used to embed the picture in the HTML5 document.

---

### 36. **What is the difference between `<picture>` tag and `<img>` tag?**

The `<img>` tag in HTML is used to display a **single** image. It has attributes like `src`, `alt`, and `width/height` for basic image handling.

The `<picture>` tag is more flexible, allowing you to define **multiple** image sources for different scenarios (e.g., responsive images, different formats). Inside `<picture>`, you can include multiple `<source>` elements with conditions like media queries or image formats, which helps deliver the most appropriate image based on screen size or browser capabilities.
