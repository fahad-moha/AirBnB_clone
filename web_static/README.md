# AirBnB clone - Web static

## Table of Contents

1. [HTML](#html)
2. [Creating an HTML Page](#creating-an-html-page)
3. [Markup Language](#markup-language)
4. [DOM (Document Object Model)](#dom-document-object-model)
5. [Element / Tag](#element--tag)
6. [Attribute](#attribute)
7. [Loading a Webpage in a Browser](#loading-a-webpage-in-a-browser)
8. [CSS (Cascading Style Sheets)](#css-cascading-style-sheets)
9. [Adding Style to an Element](#adding-style-to-an-element)
10. [Class](#class)
11. [Selector](#selector)
12. [Computing CSS Specificity Value](#computing-css-specificity-value)
13. [Box Properties in CSS](#box-properties-in-css)

## HTML
HTML (Hypertext Markup Language) is the standard markup language used for creating web pages. It provides a structure and defines the content of a webpage using tags and elements.

## Creating an HTML Page
To create an HTML page, create a new file with a .html extension. Here's an example of a basic HTML page:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Webpage</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is a paragraph.</p>
</body>
</html>
```

## Markup Language
A markup language is a system of annotating a document to define its structure and presentation. HTML is an example of a markup language used for creating web pages.

## DOM (Document Object Model)
The DOM (Document Object Model) is a programming interface for HTML and XML documents. It represents the structure of a document as a tree-like structure, where each node represents an element, attribute, or text. The DOM can be accessed and manipulated using JavaScript.

## Element / Tag
In HTML, an element or tag represents a specific component or part of a webpage. Elements are defined using opening and closing tags and can contain content or other nested elements. For example:

```html
<p>This is a paragraph element.</p>
```

## Attribute
An attribute provides additional information about an HTML element. Attributes are specified within the opening tag of an element. For example:

```html
<a href="https://example.com">Click me</a>
```

In the above example, `href` is an attribute that defines the URL to which the link will navigate.

## Loading a Webpage in a Browser
When a browser loads a webpage, it follows a series of steps. These steps include making an HTTP request to the server, receiving the HTML content, parsing the HTML to construct the DOM, fetching external resources (such as CSS and JavaScript), rendering the webpage, and executing any scripts.

## CSS (Cascading Style Sheets)
CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of a document written in HTML. It defines how HTML elements should be displayed on a webpage.

## Adding Style to an Element
You can add style to an HTML element using inline styles or by using external CSS. Here's an example of inline styles:

```html
<p style="color: red; font-size: 20px;">This is a styled paragraph.</p>
```

## Class
A class is an attribute used to classify or categorize elements. It allows you to apply styles or perform actions on multiple elements with the same class name. For example:

```html
<p class="highlight">This is a highlighted paragraph.</p>
```

## Selector
A selector is a pattern used to select specific elements in an HTML document. It is used in CSS to specify which elements the associated styles should be applied to. For example:

```css
h1 {
  color: blue;
}
```

In the above example, `h1` is a selector that selects all `<h1>` elements to apply the specified style.

## Computing CSS Specificity Value
CSS Specificity is a weight that determines which styles should be applied to an element when multiple styles conflict. It is calculated based on the combination of selectors used. Specificity values can be computed using rules such as:

- Inline styles have the highest specificity.
- IDs have a higher specificity than classes and tags.
- The universal selector (`*`) has the lowest specificity.

## Box Properties in CSS
Box properties in CSS refer to the properties that affect the layout and sizing of elements. They include properties like `width`, `height`, `margin`, `padding`, `border`, and `display`, among others. Box properties control how elements are positioned, sized, and interact with other elements on the webpage.

