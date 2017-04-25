# Episode #6 of 10 - CSS

In this lesson, you will learn how to use CSS (cascading style sheets) to add styles to your webpage such as colors, font styles, alignments, and much more. It is a best practice to place all your style definitions in a separate .css file, but you can also include them right on your HTML page by using the style element within the head. For simplicity's sake, this is what we will do now.

Let's build on our hello-world.html page from the previous lessons and add a `<style>` tag inside the head:

> View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/GoeMzQ

CSS is composed of a set of rules. Each rule has a selector that identifies the element you are targeting and a block of code inside curly braces { } that contains style definitions for that element.

Place the following CSS code inside your `<style></style>` tags:

Note that the CSS code is separated from the HTML code on CodePen @ http://codepen.io/kimlarocca/pen/GoeMzQ as per best practices.

Let's take a closer look at lines 1-3 of our CSS code. The selector on line 1 is body, so we know that this section of the code will target the body element of our webpage (i.e., everything inside the `<body></body>` tags). Inside our braces `{ }` is a single definition: background-color: lightgray. This tells the web browser to change the background color of the body to light gray from the default color white. When you view the page after adding this rule, you will see that the webpage now has a light gray background color instead of white.

Let's add some styles for the other elements on the page! Here's a breakdown of the rest of our CSS code:

**Lines 4-6**
font-size: 100px tells the web browser to make all the h1 elements on the page 100 pixels large.

**Lines 7-9**
text-align: center tells the web browser to center all the h2 elements on the page (by default, all elements are left-aligned).

**Lines 10-12**
color: red tells the web browser to make all the h3 elements on the page red.

**Lines 13-16**
font-family: Arial tells the web browser to use the Arial font on all the p elements on the page.

**Lines 16-18**
text-decoration: none is a common style for hyperlinks that tells the web browser not to underline the text inside the <a> tags (by default, all links are underlined).

**Lines 19-21**
border: solid 1px tells the web browser to add a one-pixel solid border around all images on the webpage.

## Our webpage so far...

Here is a preview of what our webpage should look like!

> View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/GoeMzQ
