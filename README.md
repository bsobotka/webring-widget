# webring-widget

Webring Widget and [other scripts](https://reisir.github.io/webring-widget/examples.html) for the [AMV Sashimi Webring](https://amvsashimi.neocities.org/). 

Only works on browsers that support JS modules, so most browsers after mid 2018

# Usage

1. Add this snippet in the HTML of your site:

```html
<webring-widget>
  <script
    type="module"
    src="https://reisir.github.io/webring-widget/scripts/widget.js"
    defer
  ></script>
</webring-widget>
```

2. Add the stylesheet to your `<head>` or make your own `<style>` for the widget

# Styling the widget

a [base stylesheet](styles/widget.css) is available, you can include it on your site or use it as a base to write a style for the widget yourself. It's recommended to at least add the base stylesheet as it automatically centers the widget in it's container and adds some padding between the elements.

Add the stylesheet to the end of your `<head>`:

```html
<head>
  <!-- the other stuff -->
  <link
    rel="stylesheet"
    href="https://reisir.github.io/webring-widget/styles/widget.css"
  />
</head>
```

# Joining the webring

Edit [scripts/sites](./scripts/sites.js) and create a push request. Or ask me on discord.

# Extra

You can see all of these in action on the [examples](https://reisir.github.io/webring-widget/examples.html) page

## List all the sites in the webring

```html
<ul id="webring-list">
  <script
    type="module"
    src="https://reisir.github.io/webring-widget/scripts/list.js"
    defer
  ></script>
</ul>
```

a [base stylesheet](styles/list.css) is available for the list, you can include it on your site or use it as a base to style the list yourself

```html
<link
  rel="stylesheet"
  href="https://reisir.github.io/webring-widget/styles/list.css"
/>
```

## Table of all the sites in the webring

```html
<table id="webring-table">
  <script
    type="module"
    src="https://reisir.github.io/webring-widget/scripts/table.js"
    defer
  ></script>
</table>
```

a [base stylesheet](styles/table.css) is available for the table, you can include it on your site or use it as a base to style the table yourself

```html
<link
  rel="stylesheet"
  href="https://reisir.github.io/webring-widget/styles/table.css"
/>
```

## Button to go to a random site (excluding the current site) on the webring

```html
<button id="random-site">Random Site</button>
<script
  type="module"
  src="https://reisir.github.io/webring-widget/scripts/random.js"
  defer
></script>
```
