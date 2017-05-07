---
title: Essential Documentation
description: Links to essential documentation and other references on the use and state of web standards.
---

There’s plenty of bad documentation on the web. This page will point you only to the most reliable sources.

### [Mozilla Developer Network](https://developer.mozilla.org/en-US/)

The [MDN](https://developer.mozilla.org/en-US/) documentation is practically an industry standard,
and most pages offer links to relevant specifications.

* [MDN HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference)
* [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
* [MDN JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

### [HTML Dog](http://htmldog.com/)

An accessible reference that’s useful for beginners look to clarify points of confusion. For
example, their entry for [``<section>``](http://htmldog.com/references/html/tags/section/) opens
with a very succinct description.

* [HTML Dog HTML Reference](http://htmldog.com/references/html/)
* [HTML Dog CSS Reference](http://htmldog.com/references/css/)

### [Can I Use...](https://caniuse.com/)

[Can I Use...](https://caniuse.com/) is a well respected and frequently updated reference for the state of stadards support in different browser. The site takes a search term and presents a table of browser support, such as [for the `rem` unit](https://caniuse.com/#feat=rem).

Remember that even though the latest browsers all support a unit like `rem`, there are still older browsers in wide circulation. So look at feature detection scripts for `rem` units, like [Modernizr’s](https://modernizr.com/download?cssremunit-setclasses), or well documented fallbacks, like [specifying a pixel value for older IE](https://snook.ca/archives/html_and_css/font-size-with-rem)—while understanding that that fallback will prevent text-zooming for IE users.

### [CSS Tricks](https://css-tricks.com/)

Although I’m always suspicious of sites with words like *tricks* in their name, CSS Tricks is an
indispensable resource. For example, their page on
[CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) is an important visual
reference.

Do note that some of the HTML in CSS Tricks’s examples can be suspect and outdated, so bring your
own semantic HTML to bear on whatever CSS advice they offer.
