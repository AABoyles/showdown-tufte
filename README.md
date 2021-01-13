# showdown-tufte

*A Showdown Extension to output HTML for use with Tufte-CSS*

## Introduction

[Tufte-CSS](https://edwardtufte.github.io/tufte-css/) is a stylesheet to make it easy to typeset HTML content using Tufte's iconic two-column handout style. But it makes some strong assumptions about the markup that it will be used with, and no markdown compiler is going to meet those assumptions by default. But this extension enables [showdown](http://showdownjs.com/) to generate HTML to be styled by Tufte-CSS.

## Usage

### Get it

* Node: It's on NPM as [`showdown-tufte`](https://www.npmjs.com/package/showdown-tufte).
* Browser: Use unpkg as CDN. `https://unpkg.com/showdown-tufte@1.0.0/index.js`

### From the browser

```js
let md = "<your markdown here>";
let converter = new showdown.Converter({ 'extensions': ['tufte'] });
let html = converter.makeHtml(text);
```

## In action

This extension was originally developed for use in [`uncompiled`](https://aaboyles.github.io/uncompiled/).
