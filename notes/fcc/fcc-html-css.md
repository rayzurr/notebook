---
title: "N/A"
status: "N/A"
order: N/A
---

# Main Title

#### The ultimate guide to *RENAME* 

//Insert Summarised Introduction/Description

> *INSERT CALLOUT:)*

## Resources

Here are some links you might find helpful!

- [Flex Box](https://flexboxfroggy.com/)

* **GitHub** -> https://www.github.com

## Table of Contents

  - [Chapter 1 - Introduction to HTML](#chapter-1---introduction-to-html)
    - [1.1 Creating an HTML Document](#11-creating-an-html-document)



## Chapter 1
 ### Learn HTML by Building a Cat Photo App
### Learn Basic CSS by Building a Cafe Menu
### Learn CSS Colors by Building a Set of Colored Markers

**RGBA (Red, Green, Blue, Alpha)**

* Used for digital displays like webpages.
* Represents colors by mixing Red, Green, and Blue values (0-255).
* Includes an Alpha channel (0.0 to 1.0) to define opacity (transparency). 
* Example: `rgba(255, 0, 0, 0.5)` is red with 50% opacity.

**HSL (Hue, Saturation, Lightness)**

* More intuitive for human understanding.
* Hue (0-360 degrees) represents the color itself (e.g., red, green, blue).
* Saturation (0-100%) defines the color intensity (0% is gray, 100% is full color).
* Lightness (0-100%) controls how light or dark the color is.
* Example: `hsl(0, 100%, 50%)` is a bright red.

**HEX (Hexadecimal)**

* Compact notation for RGB values.
* Uses a 6-digit code preceded by # (e.g., #FF0000 for red).
* Each digit represents the Red, Green, and Blue values (0-F).
* Doesn't support transparency.
* Example: `#FFCC33` is a light orange.
* 4D means (4(invisible 16) + D) = (64 + 13) = 77 // 16 means hexdecimal
* With the exception of FF = means 15 x 15 ??

**Choosing the right format:**

* Use RGBA for digital colors with transparency.
* Use HSL for easier color adjustments based on human perception.
* Use HEX for brevity and compatibility with older systems (though transparency isn't possible).


### Learn HTML Forms by Building a Registration Form
    * Survey Form (Certification Project)

## Chapter 2
### Learn the CSS Box Model by Building a Rothko Painting

- Imagine the Box Model analogy = item/bubblewrap/box/space between other boxes
content/padding/div/margin

- What is boxing size?
  - The border-box sizing model does the opposite of content-box. The total width of the element, including padding and border, will be the explicit width set. The content of the element will shrink to make room for the padding and border.

- What is `object-fit:cover` property?
  Determines how the image behaves i.e enables correct aspect ratio

### Learn CSS Flexbox by Building a Photo Gallery

- Done
- 
### Learn Typography by Building a Nutrition Label

- Done
### Learn Accessibility by Building a Quiz 

A useful property of an SVG (scalable vector graphics) is that it contains a path attribute which allows the image to be scaled without affecting the resolution of the resultant image.

Currently, the img is assuming its default size, which is too large. CSS has a max function which returns the largest of a set of comma-separated values. For example:

img {
  width: max(250px, 25vw);
}
In this example, img elements will have a minimum width of 250px. And as the viewport grows, the image will grow accordingly to be 25 percent of the viewport width.

- 'role' attribute is used to help screen readers users understand and navigate.


- label element and input element are often paired together within when used in forms. Label will have a `for = {name1}` attribute & input will have `id={name1}`. They must have matching 

- Keeping in mind best-practices for form inputs, give each input an appropriate type and name attribute. Then, give the first input a placeholder attribute.
### Tribute Page (Certification Project)

## Chapter 3
### Learn More About CSS Pseudo Selectors by Building a Balance Sheet

![Project Image](image.png)

- `Table` element is paired with the child element of `caption`. Caption will indicate what the table is about. 

- `thead` and `tbody` elements are used to indicate which portion of your table is the header, and which portion contains the primary data or content.

- The `tr` element is used to indicate a table row. The `td` element indicates a data cell, while the `th` element indicates a header cell.

- `:first-of-type` pseudo-selector is used to target the first element matches the selector and conversely `:last-of-type`

- The [attribute="value"] selector targets any element that has an attribute with a specific value.

- The key difference between tr[class="total"] and `tr.total` is that the first will select tr elements where the **only** class is total. The second will select tr elements where the class **includes** total.

- Done

### Learn Intermediate CSS by Building a Cat Painting


![Cat Photo Project](<Screenshot 2024-04-19 at 6.51.20 pm.png>)

- `position` property you can set to **static, absolute, relative, sticky or fixed**. Once you set the position property of the element, you can move the element around by setting a pixel or a percentage value for one or more of the top, right, left, or bottom properties.

- `static` is the default positioning for all elements. If you assign it to an element, you won't be able to move it around with top, right, left, or bottom.


- `sticky` position property is a mix of relative and fixed positioning


*{
  border: 1px solid red;
  z-index: -1 !important
}
### Learn Responsive Web Design by Building a Piano

![piano](image.png)
    * Technical Documentation Page (Certification Project)

- `boxing sizing : inherit` which will tell the targeted elements to use the same value as the parent element.

-`@media at-rule`, media query, is used to conditionally apply CSS. Media queries are commonly used to apply CSS based on the viewport width using the `max-width` and `min-width `properties. 

  - You can use the `and` operator to combine media queries

- `overflow: hidden` will hide any content that overflows outside of the width value

- done

## Chapter 4
### Learn CSS Variables by Building a `City Skyline

- ![Building CSS](<Screenshot 2024-04-21 at 2.57.26 pm.png>)

- Variables are created in CSS using `--variable--`

To use a variable, var and parenthese `var(--variable-name)`. ie
`background-color: var(var(--variable-name)`

- `var(--variable-name, fallback-value)`
 incase there issue it will use the fallback value

- Done
### Learn CSS Grid by Building a Magazine
    * Product Landing Page (Certification Project)

![magazine1a
](4-fcc-magazine-1.png)

![magazine1b
](4-fcc-magazine-1a.png)

- `rel: referrer` is used to track analytics on people who click on a tag link. Conversely `noreferrer` 

- Gridbox layout of a chessboard. Each tile is a grid.

- `display: flex` & `grid-template-columns: ` are the properties to use grid;

- grip template can use `minmax` as a arguement. This determines the min and max width size of grid.

-  `row-gap` property add spaces to the rows

- `grip column` is a sub-property of `grid-template-columns: ` and applies to the child elements of the main property. 

- What if you wanted to add more columns with disrupting your grid?
  1. Addition columns
  2. Use `grid-auto-flow`


- `grid-auto-flow` takes either row or column as the 1st arg, with an optional 2nd arg of `dense`. This property will auto fill the spaces The `dense` value allows the algorithm to backtrack and fill holes in the grid with smaller items, which can result in items appearing out of order.

- grid-column property, which is shorthand for grid-column-start and grid-column-end tells the grid item which grid line to start and end at.

- `hero` is the superman of the page

- The `object-fit` property tells the browser how to position the element within its container. In this case, cover will set the image to fill the container, cropping as needed to avoid changing the aspect ratio.



- How do you make your #nav-bar always be at the top of the viewport?
  - #nav-bar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 100;
  }

- done

# Chapter 5
### Learn CSS Animation by Building a Ferris Wheel
### Learn CSS Transforms by Building a Penguin
    * Personal Portfolio Webpage (Certification Project)