# Tribe Block HTML Tutorial

Welcome to the **HTML** tutorial! This guide will take you through the fundamentals of HTML, explaining the essential elements and techniques that are used to create well-structured web pages. Whether you're a beginner or want to refresh your knowledge, this guide is for you!

---

## Table of Contents

1. [What is HTML?](#what-is-html)
2. [HTML Document Structure](#html-document-structure)
3. [Common HTML Elements](#common-html-elements)
4. [HTML Attributes](#html-attributes)
5. [Links and Navigation](#links-and-navigation)
6. [Images and Media](#images-and-media)
7. [Forms and Input](#forms-and-input)
8. [Semantic HTML](#semantic-html)
9. [HTML5 New Features](#html5-new-features)
10. [Useful Resources](#useful-resources)

---

## What is HTML?

HTML (HyperText Markup Language) is the standard language used to create web pages. It provides the structure of web documents by using a system of tags and attributes that tell the browser how to display content. HTML is not a programming language, but a markup language that structures content.

HTML documents are made up of elements like headings, paragraphs, links, images, lists, and more.

For an in-depth definition of HTML, you can refer to the [MDN HTML Introduction](https://developer.mozilla.org/en-US/docs/Web/HTML).

---

## HTML Document Structure

An HTML document is structured using several key components:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tutorial</title>
</head>
<body>
    <h1>Welcome to the HTML Tutorial</h1>
    <p>This is a sample HTML document.</p>
</body>
</html>
```
### Key Components:
```
<!DOCTYPE html> - Declares the document type and version (HTML5).

<html> - Root element of the document.

<head> - Contains metadata like the document title, character encoding, and other settings.

<body> - Contains the content of the page, including text, images, and other elements.
```
For a detailed breakdown of the document structure, see [HTML Basic Structure](https://developer.mozilla.org/en-US/docs/Web/HTML/Structure).

# Common HTML Elements
Here are some of the most commonly used HTML elements:

## Headings
Headings range from <h1> (largest) to <h6> (smallest), used to define section titles.
```
<h1>This is a heading 1</h1>
<h2>This is a heading 2</h2>
```
## Paragraphs
Paragraphs are defined with the <p> tag.
```
<p>This is a paragraph of text.</p>
```
## Links
Links are created using the <a> (anchor) element with the href attribute.
```
<a href="https://www.example.com">Visit Example</a>
```
## Lists
HTML supports both ordered (numbered) and unordered (bulleted) lists.

### Unordered List
```
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```
### Ordered List
```
<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```
### Images
The <img> tag is used to embed images in your page. It requires the src attribute for the image path and alt for accessibility.
```
<img src="image.jpg" alt="Description of the image">
```
# HTML Attributes
Attributes provide additional information about HTML elements. They are always specified in the opening tag and are written as name-value pairs.

Example: The href Attribute
```
<a href="https://www.example.com">Click here</a>
```
# Common HTML Attributes:
* id - A unique identifier for an element.
* class - A class name that can be used to apply styles to elements.
* style - Inline CSS styles.
* src - Specifies the path to an image, video, or script.
* alt - A textual description of an image for accessibility.

# Links and Navigation
HTML allows you to create links to other pages, files, or websites using the <a> tag.

Example of a simple navigation bar:
```
<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>
```
For more on navigation elements, refer to [MDN Navigation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav).

# Images and Media
Images are added using the <img> tag, while other media types like video and audio can be embedded with the <video> and <audio> tags, respectively.

## Video Example:
```
<video controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```
For more on embedding multimedia, check out [MDN Media](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video).

# Forms and Input
HTML forms are used to collect user input.
The <form> tag is used to define a form, and input fields are defined using various <input> tags, including text fields, buttons, checkboxes, etc.

## Basic Form Example:
```
<form action="/submit" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <button type="submit">Submit</button>
</form>
```
For more details on forms, check out the [MDN Forms Guide](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form).

# Semantic HTML
Semantic HTML refers to using HTML elements that convey meaning about the content they contain. For example, the <header>, <footer>, <article>, and <section> elements are semantic elements that help structure content meaningfully.

## Example:
```
<header>
    <h1>Welcome to Our Website</h1>
</header>
<article>
    <h2>Latest News</h2>
    <p>Here’s the latest news...</p>
</article>
<footer>
    <p>&copy; 2025 Example Corp</p>
</footer>
```
Semantic HTML improves accessibility and SEO.

# HTML5 New Features
HTML5 introduced a lot of new features, such as new form elements, video and audio embedding, and improved support for local storage.

## Example of new input types:
```
<input type="email" name="user_email">
<input type="date" name="event_date">
```
For more on HTML5, see the [HTML5 Overview](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5).

# Useful Resources
* [MDN HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
* [HTML5 Doctor](http://html5doctor.com/)
* [FreeCodeCamp HTML Guide](https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/)

