***# CSS Interview Questions & Answers***

### Table of Contents

| Questions                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [What is CSS](#what-is-CSS)                                                                                                                                      |
| [What do you means by Cascading in CSS](#What-do-you-means-by-Cascading-in-CSS)                                                                                  |
| [What do you means by Specificity in CSS](#What-do-you-means-by-Specificity-in-CSS)                                                                              |
| [What do you means by Inheritance in CSS](#What-do-you-means-by-Inheritance-in-CSS)                                                                              |
| [What do you means by Non Inheritance in CSS](#What-do-you-means-by-Non-Inheritance-in-CSS)                                                                      |
| [What is Inline CSS](#What-is-Inline-CSS)                                                                                                                        |
| [Type of Inline CSS](#Type-of-Inline-CSS)                                                                                                                        |
| [Why do we use CSS](#Why-do-we-use-CSS)                                                                                                                          |
| [Advantages and Disadvantages of CSS](#Advantages-and-Disadvantages-of-CSS)                                                                                      |
| [How is CSS different from CSS3](#How-is-CSS-different-from-CSS3)                                                                                                |
| [List the CSS Frameworks](#List-the-CSS-Frameworks)                                                                                                              |
| [What is the syntax for CSS](#What-is-the-syntax-for-CSS)                                                                                                        |
| [In how many ways can we add CSS to our HTML file](#In-how-many-ways-can-we-add-CSS-to-our-HTML-file)                                                            |
| [What is Difference Between Padding and Margin](#What-is-Difference-Between-Padding-and-Margin)                                                                  |
| [What is the difference between Relative, Absolute and Fixed Positioning in CSS](#What-is-the-difference-between-Relative-Absolute-and-Fixed-Positioning-in-CSS) |
| [What is Flexbox](#What-is-Flexbox)                                                                                                                              |
| [What is Box Model in CSS](#What-is-Box-Model-in-CSS)                                                                                                            |
| [What is Box Sizing Property](#What-is-Box-Sizing-Property)                                                                                                      |
| [What is different between Content Box and Border Box](#What-is-different-between-Content-Box-and-Border-Box)                                                    |
| [What is Media Query ](#What-is-Media-Query)                                                                                                                     |
| [What is CSS preprocessor Sass](#What-is-CSS-preprocessor-Sass)                                                                                                  |
| [What is the default value of Position Property](#What-is-the-default-value-of-Position-Property)                                                                |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |
| [](#)                                                                                                                                                            |


### What is CSS

CSS, or Cascading Style Sheets, is a stylesheet language used to control the presentation and layout of web pages written in HTML and XML. It enables the separation of document content from presentation, allowing designers to style elements with properties such as color, layout, and typography for enhanced visual aesthetics.


**[⬆ Back to Top](#table-of-contents)**

---


### What do you means by Cascading in CSS

Cascading refers to the logic your browser uses to determine which CSS rulesets are the most important, especially when they conflict with each other. One of the simplest ways your browser does this is by paying attention to the order in which your rulesets appear.


**[⬆ Back to Top](#table-of-contents)**

---


### What do you means by Specificity in CSS

Specificity in CSS determines which style rule takes precedence when multiple rules target the same element. It is calculated based on the number and types of selectors used in a rule. Higher specificity values override lower ones, ensuring accurate and predictable styling of elements in web pages.


**[⬆ Back to Top](#table-of-contents)**

---


### What do you means by Inheritance in CSS

Inheritance refers to the ability of certain properties to be passed from a parent element to its children. Properties like font-family and color are inherited by default. 


**[⬆ Back to Top](#table-of-contents)**

---


### What do you means by Non Inheritance in CSS

Non-inheritance means properties that are not inherited and must be explicitly defined for each element, like width and margin.


**[⬆ Back to Top](#table-of-contents)**

---

### What is Inline CSS

Inline CSS is a style sheet that includes a CSS property in the content of an HTML element. It's used to apply a unique style to a single HTML element.


**[⬆ Back to Top](#table-of-contents)**

---


### Type of Inline CSS

There are two type of Inline CSS

1. **Replaced inline** elements are those whose content is outside of the document. For example, an image tag is a replaced inline element because its content is the image file itself. Replaced inline elements are typically displayed as boxes with specific dimensions.
   
2. **Non-replaced inline** elements are those whose content is contained in the document. For example, a span tag is a non-replaced inline element because its content is the text between the opening and closing tags. Non-replaced inline elements are typically displayed as lines of text.


**[⬆ Back to Top](#table-of-contents)**

---


### Why do we use CSS

We use CSS because of the following reasons:

1.  CSS saves time: You can write CSS once and reuse the same sheet on multiple HTML pages.
2.  Easy Maintenance: To make a global change simply change the style, and all elements in all the webpages will be updated automatically.
3.  Search Engines: CSS is considered a clean coding technique, which means search engines won’t have to struggle to “read” its content.
4.  Superior styles to HTML: CSS has a much wider array of attributes than HTML, so you can give a far better look to your HTML page in comparison to HTML attributes.
5.  Offline Browsing: CSS can store web applications locally with the help of an offline cache. Using of this we can view offline websites.


**[⬆ Back to Top](#table-of-contents)**

---


### Advantages and Disadvantages of CSS

Certainly! Here's a table outlining the advantages and disadvantages of CSS:

| Advantages of CSS                                        | Disadvantages of CSS                                         |
| -------------------------------------------------------- | ------------------------------------------------------------ |
| Allows for separation of content and design              | Browser compatibility issues                                 |
| Enhances consistency and maintainability                 | Steeper learning curve compared to basic HTML                |
| Offers greater control over styling elements             | Increased complexity for intricate layouts                   |
| Supports responsive design for various devices           | Potential for browser-specific quirks and inconsistencies    |
| Enables faster page loading through external stylesheets | Limited capabilities for complex animations and interactions |


**[⬆ Back to Top](#table-of-contents)**

---


### How is CSS different from CSS3

Here's the information converted into a table format:

| S.No. | CSS                                           | CSS3                                                                                                                    |
| ----- | --------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| 1     | Capable of positioning texts and objects.     | Capable of making the web page more attractive and takes less time to create. Writing CSS3 code in CSS will be invalid. |
| 2     | Responsive designing is not supported.        | CSS3 supports responsive design as it's the latest version.                                                             |
| 3     | Cannot be split into modules.                 | CSS3 can be broken down into modules.                                                                                   |
| 4     | Cannot build 3D animation and transformation. | Supports all kinds of animation and transformations including 3D animation.                                             |
| 5     | Slower compared to CSS3.                      | CSS3 is faster than CSS.                                                                                                |


**[⬆ Back to Top](#table-of-contents)**

---


### List the CSS Frameworks

The best CSS frameworks are:

1.  Bootstrap
2.  Foundation
3.  Bulma
4.  UIKit
5.  Semantic UI
6.  Materialize
7.  Pure
8.  Tailwind CSS


**[⬆ Back to Top](#table-of-contents)**

---


### What is the syntax for CSS

A CSS style rule consists of a selector, property, and its value. The selector points to the HTML element where CSS style is to be applied. The CSS property is separated by semicolons.

Syntax:

```
selector {
Property: value;
}
```


**[⬆ Back to Top](#table-of-contents)**

---


### In how many ways can we add CSS to our HTML file

Cascading Style Sheet(CSS) is used to set the style in web pages that contain HTML elements. It sets the background color, font size, font family, color, … etc properties of elements on a web page.
There are three types of CSS which are given below:

1.  Inline CSS: Inline CSS contains the CSS property in the body section attached with the element known as inline CSS. This kind of style is specified within an HTML tag using the style attribute.
2.  Internal or Embedded CSS: This can be used when a single HTML document must be styled uniquely. The CSS ruleset should be within the HTML file in the head section i.e the CSS is embedded within the HTML file.
3.  External CSS: External CSS contains a separate CSS file which contains only style property with the help of tag attributes (For example class, id, heading, … etc). CSS property is written in a separate file with .css extension and should be linked to the HTML document using the link tag. This means that for each element, style can be set only once and that will be applied across web pages.


**[⬆ Back to Top](#table-of-contents)**

---


### Which type of CSS holds the highest priority

In CSS, the specificity of selectors determines which styles are applied when multiple conflicting styles are defined for the same element. The priority order from highest to lowest is:

1. Inline styles: Styles defined directly on the HTML element using the `style` attribute.
2. ID selectors: Styles applied to elements with a specific ID using `#id`.
3. Class selectors, attribute selectors, and pseudo-classes: Styles applied to elements with a specific class, attribute, or pseudo-class like `:hover`.
4. Type selectors and pseudo-elements: Styles applied to elements based on their tag name or pseudo-elements like `::before`.
5. Universal selector (`*`) and combinators: Styles applied universally or based on element relationships like `div p`.

However, it's essential to note that !important declarations can override the specificity rules, so they should be used judiciously.


**[⬆ Back to Top](#table-of-contents)**

---


### What are CSS Selectors

CSS Selectors: CSS Selectors are used to selecting HTML elements based on their element name, id, attributes, etc. It can select one or more elements simultaneously.

element selector: The element selector in CSS is used to select HTML elements which are required to be styled. In a selector declaration, there is the name of the HTML element, and the CSS properties which are to be applied to that element is written inside the brackets {}.

Syntax:

```
element_name {
    // CSS Property
}
```

id selector: The #id selector is used to set the style of the given id. The id attribute is the unique identifier in an HTML document. The id selector is used with a # character.

Syntax:

```
#id_name {
    // CSS Property
}
```

class selector: The .class selector is used to select all elements which belong to a particular class attribute. To select the elements with a particular class, use the (.) character with specifying the class name. The class name is mostly used to set the CSS property to the given class.

Syntax:

```
.class_name {
    // CSS Property
}
```


**[⬆ Back to Top](#table-of-contents)**

---


### What are CSS HSL Colors

CSS HSL colors are a way to specify colors using hue, saturation, and lightness values. HSL stands for Hue, Saturation, and Lightness.

- **Hue (H)**: This represents the type of color, such as red, green, blue, etc. It is represented as an angle between 0 and 360 degrees on the color wheel. For example, 0° represents red, 120° represents green, and 240° represents blue.

- **Saturation (S)**: This represents the intensity or purity of the color. It is represented as a percentage, where 0% is a shade of gray (completely unsaturated), and 100% is the full color. Higher saturation values result in more vivid colors.

- **Lightness (L)**: This represents the brightness of the color. It is also represented as a percentage, where 0% is black (completely dark), 50% is the normal color, and 100% is white (completely light).

Here's the syntax for specifying colors using HSL in CSS:

```css
color: hsl(hue, saturation, lightness);
```

For example:

```css
color: hsl(120, 100%, 50%); /* Represents pure green */
```

HSL colors provide a more intuitive way to manipulate colors compared to hexadecimal or RGB values, especially when working with color variations and adjustments.


**[⬆ Back to Top](#table-of-contents)**

---


### What is difference between Canvas and SVG

| SVG                                                                                   | Canvas                                                                                         |
| ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| SVG uses geometric shapes to render graphics                                          | Canvas uses pixels                                                                             |
| Vector based (composed of shapes)                                                     | Raster based (composed of pixel)                                                               |
| SVG has better scalability. So it can be printed with high quality at any resolution. | Canvas has poor scalability. Hence it is not suitable for printing on higher resolution.       |
| SVG gives better performance with smaller number of objects or larger surface.        | Canvas gives better performance with smaller surface or larger number of objects.              |
| SVG can be modified through script and CSS.                                           | Canvas can be modified through script only.                                                    |
| Multiple graphical elements, which become the part of the page’s DOM tree.            | Single element similar to <img> in behavior. Canvas diagram can be saved to PNG or JPG format. |


**[⬆ Back to Top](#table-of-contents)**

---


### What is Difference Between Padding and Margin

| Property    | Padding                                                                                             | Margin                                                                                                                   |
| ----------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Definition  | Space between the content and the border of an element.                                             | Space outside the border of an element.                                                                                  |
| Affected by | Padding affects the area inside the border of an element.                                           | Margin affects the space outside the border of an element.                                                               |
| Purpose     | Used to create space between the content and the border of an element, providing visual separation. | Used to create space between elements, controlling their positioning relative to each other and their parent containers. |
| Collapsing  | Padding values do not collapse.                                                                     | Margin values may collapse under certain circumstances, such as adjacent margins of block elements.                      |
| Inheritance | Padding is not inherited by child elements.                                                         | Margin values are not inherited by child elements.                                                                       |


**[⬆ Back to Top](#table-of-contents)**

---


### What is the difference between Relative Absolute and Fixed Positioning in CSS

| Positioning Type | Description                                                                                                                                              |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Relative         | Positioned relative to its normal position in the document flow. It can be offset using top, bottom, left, and right properties.                         |
| Absolute         | Positioned relative to its nearest positioned ancestor (including the document body if no ancestor is positioned). It is taken out of the document flow. |
| Fixed            | Positioned relative to the browser window. It remains fixed in its position even when the page is scrolled.                                              |

Relative positioning shifts an element from its original position, while absolute positioning places it relative to its closest positioned ancestor. Fixed positioning positions the element relative to the browser window, remaining fixed during scrolling.


**[⬆ Back to Top](#table-of-contents)**

---


### What is Flexbox 

Flexbox is a CSS layout model that provides a more efficient way to design and align elements in a container, allowing for flexible and dynamic responsive layouts.


**[⬆ Back to Top](#table-of-contents)**

---


### What is Box Model in CSS

The CSS box model is a set of rules that define how elements are displayed on a website, including their boundaries, spacing, and parameters. It represents each element in a document as a rectangular box, made up of four parts or areas:

1. Content box: The area where content is displayed
2. Padding box: White space around the content
3. Border box: Wraps the content and any padding
4. Margin box: The outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements


**[⬆ Back to Top](#table-of-contents)**

---


### What is Box Sizing Property

Box-sizing enables you to define how you want the height and width of an element to be calculated. It means that you can use this property to specify whether the padding or border of the element should be included in the height and width or not.


**[⬆ Back to Top](#table-of-contents)**

---


### What is different between Content Box and Border Box

| Property           | Content Box                                        | Border Box                                                     |
| ------------------ | -------------------------------------------------- | -------------------------------------------------------------- |
| Description        | Refers to the area inside the element's border.    | Refers to the area including the element's padding and border. |
| Width Calculation  | Width is calculated excluding padding and border.  | Width is calculated including padding and border.              |
| Height Calculation | Height is calculated excluding padding and border. | Height is calculated including padding and border.             |
| Total Size         | Total size does not include padding or border.     | Total size includes padding and border.                        |

Content Box represents the area inside the element's border, while Border Box represents the area including the element's padding and border. Width and height calculations differ between the two, affecting the total size of the element.


**[⬆ Back to Top](#table-of-contents)**

---


### What is Media Query 

A media query in CSS allows you to apply styles based on the characteristics of the device or viewport, such as screen size, resolution, orientation, or color scheme, enabling responsive design.


**[⬆ Back to Top](#table-of-contents)**

---


### What is CSS preprocessor Sass 

Sass (Syntactically Awesome Style Sheets) is a CSS preprocessor that extends CSS with features like variables, nesting, mixins, and functions, making stylesheets more maintainable and efficient to write and manage.


**[⬆ Back to Top](#table-of-contents)**

---


### What is the default value of Position Property

The default value of the `position` property in CSS is `static`. Elements with `position: static` are positioned according to the normal flow of the document, without any special positioning. They are not affected by the top, bottom, left, or right properties, nor by z-index.


**[⬆ Back to Top](#table-of-contents)**

---


### 


**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---
**[⬆ Back to Top](#table-of-contents)**

---

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊

---
