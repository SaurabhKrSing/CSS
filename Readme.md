# CSS Interview Questions & Answers

### Table of Contents

| Questions                                                                             |
| ------------------------------------------------------------------------------------- |
| [What is CSS](#what-is-CSS)                                                           |
| [Why do we use CSS](#Why-do-we-use-CSS)                                               |
| [Advantages and Disadvantages of CSS](#Advantages-and-Disadvantages-of-CSS)           |
| [Feature of Java 8](#Feature-of-Java-8)                                               |
| [What is Platform](#What-is-Platform)                                                 |
| [What is Platform Independence](#What-is-Platform-Independence)                       |
| [Why we use static in Main Method in java](#Why-we-use-static-in-Main-Method-in-java) |

### What is CSS

CSS, or Cascading Style Sheets, is a stylesheet language used to control the presentation and layout of web pages written in HTML and XML. It enables the separation of document content from presentation, allowing designers to style elements with properties such as color, layout, and typography for enhanced visual aesthetics.

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

S.No.

CSS

CSS3

1 CSS is capable of positioning texts and objects. CSS is somehow backward compatible with CSS3. On the other hand, CSS3 is capable of making the web page more attractive and takes less time to create. If you write CSS3 code in CSS, it will be invalid.
2 Responsive designing is not supported in CSS CSS3 is the latest version, hence it supports responsive design.
3 CSS cannot be split into modules. Whereas, whereas CSS3 can be breakdown into modules.
4 Using CSS, we cannot build 3D animation and transformation. But in CSS3 we can perform all kinds of animation and transformations as it supports animation and 3D transformations.
5 CSS is very slow as compared to CSS3 Whereas, CSS3 is faster than CSS.

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

Inline CSS: Inline CSS contains the CSS property in the body section attached with the element known as inline CSS. This kind of style is specified within an HTML tag using the style attribute.
Internal or Embedded CSS: This can be used when a single HTML document must be styled uniquely. The CSS ruleset should be within the HTML file in the head section i.e the CSS is embedded within the HTML file.
External CSS: External CSS contains a separate CSS file which contains only style property with the help of tag attributes (For example class, id, heading, … etc). CSS property is written in a separate file with .css extension and should be linked to the HTML document using the link tag. This means that for each element, style can be set only once and that will be applied across web pages.

**[⬆ Back to Top](#table-of-contents)**

---

### Which type of CSS holds the highest priority

Inline CSS has the highest priority, then comes Internal/Embedded followed by External CSS which has the least priority. Multiple style sheets can be defined on one page. If for an HTML tag, styles are defined in multiple style sheets then the below order will be followed.

As Inline has the highest priority, any styles that are defined in the internal and external style sheets are overridden by Inline styles.
Internal or Embedded stands second in the priority list and overrides the styles in the external style sheet.
External style sheets have the least priority. If there are no styles defined either in the inline or internal style sheet then external style sheet rules are applied for the HTML tags.

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

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊

---
