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

If you scroll to the bottom of the page, you'll notice that one of the images is broken. Let's fix it!

### Get to Know the Browser Dev Tools

The browser dev tools help us debug our frontend code, see what we sent to or received back from our backend servers, and even assess the accessibility of our site.

Let's fix that image. Right-click on the broken image and select "Inspect". The browser dev tools will open to the "Elements" tab, showing the specific element you chose to inspect, in this case the `<img>` element. The "Elements" tab will show the HTML document and as you click on each element, you can view more information about it, including the CSS styles that apply to that specific element.

Make note of the `src` attribute and its value, then select the "Network" tab. This tab lists all of the requests (and their responses) that the browser made on behalf of the page to other locations. You'll see the following requests in the screenshot below:

- `blog.html` - this is the browser requesting the web page from the server
- `280?id=10`
- `280?id=59`
- `280?id=82`
- `boston-terrier.jpg` - shown in red, this indicates an error.

![](../../images/network-tab.png)

If you click on the request that is failing (red), you'll see the "Request URL" in the "General" tab refers to an image that we don't yet have in the `website` folder. In fact, we don't even have an `images` folder!

You'll also see this error reflected on the "Console" tab and it even shows the line number in the HTML where the error occurred.

![](../../images/console-tab.png)

Click on the link on the right to go to the code in your browser dev tools.