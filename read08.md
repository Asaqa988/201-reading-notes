# Layout
 
- Controlling t XX he position of elements
- XX Creating site layouts
- XX Designing for different sized screens


## Key Concepts in Positioning El ements

### Building Blocks
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

#### Block-level elements
* start on a new line
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
enim ad minim veniam, quis nostrud exercitation ullamco laboris
nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
reprehenderit in voluptate velit.
• Lorem ipsum dolor sit

• Consectetur adipisicing

• Elit, sed do eiusmod
![](https://th.bing.com/th/id/R.9cacc34a885090538332c1a8be21580e?rik=vGyQrBFqwDZwoA&pid=ImgRaw)

### Containing Elements

If one block-level element sits inside another block-level element then the outer box i  known as the containing or parent element.

## Normal Flow
### position:static
In normal flow, each block-level element sits on top of the next one. Since this is the default
way in which browsers treat HTML elements, you do not
need a CSS property to indicate that elements should appear in normal flow, but the syntax would be:


## Screen Resolution
- Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

## Page Sizes
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).

## Fixed Width Layouts
* Advantages
- Pixel values are accurate at controlling size and positioning of elements.

- The designer has far reater control over the appearance and position of items on the page than with liquid layouts.

- You can control the lengths of lines of text regardless of the size of the user’s window.

- The size of an image will always remain the same relative to the rest of the page.

* Disadvantages
- You can end up with big gaps around the edge of a page.

- If the user’s screen is a much higher resolution than the designer’s screen, the page can look smaller and text can be harder to read.
- If a user increases font sizes, text might not fit into the allotted spaces.

* The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.

### The page will often take up more vertical space than a liquid layout with the same content.
## Liquid Layouts
* Advantages
- Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.

- If the user has a small window, the page can contract to fit it without the user having to scroll to the side.

- The design is tolerant of users setting font sizes larger than the designer intended (because the page can stretch).

* Disadvantages
- If you do not control the width of sections of the page then the design can look very different than you intended, with unexpected gaps around certain elements or items squashed together.

- If the user has a wide window, lines of text can become very long, which makes them harder to read.

- If the user has a very narrow window, words may be squashed and you can end up with few words on each line.

- If a fixed width item (such as an image) is in a box that is too small to hold it (because the user has made the window smaller) the image can overflow over the text.
 
