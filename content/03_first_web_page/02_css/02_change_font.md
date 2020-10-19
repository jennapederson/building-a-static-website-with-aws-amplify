+++
title = "Change the Font"
chapter = false
weight = 2
+++

### Change the Font

Let's first change the font of the body of the HTML. CSS rules can be added directly to elements, inside the `head` of the page, or in an external `.css` file linked from the `head` of the page.

Inside of the `head` element of your `index.html` file, add the following at the bottom, immediately proceeding the closing `head` tag.

```
<style>
    body {
      font-family: Arial, Helvetica, sans-serif;
    }
</style>
```

We'll add this rule directly to the `head` to see how it works, but we'll add the rest of the CSS rules to an external CSS file.

After saving the file, refresh the page in your browser and note font changed to Arial.
