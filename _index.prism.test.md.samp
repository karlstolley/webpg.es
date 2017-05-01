---
title: How to Design and Write Web Pages Today
description: Companion site for How to Design and Write Web Pages Today, 2nd Edition.
bodyclass: home
---

Here comes some content.

### Headings Are Nice!

Wonder how [the source](#the-source) will be laid out. I’m guessing the block-level indents will not be preserved.

Let’s see some source code:

```markup
<!DOCTYPE html>
<html lang="en">
  <header id="header">
    <h1><a href="http://webpg.es/" rel="home">webpg.es</a></h1>
    <p class="tagline">
      Companion site for
      <cite>How to Design and Write Web Pages Today</cite>,
      2nd edition
    </p>
    <nav id="navigation">
      <ul class="navigation">
        <li class="accessibility"><a href="#content">Skip to page content</a></li>
        <li><a href="/">Home</a></li>
        <li><a href="/about/">About</a></li>
      </ul>
    </nav>
  </header>
```

Hey, how about some JavaScript?

```javascript
function loadjQuery() {
  var jQ;
  if (window.jQuery) {
    return pageSetup();
  }
  let num = 2000;
  let loggedIn = true;
  else {
    jQ = document.createElement("script");
    jQ.src = jQueryURL;
    jQ.onload = jQ.onreadystatechange = pageSetup;
    // Log an error if jQuery fails to load from the URL
    // specified:
    jQ.onerror = function() {
      console.log("Unable to load jQuery from", jQueryURL);
    };
    return document.body.appendChild(jQ);
  }
}
```

And you know some CSS would be awesome, too:

```css
html {
  text-rendering: optimizeLegibility;
  -webkit-text-size-adjust: 100%;
  -moz-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
  text-size-adjust: 100%;
}
h1 a {
  color: #ff609d; /* pink*/
  color: #80c2ff; /* blue */
  color: #c1ce67; /* green */
  color: #d4fd00; /* rev sat green */
  color: #e7fd74; /* rev desat green */
}
nav,
footer[property^="dc"],
.tagline {
  font-family: "Aptifer Sans W04"; !important
}
.tagline {
  position: absolute;
  left: -10000px;
}
.home .tagline {
  position: static;
}
/* Responsive Media */
audio,
img,
video {
  display: block;
  max-width: 100%;
}
picture img {
  width: 100%;
}

@media screen and (min-width: 600em) {
  /* Typical bold and italic styles */
  b,
  strong {
    font-weight: bold;
  }
  i,
  em,
  cite {
    font-style: italic;
  }
}
```

And how about the terminal? Everyone loves the terminal:

```txt
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   _layouts/default.html
	modified:   about/index.md
	modified:   assets/css/print.scss
	modified:   assets/css/screen.scss
	modified:   assets/js/site.js
	modified:   index.md

no changes added to commit (use "git add" and/or "git commit -a")
```

And how about some Haml?

```haml
!!!5
%html{lang: 'en'}
  %head
  %body.home
    %header#header
```

And hey, everyone loves Ruby!

```ruby
class SessionsController < ApplicationController
  def create
    render text: request.env['omniauth.auth'].to_yaml
  end

  def destroy
  end
end
```
