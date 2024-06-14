# HTML Elements and Syntax
## Introducing the `div` element

The `div`, or content division element, is used to define sections or divisions of content on the webpage. When using these elements you may not see a difference from the user-view but it helps organize groups of elements within the html page.

**_But why is it necessary to organize your html elements?_**

There are many reasons why developers might use the `div` element in their code. Some of which may include:

- **Creating more readable code.** Using the `div` element makes it easier for code reviewers to see defined sections to help identify bugs, or isolate features to sections on the website.
- **For styling!** By creating defined sections, it allows developers to add custom styling to each section of their website. This is perhaps one of the most common reasons developers use `div` tags.
In order for our style sheet, or CSS file, to identify the different `div` sections, we use custom selectors. This is where attributes like `id` and `class` come in!

- `id` attribute: An id is a name that is  unique to an element. This means that no two elements can share the same `id`.
- `class` attribute: Unlike the `id` attribute, multiple elements can share the same `class` name. This can be helpful when styling similar types of sections or elements.

We will explore more about the CSS syntax used to apply styling to `id` and `class` names in the next section. For now, let’s set up the structure of our client’s personal website based on our wireframe.