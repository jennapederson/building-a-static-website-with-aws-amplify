+++
title = "Change HTML Layout"
chapter = false
weight = 3
+++

### Create Blog Layout in HTML

Let's turn that into a webpage with a simple blog layout. Copy the HTML below and paste it into your `index.html` file.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Blog</title>
</head>
<body>
  <h1>My First Blog</h1>
  <div>
    <div>
      <h2>Blog Post Title 1</h2>
      <h3>Posted on: 16 October 2020</h3>
      <img src="https://placedog.net/500/280?id=10" alt="Blog Post Title 1">
      <div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
    </div>
    <div>
      <h2>Blog Post Title 2</h2>
      <h3>Posted on: 10 September 2020</h3>
      <img src="https://placedog.net/500/280?id=59" alt="Blog Post Title 2">
      <div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        <p>Lorem ipsum dolor sit amet.</p>
      </div>
    </div>
    <div>
      <h2>Blog Post Title 3</h2>
      <h3>Posted on: 1 August 2020</h3>
      <img src="images/boston-terrier.jpg" alt="Blog Post Title 3">
      <div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
    </div>
  </div>
  <footer>Made with 🐶 💕</footer>
</body>
</html>
```

Save the file. Then back to your browser and refresh the page. You should now see the following blog layout:

![](../../images/my-first-blog-browser.png)


If you scroll to the bottom of the page, you'll notice that one of the images is broken.

![](../../images/missing-image.png)

Let's fix it!
