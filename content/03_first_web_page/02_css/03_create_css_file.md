+++
title = "Create CSS File"
chapter = false
weight = 3
+++

### Create CSS File

Inside the `website` folder, create a folder to hold your CSS code and name it `css`. Create a new file named `styles.css` inside the new `css` folder. Your website folder structure will now look like this:

![](/images/website-file-structure-css-step.png)

### Add CSS

Copy the CSS rules below and paste it into the `styles.css` file you just created. Save the file.

```
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

header {
  text-align: center;
  padding: 75px;
  background-color: #19549e;
  color: #ffffff;
}

header a {
  color: #ffffff;
}

h2, h3 {
  text-transform: uppercase;
}

a {
  text-decoration: none;
}

.content-wrapper {
  display: grid;
  grid-template-columns: 2fr 8fr 2fr;
}

.content {
  grid-column-start: 2;
  grid-column-end: 2;
}

.posts-wrapper {
  display: grid;
  row-gap: 45px;
}

.post-wrapper {
  display: grid;
  grid-template-columns: 1fr 3fr;
  column-gap: 35px;
}

.post-content h3 {
  margin-top: 0;
}

.post-image > img {
  width: 100%;
}

footer {
  text-align: center;
  margin: 25px 0;
}
```

### Link to CSS File

Before viewing the styled page in the browser, you'll also need to link your HTML to that CSS file. To do this, we'll use the `link` tag inside the `head` element.

Remove the entire `style` element setting the body font from the `head` of the HTML and replace it with this:

```
<link rel="stylesheet" href="css/styles.css">
```

### View Web Page in Your Browser

Now that you've added some CSS styles and linked the HTML to the `styles.css` file, you can open the `index.html` file in our browser or refresh the page if it's already open.

![](/images/styled-with-css.png)

#### Congratulations!

🎉 You've styled the HTML of your first web page using CSS!

Wondering what all those CSS rules do? Time to look at them in the browser dev tools.

### Inspect CSS Styles in Browser Dev Tools

Right-click on the title of the page, "My First Blog", and select "Inspect". The browser dev tools will open to the "Elements" tab, showing the specific element you chose to inspect, in this case the `<h1>` element. The "Elements" tab will show the HTML document and as you click on each element, you can view more information about it, including the CSS styles that apply to that specific element.

In the right panel Styles tab, you will see the CSS styles that are applied to the specific HTML element you've selected. You can add new rules here or disable rules, testing your code directly in the browser before adding it to your code.

![](/images/styles-tab.png)