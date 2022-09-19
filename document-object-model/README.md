### Document Object Model (DOM)

#### What is the DOM?

> DOM stands for Document Object Model.

When web page is loaded, the browser creates a Document Object Model (DOM) for the page. The Document Object Model is a programming interface for web documents. It represents the page so that can change the structure document, style and content.

The Dom represents the document as nodes and objects, that way, programming languages can interact with the page. It allows us add, change and remove elements from the document. We can also add events to these elements to make our page more dynamic.

The dom views a HTML document as a tree of nodes. A node represents a HTML element.

Let's take a look at this HTML code to better understand the DOM tree structure:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>DOM tree structure</title>
  </head>
  <body>
    <h1>DOM tree structure</h1>
	<h2>Learn about the DOM</h2>
  </body>
</html>
```

### Reference:

- https://www.freecodecamp.org/news/what-is-the-dom-document-object-model-meaning-in-javascript/
- https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction
- https://www.w3schools.com/js/js_htmldom.asp
