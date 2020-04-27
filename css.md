[Home - Table of Contents](index)

## Design Web Pages with CSS

### What is CSS
CSS allows you to control the appearance of content. It works by allowing you to set rules that determine how the content of specified elements will be displayed. A rule has a selector and a declaration. The selector specifies the element/s and the declaration sets values for properties of the element. For example, a {color: red;} specifies that color property of the link element (anchor) be set to red.

There are three primary selector categories that target content on a page:

- The **type** selector (sometimes called the name or element selector) uses the element's name. E.g., `h1 {color: red;}`
- The **class** selector uses the class attribute. E.g., `.myboxes {background: red;}` sets the background color of all the elements with a class attribute that includes myboxes.
- The **ID** selector uses the elements id attribute. E.,g. `#box4 {background: red;}` sets the background color of the specific element that has its id attribute set to box4.

There are many additional types of selectors that allow you to drill down to target specific elements or sets of elements. For example, you can set and then target custom attributes. If the HTML element is `<a href="bandpic" data-filetype="image">Link Text</a>` it can be targeted using `a[data-filetype="image"] {color: red;}`.

It's usually best to write css into one or more external style sheets, one obvious advantage being the styles can be shared across multiple pages. The styles cascade according to prioritization and inheritance rules including the order in which they are set and the specificity with which they are set.

### Color
Color is an important element of design. Ensuring sufficient contrast between text and background colors is essential to ensure the site is accessible to as many people as possible.

Color can be specified using RGB values, Hex values, or predefined color names. For example `color: rgb(255,255,255);` is the same as `color: #ffffff;` and the same as `color: white;`. CSS3 also allows colors to be specified with hsl values. `color: hsl(0, 0%, 100);` also specifies white. Both hsl and rgb also allow an alpha channel to be specified for opacity.