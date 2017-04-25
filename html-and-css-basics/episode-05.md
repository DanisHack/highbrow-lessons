# Episode #5 of 10 - The Head

As we mentioned in lesson one, the head contains elements that are not necessarily displayed on the actual webpage. The head element can contain the webpage title, metadata, styles, scripts, and more. Let’s add some code to the head of our hello-world.html webpage:

> View, copy, and play with this code on CodePen at http://codepen.io/kimlarocca/pen/OMqzby

## The Title Element

While not required in HTML5, the title element should never be left out. The text inside the `<title>` start tag and `</title>` end tag defines the title of your webpage, which should be no more than 70 characters. This will be displayed on your browser tab, when you bookmark a page, or when someone shares your page on their social network. The `<title>` element is extremely important for search engine optimization. For example, Google will display your webpage’s title in the search results and will use keywords in the title to rank your webpage.

## Metadata

The `<meta>` tag contains data about your webpage. We included some common examples of metadata on our hello-world.html webpage. Here is a breakdown of the metadata code:

```html
<meta charset="UTF-8">
```

The metadata on line 6 defines the character encoding for your webpage. The charset attribute tells the web browser that you want to use UTF-8 (Unicode) encoding. If you fail to define a character set, then the web browser will use the default encoding on the user’s machine, and some of your characters may render improperly.

```html
<meta name="description" content="An example of a basic webpage.">
```

It’s a good idea to write meaningful descriptions for all your webpages. On line 7, the value of the content attribute (in this case "An example of a basic webpage.") will be displayed on your webpage’s search results under the title of the page. While it is not a search engine ranking factor, it may convince a user to click on your link. The content should be no longer than 215 characters.

## The Link Element

The link element is most commonly used to link to an external CSS (cascading style sheet) document. On line 8, `<link rel="stylesheet" href="style.css">` tells the web browser to load the our external style sheet document style.css and that the document is a "stylesheet."

##  Script and Style Elements

You can also include CSS and Javascript code right in the head of your HTML document instead of linking to external resources, although that is not the best practice.
