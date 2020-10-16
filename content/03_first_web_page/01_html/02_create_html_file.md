+++
title = "Create HTML File"
chapter = false
weight = 2
+++

### Create index.html File

Open up your text editor and create a new folder named `website` on the your Desktop. In VS Code, you'll click "Open Folder", navigate to your Desktop, and create a new folder. This is the folder that will hold all of the static resources for your website, including the HTML, CSS, JavaScript, and any images.

Inside the `website` folder, start a new file. Before adding any code to this file, save it with the name `index.html` to the `website` folder located on your desktop.

![](../../images/save-file.png)

When we set the file extension, `.html`, your text editor knows what type of file you are working with and will give you some hints along the way.

### Add HTML

Copy the HTML document below and paste it into the `index.html` file you just created. Save the file.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hello, World!</title>
</head>
<body>
  <h1>Hello, World!</h1>
</body>
</html>
```

### View Web Page in Your Browser

In order to see what we're building as we build it, we'll want to open this HTML file in our browser. Go to the `website` folder on your Desktop and open the file. Because of the file extension, `.html`, your computer knows to open this in your default browser. If your default browser is not set to Chrome or Firefox, you can right-click on the file and select "Open with..." to use Chrome or Firefox.

![](../../images/hello-world-browser.png)

Right now, your web page is not running on a server. We are viewing it locally on your computer, in the browser and the browser knows how to render the HTML.

### Get to Know the Browser Dev Tools

While viewing the index.html web page in your browser, right-click anywhere on the page and select "Inspect".