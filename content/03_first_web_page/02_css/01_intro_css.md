+++
title = "Intro to CSS"
chapter = false
weight = 1
+++

### What is CSS?

Cascading Style Sheets, or CSS for short, is the code we use to style our content. We can make our paragraphs be a specific color, font, and font-size, to make clickable links stand out, or to show they are clickable when you hover over them.

Every browser has a default stylesheet. With CSS, we can apply styles that override the browser's default style sheet based on rules. You can target different elements in the HTML, you can target different browsers, and you can even target different screen sizes.

CSS is made up of rules.

![](/images/CSSRule.png)

- Selector: defined what element or elements this rule should apply to
- Property: The CSS property to influence
- Value: the new value of the property
- Rule: the property and value are the rule

### Browser Default Stylesheets

Every browser has a default stylesheet. This means that if we don't add any styling, the page is still accessible (or at least, it should be). However, it might not look as pretty or as on-brand as you'd expect. This also means that browsers are free to set their own defaults, can be different across browsers. This is one reason it is important to test your website in multiple browsers.

### CSS Selectors

CSS selectors can select one or more HTML elements, depending on how specific they are.

In the example above, the selector is an element selector, applying the rule to `p` elements.

#### Id Selector

The id selector selects the element with the given id.

```
#hello-world {
  color: red;
}
```

#### Class Selector

The class selector applies the rule to all elements that have the given class.

```
.content-wrapper {
  display: grid;
  grid-template-columns: 2fr 8fr 2fr;
}
```

Learn more about the other selectors [here](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors).

Let's try this out!