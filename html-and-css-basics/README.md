# [HTML and CSS Basics](http://gohighbrow.com/portfolio/html-and-css-basics/)

by [Kim LaRocca Henry](http://gohighbrow.com/team/kim-larocca-henry/)

![HTML and CSS Basics](http://gohighbrow.com/wp-content/uploads/2016/11/technology_HTML-and-CSS-Basics-01.png)

Get started with web design! Learn the basic structure of an HTML webpage, how to use common HTML elements, and how to style your page using basic CSS. Build your first webpage, view it in your favorite web browser, and create a website out of several webpages.

---

## Episode #1 of 10 - Intro to HTML

HTML (HyperText Markup Language) is a language used to build webpages and applications. The current version is HTML5. Made up of structured and nested elements, HTML5 provides all the building blocks necessary to create webpages.

Here is the basic structure of an HTML5 webpage:

View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/LGaoyp

You’ll notice that all HTML tags are enclosed by angle brackets <> and for the most part, they come in pairs. When you have a pair of HTML tags, the first one is called the start tag and the second one is called the end tag. They are both the same, except that the end tag has a forward slash before the tag name.

Now that you’ve seen the basic structure, let’s break it down line by line!

**1 `<!doctype html>`**

On our very first line of code, we have the document type definition for HTML5 documents. This line is required.

**2 `<html>`**
On line 2, we have our <html> start tag. This tells the browser that it is reading an HTML document. The `<html>` start tag and `</html>` end tag will enclose all of the other HTML elements on the page.

**3 `<head>`**

On line 3 is our `<head>` start tag. The head contains elements that are not necessarily displayed on the actual webpage. The head element can contain the webpage title, metadata, styles, scripts, and more. We’ll learn more about the head in an upcoming lesson!

**4 `<title>`**
While not required in HTML5, the title element should never be left out. The text inside the `<title>` start tag and `</title>` end tag defines the title of your webpage. This will be displayed on your browser tab, when you bookmark a page, or when someone shares your page on their social network.

**5 `</head>`**
On line 5 we have the `</head>` end tag, which tells the browser that the head element is complete.

**6 `<body>`**
On line 6 is our `<body>` start tag. The body element contains everything that will be visible on your webpage such as text, images, links, and more.

**7 `</body>`**
On line 7, we have the `</body>` end tag, which tells the browser that the body element is complete.

**8 `</html>`**
On line 8, we have the `</html>` end tag, which tells the browser that the HTML element is complete.

## Episode #2 of 10 - Hello World!

Are you ready to build your very first webpage? It is traditional to use the phrase "Hello World" when testing code or when learning a new programming language. Open up any text editor such as Notepad (if you are a PC user) or TextEdit (if you are a Mac user). Make sure you are in **plain text mode** and not rich text mode. For example, in TextEdit, you can go to Format -> Make Plain Text to switch to plain text mode.

Let’s use the following basic HTML5 webpage structure that we learned in lesson one:

View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/vLPZEd

You’ll notice there are a couple changes to our code from lesson one. First, on line 6, we are changing the title of the page to "Hello World!" The other change is adding the text "Hello World!" within the `<body></body>` tags on line 10. Remember, anything you place inside the `<body></body>` tags will be displayed on your web browser when you view the webpage.

That’s it! You have successfully built your first webpage. Save it somewhere on your computer as hello-world.html. Be sure to save it using the .html file extension and not .txt!

### View Your webpage

Now that you have saved your HTML file, it’s time to view your work. Open up your favorite web browser (Chrome, FireFox, Safari, Internet Explorer, etc.) and select the hello-world.html file. Normally you would type in a URL to view a webpage, but in this case, we want to view a local file instead (i.e., a file that only exists on your computer). My favorite web browser is Chrome. To open up a local webpage in Chrome, go to File -> Open File, navigate to your hello-world.html page, select it, and click "open."

You should now see the text "Hello World!" displayed on your web browser. (Tip: If you see the code instead of just the "Hello World!" text, then you failed to save your webpage as a plain text .html file as instructed above). Note the title of the webpage "Hello World!" is displayed on the tab in Chrome and also when you go to bookmark the page.

### View Page Source

The final step in this lesson is to view the source code of the page. Right click anywhere on the page and select "View Page Source" or "Show Page Source." This will open up a new window that displays the source code for your page. You may notice that the browser adds some code to your original code. Knowing this trick is great if you want to view another website’s code and learn more about how they built their webpage.

## Episode #2 of 10 - Headings and Paragraphs

In this lesson, you will learn about headers, subheaders, and paragraphs and see how to add them to your webpages. Let’s build on our hello-world.html page from lesson two:

View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/YwgVPq

You will see that the body element has changed from the previous lesson. The new additions represent some important building blocks for your webpage.

### The H1 Header

On line 10, we have added an `<h1>` header tag to our webpage:

```html
<h1>H1 Header</h1>
```

The H1 header is arguably one of the most important elements you will include within the body of your webpage. The `<h1>` tag is generally used to display the title of the page, and as such, it is typically the largest and most prominent text you see. It is a best practice to only have one `<h1>` tag on any given webpage, and the contents of the `<h1>` tag should be 55 characters or less.

The `<h1>` tag is critical for SEO (search engine optimization). Many SEO experts believe it is the second most important element on the page after the `<title>` tag. While the `<h1>` tag does not necessarily have to match the `<title>` tag, it should contain the important keywords you want your page to rank for on search engines.

### Subheaders

After the `<h1>` tag, you have the ability to use subheader tags that decrease in importance from `<h2>` and `<h3>` all the way down to `<h6>`. On line 11, we have included an example of an H2 subheader:

```html
<h2>H2 Subheader</h2>
```

On line 13, we have an example of an H3 subheader:

```html
<h3>H3 Subheader</h3>
```

Subheader tags should not be used simply to make text big or bold. They should be used as headings for new sections, and they should indicate important information to users and search engines, as both will scan your webpage’s headings to determine if the page is relevant to them. As far as best practice goes, there is no limit on how many subheader tags you can include on your page. Use common sense—not all text on your page is that important, and not all text should be defined as a heading!

### Paragraphs

The `<p>` tag is another common HTML tag that is used to display paragraphs of text on your webpage. We have an example of this on line 12:

```html
<p>This is a paragraph!</p>
```

Another example is on line 14:

```html
<p>This is another paragraph!</p>
```

### Our webpage so far...

Here is a preview of what our webpage should look like!

View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/YwgVPq
