---
layout: layout.njk
title: </> htmx - high power tools for html
---

## The `debug` Extension

This extension includes log all htmx events for the element it is on, either through the `console.debug` function
or through the `console.log` function with a `DEBUG:` prefix.

### Install

```html
<script src="https://unpkg.com/htmx.org/dist/ext/debug.js">
```

### Usage

```html
<button hx-ext="debug">Debug Me...</button>
```
