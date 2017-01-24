# CSS Selectors Practices

## Nature Drawing 101: Draw a Tree! - [solution](solution.md)
1. Draw the structure (DOM tree) of the following HTML document:

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>My Site</title>
  </head>
  <body>
    <header>
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
    </header>

    <section>  
      <h1>Welcome to my site!</h1>
      <img src="/static/say_cheese.jpg">
      <p>Words and <a href="/">links</a></p>
    </section>

    <footer>
      <small>Copyright 2015 Jon Doe.</small>
    </footer>
  </body>
</html>
```

* How many children does `header` have?
* Name a direct child of the `p` element.
* Name a direct parent of the `p` element
* What is the parent of the `html` element?

## CSS Selector Challenge - [solution](solution.md)
Please refer to [this google doc](https://docs.google.com/document/d/1sKbuZaSio1o65iRdkNpB03pwJfJj98GPHUJQsoKJmE4/edit?usp=sharing).

For each page, come up with as many CSS Selectors as you can think of to select the html elments in **red**, and *only* the elements in red.

#### Advanced CSS Selectors
For practice with some of the more obscure selectors, see [CSS Diner](https://flukeout.github.io/).

## Class Based CSS Rules
For this challenge we recommend you clone the following [blank template](https://github.com/SF-WDI-LABS/blank_template).

Create the following CSS rules:

1. `.shout` changes text to be in all capital letters (as if you're shouting)
1. `.img-circle` crops an image to be a circle.
    ![img-circle](https://cloud.githubusercontent.com/assets/1489337/22270271/a8c466fa-e243-11e6-8457-72460378a30e.png)
1. `.img-thumbnail` adds rounded corners and an inset border to an image.
    ![img-thumbnail](https://cloud.githubusercontent.com/assets/1489337/22270292/b57544c8-e243-11e6-95c6-bf486eb5f731.png)
1. `.success`, `.info`, `.warn`, `.danger` - recreate the following effects on a block of text:
    ![alerts-all](https://cloud.githubusercontent.com/assets/1489337/22269495/6c044f80-e240-11e6-9de6-226b4beb9e45.png)
1. `.container` elements with this style should have a maximum width of 800px, and be in the middle/center of the page.
1. `.half-width`, `.third-width` -- elements with this style should take up only half or a third of the width of a page (and ideally they should be able to line up next to each other, e.g. like columns).

As you move through this challenge, you will need to write HTML to test your CSS. For example, for the first challenge (`.shout`), you would want to write something like:

```html
<h1 class="shout">why are you shouting at me?</h1>
```
