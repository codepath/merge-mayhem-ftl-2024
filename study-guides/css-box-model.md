# CSS Box Model

In a document, or a website, each element is represented by a regular box. Each of the rectangular boxes has four edges: the margin edge, border edge, padding edge, and content edge. Let's take a look at the CSS Box Model.


## Box Model Components

![Image of CSS box model](https://upload.wikimedia.org/wikipedia/commons/7/7a/Boxmodell-detail.png)

Source: [Wikipedia](https://en.wikipedia.org/wiki/CSS_box_model)

- `width`: This refers to the width of the content area of the element.
- `height`: This refers to the height of the content area of the element.
- `padding`: Directly surrounding the content area of the element is the padding. The **padding** can be divided into four different properties: `padding-top`, `padding-right`, `padding-bottom`, and `padding-left`. Most web browsers give elements a default padding size of `0px`.
- `border`: The **border** is the space between the padding and margin. Developers can modify the `border-color`, `border-style`, and `border-width` of an element. These properties can also be specified to its 4 different edges: `border-top`, `border-right`, `border-bottom`, and `border-left`. Most web browsers give elements a default border size of `0px`.
- `margin`: The **margin** is the outermost space directly surrounding the border. The margin can be divided into four different properties: `margin-top`, `margin-right`, `margin-bottom`, and `margin-left`. Most web browsers give elements a default margin size of `16px`.

- Property: A property is the type of style on an HTML element. This includes color, positioning, font, border, etc. Check out MDN Docs for a full list of CSS properties.
- Value: This is the exact style you want to implement on your website. In the example above, we want to use the color `navy` in the `body` of our website.
- **Note:** Each property has its own set of valid values. For example, The `color` property can take values by name (`blue`, `green`, etc), Hex format (`#FFFFFF`), or RGB colors (`rgb(255,255,255)`).
- `:`: The colon symbol is used to separate the property and value.
- `;`: The semicolon symbol is used to end a declaration or rule.

There are many great reference materials to read about different CSS properties and values. We highly recommend checking out [CSS Reference's free visual guide to CSS](https://cssreference.io/).

## CSS Selectors

Let’s take a step back and review different CSS selectors and their associated syntax. For this we will focus on the basic selectors, but we highly recommend you check out MDN Docs for a [full list of CSS selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors).

:bangbang: **Tip**: For sizing, you can use a variety of units. The popular units are `em`, `%`, or `px`. Check out MDN Docs on [CSS values and units](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units).

You can learn more about the [CSS Box Model on MDN Doc](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model).

## 🐞 Debugging with Chrome Developer Tools

Using a [Chrome](https://www.google.com/chrome/) browser? The DevTools on Chrome is a great resource to help you debug your code, visualize changes in HTML or CSS, and analyze the positioning of elements based on the box model.

![Gif on Chrome DevTools and element inspection](http://www.compjour.org/files/images/tutorials/devtools/inspecting-elements-perusing-the-dom.gif)

Source: [Computational Journalism](http://www.compjour.org/tutorials/elements-of-a-webpage/)

The DevTools in Chrome is very powerful. We highly recommend you take the time to check out Computational Journalism's tutorials on [elements of a webpage](http://www.compjour.org/tutorials/elements-of-a-webpage/) and [Chrome DevTools documentation](https://developer.chrome.com/docs/devtools/).
