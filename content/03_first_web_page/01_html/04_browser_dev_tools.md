+++
title = "Browser Dev Tools"
chapter = false
weight = 4
+++

### Get to Know the Browser Dev Tools

The browser dev tools help you debug your frontend code, see what the page sent to or received back from the backend servers, and even assess the accessibility of your site.

Let's fix that image. Right-click on the broken image and select "Inspect". The browser dev tools will open to the "Elements" tab, showing the specific element you chose to inspect, in this case the `<img>` element. The "Elements" tab will show the HTML document and as you click on each element, you can view more information about it, including the CSS styles that apply to that specific element.

Make note of the `src` attribute and its value. Refresh the page once more, then select the "Network" tab in the dev tools. This tab lists all of the requests (and their responses) that the browser made on behalf of the page to other locations. You'll see the following requests in the screenshot below:

- `blog.html` - this is the browser requesting the web page from the server
- `280?id=10` - a request for https://placedog.net/500/280?id=10
- `280?id=59` - a request for https://placedog.net/500/280?id=59
- `boston-terrier.jpg` - shown in red, this indicates an error.

![](/images/network-tab.png)

If you click on the request that is failing (red), you'll see the full URL in the "Request URL" of the "General" tab. You'll also see this error reflected on the "Console" tab and it even shows the line number in the HTML where the error occurred.

![](/images/console-tab.png)

Click on the linked file and line number on the right. This will take you to the "Source" tab and show you where the error is occurring in the code. The `src` attribute is referring to `images/boston-terrier.jpg` but if you look at the highlighted folder in the screenshot below, you'll see there is no `boston-terrier.jpg` file nor is there even an `images` folder inside the `website` folder.

![](/images/source-tab.png)

Let's fix it!

Inside your `website` folder, create a new folder named `images`. Download this {{% button href="/03_first_web_page/01_html/files/images/boston-terrier.jpg" icon="fas fa-download" %}}image file{{% /button %}} and put it into the new `images` folder.

Now, your `website` file structure should look like this:

![](/images/website-file-structure.png)

The `src` attribute of the `img` tag is expecting the file to be located in the `images` folder. Our website can access its own files, any of those static resources located in the `website` folder. Sometimes this is called the root folder. To refer to those files, you don't need to specify the `website` folder in the `src` path. The browser knows you are referring to the files at the root folder of the website.

Refresh the page and make sure the image is displayed. You'll notice that the image is way too big.

![](/images/image-too-big.png)

Let's fix it!

In the `index.html` file, find the HTML element for the image.

It will look like this:

```
<img src="images/boston-terrier.jpg" alt="Blog Post Title 3">
```

Instead of using the default height and width of the image, we'll make the width match the others by specifying the `width` attribute. Change it to this:

```
<img src="images/boston-terrier.jpg" width="500" alt="Blog Post Title 3">
```

After refreshing the page, the image for the third post should look consistent with the others!

Right now, your page is using the browser's default CSS style sheet. You'll notice that the HTML already includes CSS classes applied to the HTML elements. Next, we'll update the CSS of the page to give those elements some style.