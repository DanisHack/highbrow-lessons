# Episode #7 of 10 - Creating a Basic HTML5 Layout

Let's design a typical blog page by adding some code inside your webpages `<body>` tags!

First, we will define a header on your site, which typically comprises the website title/logo and main navigation:

> View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/adxoox

With HTML5, you can use the `<header>` tag to start the header of your webpage (line 12). On line 13, you’ll notice a comment in the code. You can use comments to leave yourself notes or help others figure out what you are doing. Anything inside <!-- and --> will be ignored by the web browser.

On line 14, we have our webpage title inside the `<h1></h1>` tags, followed by our main navigation on lines 16-23. With HTML5, you can use the nav element for your navigation. Inside the `<nav></nav>` tags we have an unordered list `<ul></ul>` with some list items `<li></li>`. Each link in our navigation will be a separate list item in our unordered list.

On lines 27-29, we have the code for a “hero" image, a popular trend in web design.

In HTML5, you can use the section element to define a new section of your website. You’ll notice that we have added an attribute to the `<section>` tag: `id="hero"`. This will help us target just the hero image section later when we style the page with CSS. Inside the `<section></section>` tags is the code to display the actual hero image.

On lines 32-42, we have a new section on our webpage where we will display some articles.

You can see that we have given this section a different ID than the previous section to help us target just the articles section with CSS. For this section, we are using `id="articles"`. In HTML5, you can use the article element to define an article on your webpage. Inside each article element, we will have a subheader (i.e., the title of the article) and a paragraph. You’ll see that we have included two articles on our webpage by repeating the first block of code on lines 34-37.

Finally, on lines 47-49, we have the footer of our webpage.

With HTML5, you can use the footer element to define a footer on your webpage. We have kept it simple by including a paragraph inside the `<footer></footer>` tags with a copyright notice and link—information that is typical on most websites.

## Our webpage so far...

Here is a preview of what our webpage should look like. It may look a little boring right now, but in the next lesson, we will add some styles to spice it up!

> View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/adxoox
