[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/daKmoR/grain-responsive-container)
[![Polymer Version](https://img.shields.io/badge/polymer-v2-blue.svg)](https://www.polymer-project.org)

# \<grain-responsive-container\>

Allows you to easily define is-mobile, is-tablet, is-desktop for your element so you can style it accordingly.

## Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="grain-responsive-container.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<style>
  grain-responsive-container {
    --background: #FFFAA5;
    --tablet-background: #ABFF8A;
  }
  grain-responsive-container[is-tablet] {
    border: 1px solid #E76C4A;
  }
</style>
<grain-responsive-container>
  I will be yellow on desktop and green on tablet just by using css variables.
  For everything else I can use the is-mobile, is-tablet, is-desktop attribute of the element. 
</grain-responsive-container>
```

## Installation

```sh
$ bower install --save daKmoR/grain-responsive-container
```

## Getting Started

Import the package.

```html
<link rel="import" href="/bower_components/grain-responsive-container/grain-responsive-container.html">
```

*For more information, see the API documentation.*

## Working on the Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
* View the Element via `polymer serve`
* Run tests via `polymer test`
