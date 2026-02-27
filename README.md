# 📘 Complete Beginner Guide to HTML

## 1️⃣ Introduction to HTML

### What is HTML?

HTML (HyperText Markup Language) is the standard markup language used to
create and structure web pages on the internet.

It is the basic building block of every website.

------------------------------------------------------------------------

### Understanding the Term HTML

-   **HyperText**: Text that links to other web pages.
-   **Markup**: Special symbols (called tags) used to structure content.
-   **Language**: A system used to communicate with web browsers.

------------------------------------------------------------------------

### Basic Facts About HTML

-   HTML files are saved with the `.html` extension.
-   HTML files are opened using web browsers like Chrome, Edge, or
    Firefox.
-   Every HTML document must begin with:

``` html
<!DOCTYPE html>
```

This declaration tells the browser that the document is written in
HTML5.

------------------------------------------------------------------------

### HTML Comments

Comments are used to write notes inside the code. They are not visible
in the browser.

``` html
<!-- Write your comments here -->
```

------------------------------------------------------------------------

### HTML Style Attribute

The `style` attribute is used to add styling such as color, font size,
and alignment to HTML elements.

Example:

``` html
<p style="color: blue;">Hello World</p>
```

------------------------------------------------------------------------

## 2️⃣ Structure of an HTML Page

Every HTML page follows this basic structure:

``` html
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        Content goes here
    </body>
</html>
```

### Explanation of Each Tag

  Tag         Purpose
  ----------- ---------------------------------------------
  `<html>`    Root element of the webpage
  `<head>`    Contains metadata (not visible on the page)
  `<title>`   Sets the browser tab title
  `<body>`    Contains visible webpage content

------------------------------------------------------------------------

## 3️⃣ Understanding HTML Tags

-   **Opening Tag** → `<tagname>`
-   **Closing Tag** → `</tagname>`

Example:

``` html
<p>This is a paragraph</p>
```

Some tags are **empty tags**, which means they do not require a closing
tag.

------------------------------------------------------------------------

## 4️⃣ Important HTML Tags

### 1. Heading Tags

HTML provides six heading levels:

``` html
<h1> to <h6>
```

-   `<h1>` -- Largest and most important heading\
-   `<h6>` -- Smallest heading

------------------------------------------------------------------------

### 2. Paragraph Tag

``` html
<p></p>
```

Used to define paragraphs. It automatically adds spacing before and
after the text.

------------------------------------------------------------------------

### 3. Anchor Tag (Link)

``` html
<a></a>
```

Used to create hyperlinks.

Important attribute:

-   `href` -- Specifies the destination URL.

Example:

``` html
<a href="https://www.google.com">Visit Google</a>
```

------------------------------------------------------------------------

### 4. Image Tag

``` html
<img>
```

Used to display images. It is an empty tag.

Important attributes:

-   `src` -- Image path
-   `alt` -- Alternative text

Example:

``` html
<img src="image.jpg" alt="Sample Image">
```

------------------------------------------------------------------------

### 5. Line Break Tag

``` html
<br>
```

Moves content to the next line without starting a new paragraph.

------------------------------------------------------------------------

### 6. Horizontal Rule Tag

``` html
<hr>
```

Creates a horizontal line to separate sections of content.

------------------------------------------------------------------------

### 7. Center Tag

``` html
<center></center>
```

Used to center content.\
Note: This tag is deprecated in modern HTML. CSS should be used instead.

------------------------------------------------------------------------

### 8. List Tags

Lists help organize content clearly.

#### Unordered List (Bullet Points)

``` html
<ul>
  <li>Apple</li>
  <li>Banana</li>
  <li>Orange</li>
</ul>
```

#### Ordered List (Numbered List)

``` html
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
```

------------------------------------------------------------------------

### 9. Table Tag

Used to display data in rows and columns.

``` html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
  </tr>
</table>
```

Table elements:

-   `<table>` -- Table container\
-   `<tr>` -- Table row\
-   `<th>` -- Table header cell\
-   `<td>` -- Table data cell

------------------------------------------------------------------------

### 10. Div Tag

``` html
<div></div>
```

Used as a container to group other HTML elements. It is commonly used
for layout design.

------------------------------------------------------------------------

### 11. Link Tag

``` html
<link>
```

Used to connect external resources, mainly CSS files.

Example:

``` html
<link rel="stylesheet" href="style.css">
```

------------------------------------------------------------------------

### 12. Form Tag

``` html
<form></form>
```

Used to collect user input.

Common form elements:

-   `<input>`
-   `<textarea>`
-   `<select>`
-   `<button>`

Example:

``` html
<form>
  <input type="text" placeholder="Enter your name">
  <button type="submit">Submit</button>
</form>
```

------------------------------------------------------------------------

### 13. Select Tag (Dropdown)

``` html
<select>
  <option>Option 1</option>
  <option>Option 2</option>
</select>
```

Used to create a dropdown list.

------------------------------------------------------------------------

## 5️⃣ HTML Formatting Elements

These tags change the appearance or meaning of text.

-   `<b>` -- Bold text\
-   `<strong>` -- Important text\
-   `<i>` -- Italic text\
-   `<em>` -- Emphasized text\
-   `<mark>` -- Highlighted text\
-   `<small>` -- Smaller text\
-   `<del>` -- Deleted text\
-   `<ins>` -- Inserted text\
-   `<sub>` -- Subscript text\
-   `<sup>` -- Superscript text

------------------------------------------------------------------------