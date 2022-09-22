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

Our Document is called the root node and contains a children node which is the HTML. The HTML contains two children which is `head` and `body` elements.

Both `head` and `body` elements have children their own.

Here is another way to visualize this tree of nodes.

![tree-nodes](/images/tree-nodes.jpg)

We can access these elements in the document and make changes to them by JavaScript.

The previous sort examples, nearly all examples, is JavaScript. That is to say, it is writen inside JavaScript, but uses the document object model to acessing the document and it's elements. The document object model is not programing language, but without it, JavaScript language would not have anything type or notion of web pages, the HTML documents, the SVG documents and the parts of component. The document as a whole, the head, tables within document, the head table and text within cells of table and all another elements in document are parts of DOM for that document. They can be all acessed ... using DOM and a script language as JavaScript

### Reference:

- https://www.freecodecamp.org/news/what-is-the-dom-document-object-model-meaning-in-javascript/
- https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction
- https://www.w3schools.com/js/js_htmldom.asp
