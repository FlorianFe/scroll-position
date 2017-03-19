# \<scroll-position\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/florianfe/scroll-position)

Simply place an element inside an element you want to track the vertical scroll position of. The scroll position is a value between 0 and 100 and stored in the "value"-property of the element.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

<!--
```
<custom-element-demo>
  <template is="dom-bind">

    <link rel="import" href="scroll-position.html">
    <link rel="import" href="https://polygit.org/components/polymer/polymer.html">
    <link rel="import" href="https://polygit.org/components/paper-progress/paper-progress.html">

    <style is="custom-style">

      .container
      {
        height: 300px;
        overflow: scroll;
        text-align: center;
      }

      paper-progress
      {
        width: 100%;
      }

    </style>

    <div class="container">
      <scroll-position value="{{value}}"></scroll-position>
      <img src="http://lorempixel.com/1080/1920" />
    </div>

    <br><br>

    <paper-progress value="[[value]]"></paper-progress>
  </template>
</custom-element-demo>
```
-->

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
