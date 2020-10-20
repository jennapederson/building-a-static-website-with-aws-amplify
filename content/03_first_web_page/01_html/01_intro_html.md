+++
title = "Intro to HTML"
chapter = false
weight = 1
+++

# What is HTML?

HTML is HyperText Markup Language, essentially text linking to other related text. HTML defines the structure of your web page. telling the browser that a block of text is a paragraph, that an image is an image, and that a link is a link and should take the user to that location when clicked.

HTML is made up of elements that wrap your content to make it show up in your browser based on that type of element. You are telling your browser that this should be a paragraph of text.

![](../../images/HTMLElement.png)

- Opening tag: the name of the element wrapped with opening and closing angle brackets
- Attribute: conveys extra information about the element
- Content: your content is wrapped by the opening and closing tag
- Closing tag: the name of the element wrapped with opening and closing angle brackets, with a forward slash preceding the element name, signaling to the browser that we are done with this chunk of content and to close the element

HTML elements can be nested inside other elements. HTML element can contain attributes that convey extra information about the element. HTML elements can also be empty, without content.

## Basic HTML File Structure

`html` tags wrap an entire HTML document. The `head` tag contains information about the page itself, including the title which shows in the browser tab or window.

The `body` of the html document is where our content will live — everything you want to be shown to the user will be nested inside the opening and closing body tags.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TITLE</title>
</head>
<body>
  YOUR CONTENT
</body>
</html>
```

Note that the `DOCTYPE` is information for the browser so it knows what type of document to expect. It is not an HTML tag.

Let's try this out!