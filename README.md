# Custom Scrollbar on Hover

This is an HTML/CSS code snippet that demonstrates how to create a custom scrollbar that appears when hovering over content.
Scrollbar is rendered only if content overflows container.


[Live Demo](https://morsko1.github.io/custom-scrollbar-on-hover/index.html)


## HTML Structure

The HTML code is structured as follows:

- `<div class="page">`: Represents the main page container.
- `<div class="container">`: Represents a container element with a header and content.
- `<div class="header">`: Represents the header section of the container.
- `<div class="content">`: Represents the content section of the container.


## CSS Styling

The CSS code provided in the snippet is responsible for creating the custom scrollbar effect. Here's an overview of the CSS styles used:

- `.page`: Sets the main page container.
- `.header`: Styles the header section.
- `.container`: Styles the container element.
- `.content`: Styles the content section and enables vertical scrolling if the content exceeds the container height.
  - `&::-webkit-scrollbar`: Styles the scrollbar track, setting its width to 8 pixels.
  - `&::-webkit-scrollbar-thumb`: Styles the scrollbar thumb.
  - `&:not(:hover)::-webkit-scrollbar-thumb`: Hides the scrollbar thumb when not hovering over the content.
