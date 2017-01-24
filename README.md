# CSS Selectors Practices

#### Nature Drawing 101: Draw a Tree! - [solutions](solutions.md)
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

#### CSS Selector Challenge - [solutions](solutions.md)
Please refer to [this google doc](https://docs.google.com/document/d/1sKbuZaSio1o65iRdkNpB03pwJfJj98GPHUJQsoKJmE4/edit?usp=sharing).

For each page, come up with as many CSS Selectors as you can think of to select the html elments in **red**, and *only* the elements in red.

For practice with more advanced/obscure selectors, see [CSS Diner](https://flukeout.github.io/).

#### Class Based CSS Rules

1. `.shout` changes text to be in all capital letters (as if you're shouting)
1. `.avatar` make an image appear round, with a thin border or shadow. Limit its height to about 40px.
1. `.success`, `.info`, `.warn`, `.danger` - recreate the following effects on a block of text:
   ![alerts-all](https://cloud.githubusercontent.com/assets/1489337/22269495/6c044f80-e240-11e6-9de6-226b4beb9e45.png)
1. `.container` elements with this style should have a maximum width of 800px, and be in the middle/center of the page.
1. `.half-width`, `.third-width` -- elements with this style should take up only half or a third of the width of a page (and ideally they should be able to line up next to each other, e.g. like columns).

