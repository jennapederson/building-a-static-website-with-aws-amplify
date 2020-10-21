+++
title = "Intro to JavaScript"
chapter = false
weight = 1
+++

### What is JavaScript?

JavaScript (JS) is code that runs in your browser and makes your website more interactive. JavaScript can dynamically update the HTML and set CSS styles. It also allows developers to request data from your application's backend servers.

 JavaScript can run when your page first loads to pull in data from some other location. It can run in response to when a user takes an action on the page, like clicking a button. It can run at a regular interval, like every 10 seconds to refresh data on the page. JavaScript looks more like a traditional programming language compared to HTML and CSS.

A common use case for using JavaScript is when you type your password into an input form element and then mistype the confirmation password, you'll often see sites highlight that the two passwords don't match. They'll compare the values of the two password inputs with JavaScript and then use JavaScript to update the HTML of the page to show you an error message.

![](/images/JSClickHandler.png)

In the example above:

- `document` refers to the HTML of the page
- `querySelector(button)` is selecting the first button element from the document
- Refers to the selected element's `onclick` action handler
- The click handler is some functionality that we want to execute, wrapped in a function block

Let's try this out!