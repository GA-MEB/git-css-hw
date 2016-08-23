[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Homework : Using Git, Continued

<!-- MATERIALS METADATA -->
<!--
  title: 'Using Git, Continued'
  type: homework
  duration: ??
  creators: Matt Brendzel
  competencies: git, html
-->

## Directions

Just like yesterday, you will be implementing a series of changes to a website,
and making commits after each one. Also just like yesterday, you **must** use
`git commit` rather than `git commit -m` to make your commits, and you should
try as much as possible to adhere to the [Commit Guidelines](./commit-guidelines.md).

Some HTML files have been provided for you to start off with -- these should
roughly match what you submitted yesterday.

Ready? Let's get started.

1.  Create a CSS file called `main.css` and link to it from `index.html`,
    `about.html`, and `product-page-01.html`.

2.  Set all the text content in the page to be center-aligned. (Hint: Is there a
    simple way to do this?)

3.  Set the image found [here](https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/Railway_workshop_museum_exhibition_in_Ljubljana%2C_Slovenia.jpg/1024px-Railway_workshop_museum_exhibition_in_Ljubljana%2C_Slovenia.jpg)
    as the background of the page, and have it cover the entire page.

4.  Set some default font properties for the document: 'Lucida Sans' (a member
    of the 'sans-serif' font family) with a size of 20px.

5.  Give the main section of the page a text color of `#dddddd`, with a
    translucent background (white, at 60% opacity). Style the `<article>` and
    `<h2>` in `about.html` the exact same way.

6.  Apply those same properties to the top-level heading. Additionally, give the
    top-level heading a 'bolder' font weight and a font size of 45 pixels.

7.  Go over to `product-page-01.html`. Suppose that we want all of the
    checkboxes and buttons in the form (but nothing else) to have the same
    color, size, and font. Define a class accomplish this; make all of that text
    blue, in the 'Impulse' font (sans-serif family).

8.  Whoops, new request from marketing! Apparently the submit button, which they
    keep calling a 'call to action', isn't big enough or eye-catching enough.
    They want the button to be bright red, and for the text to be big (50px or
    more). Use either an ID or another class to make those modifications.

9.  Hmmm. That blue text color is clashing with our new red background -- lets
    make that button text white instead.

10. Lastly, let's do something to make all of those links look nicer. Make it so
    that all linkshave black text; then, make it so that the link inside the nav
    bar of `index.html` and the 'back' buttons in `about.html` and
    `product-page-01.html` have the same translucent background as the headings,
    _without changing anything else_. Accomplish this in whatever way you think
    is best.

As before, you will probably need to consult a reference to figure out exactly
how to implement these steps. Fortunately, both the
[MDN](https://developer.mozilla.org/en-US/docs/Web/CSS) and
[W3Schools](http://www.w3schools.com/css/default.asp)
have content on CSS. Another good resource is
[CSS-Tricks.com](https://css-tricks.com/).

### Reach Targets

> NOTE: Do not attempt until every other objective is met.

It's possible to completely sidestep needing classes and IDs in this
example by using more complex selectors in your CSS rules. Can you
figure out how? Take a look at the references above for hints.

Make a commit after refactoring your CSS to use these more advanced selectors.

## Submission

Push your code up to GitHub `git push origin master`) once you finish your work,
and then create an issue on the `wdi-remote-r2d2` repo as you did before.

Remember, the title should be "YourGitHubUsername -- Week XX Day XX", and it
should contain a link that points to the repo on GitHub that holds your work and
a 'comfort' score from 1 to 5 indicating how comfortable you feel with the
material.
