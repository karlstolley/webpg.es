---
title: Tools and Setup
description: Setup instructions and links to essential, open-source software for web development.
---

Software and setup instructions can change quickly, which is why specifics weren’t included in the book. Here are the basics to get yourself up and running quickly.

### Editors

Here are some recommended plain-text editors to help get you started. All are free software, although the full version of BBEdit requires a license.

* Windows: [Notepad++](https://notepad-plus-plus.org/download/v7.3.3.html)
* macOS: [BBEdit](http://www.barebones.com/products/bbedit/download.html). Note that BBEdit replaces TextWrangler, which was mentioned in the book. The full BBEdit may be used for a 30-day evaluation period, after which “you can continue to use BBEdit for free, forever, with no nag screens or unsolicited interruptions,” according to [Bare Bones Software’s website](http://www.barebones.com/products/textwrangler/).
* All Platforms: [Atom](https://atom.io/), a text editor written by a team at GitHub. This editor is very popular with my students.

### Browsers

[Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) is my browser of choice for development purposes. I usually add to it [Chris Pederick’s Web Developer Add-on](https://addons.mozilla.org/firefox/addon/web-developer/), which is [also available for Chrome](https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm), if you prefer to develop or test sites in [Google Chrome](https://www.google.com/chrome/).

### Node.js

[Node.js]() is that you can use to run multiple tools, including the command-line `http-server` development server to test your website.

While there are [standalone installers for Node.js](https://nodejs.org/en/download/) on all operating systems, macOS and Linux users should consider using a package manager to install Node.js. Linux will already have a package manager, but macOS requires you to install one. [Homebrew](https://brew.sh/) is my macOS package-manager of choice; if the instructions on that page do not work on your version of macOS/OS X, there are additional [installation instructions](https://github.com/Homebrew/brew/blob/master/docs/Installation.md#installation) that you can consult.

With a package manager like Homebrew, installing Node.js just requires a simple terminal command:

```txt
$ brew install node
```

``brew`` is the name of the package manager. On Linux, that might be `apt`, `yum`, `pacman`, or whatever the package manager of choice is on your Linux distribution. The advantage of using a package manager is that you can easily update all of your installed software later. For example, to upgrade all of your Homebrew-installed packages, run:

```txt
$ brew update
$ brew upgrade
```

Node.js includes the Node Package Manager (npm), which can be used to install Node.js packages. Run `npm` on the command line to install the package you need. For example, to install the [http-server](https://www.npmjs.com/package/http-server) package, you would run:

```txt
$ npm install -g http-server
```

The ``-g`` part instructs npm to install the http-server package globally, so that you can use it in any directory where you’re working on a website. **Note that, depending on how you’ve installed Node, you may have to prefix the command with `sudo`, which will then prompt you for your administrative password:**

```txt
$ sudo npm install -g http-server
```

The npm documentation [offers several workarounds](https://docs.npmjs.com/getting-started/fixing-npm-permissions) for installing Node.js packages globally without having to use `sudo`.

Here are some recommended packages to start with:

* [http-server](https://www.npmjs.com/package/http-server): A simple, zero-configuration web server for development purposes. Install by running `npm install -g http-server`
* [htmllint](https://www.npmjs.com/package/html-lint): A basic but effective HTML linter. Install by running `npm install -g htmllint`
* [stylelint](https://www.npmjs.com/package/stylelint): A solid CSS linter. Install by running `npm install -g stylelint`
* [ESlint](https://www.npmjs.com/package/eslint): A very powerful JavaScript linter. Install by running `npm install -g eslint`

You will need to have configuration files to run htmllint, stylelint, and ESLint. Starter configuration files are all included in [the RPK](/rpk/).
