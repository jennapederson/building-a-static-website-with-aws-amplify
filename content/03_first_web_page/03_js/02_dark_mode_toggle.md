+++
title = "Add Dark Mode Toggle"
chapter = false
weight = 2
+++

Let's add a dark mode to our new website. We'll add a toggle button and change the applied CSS styles when the button is pressed using JavaScript.

### Add a toggle button

Add the button code below as the last element in the `header` in your `index.html` file, right before the closing `header` tag. Note that we've added the `dark-mode-toggle` class and set an `onclick` JavaScript handler directly to the button, a function named `toggleDarkMode`.

```
<button class="dark-mode-toggle" onclick="toggleDarkMode()">Toggle dark mode</button>
```

### Write the JavaScript

JavaScript can go in the `head`, the `body`, or after the `body`, depending on when you want it to run. It can also be included in a separate JavaScript file and then included in the HTML using the `script` tag with the `src` attribute.

Today, we'll put it directly in a `script` tag in the HTML file. Toward the end of the `index.html` file, add the JavaScript function below right between the closing `footer` tag and the closing `body` tag.


```
<script type="text/javascript">
  function toggleDarkMode() {
    var element = document.body;
    element.classList.toggle("dark-mode");
  }
</script>
```

The function `toggleDarkMode` will get the `body` element's list of classes and toggle (add or remove) the `dark-mode` class.

### Add the Dark Mode Styles

Now we need to add some CSS rules when the `dark-mode` class is used. Add the following to the `styles.css` file:

```
.dark-mode {
  background-color: #121212;
  color: white;
  opacity: 87%;
}

.dark-mode .dark-mode-toggle {
  background-color: #ffffff;
  color: #121212;
}

button {
  background-color: #121212;
  color: #ffffff;
  padding: 10px;
}
```

### View Web Page in Your Browser

Now you can go back to the page in your browser and press the toggle button.

TODO
![](../../images/styled-with-css.png)

#### Congratulations!

🎉 You've toggled CSS classes with JavaScript to change the look and feel of the page when a button is pressed!

Let's deploy this site!