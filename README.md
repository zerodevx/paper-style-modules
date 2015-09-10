# `<paper-style-modules>`

A style-module version of PolymerElements' `<paper-styles>` that's compatible
with Polymer 1.1+.

This is just a quick conversion of PolymerElements' paper-styles' classes in
~5 mins.


### Let's get this money

Basic usage:

```html
<link rel="import" href="bower_components/paper-style-modules/paper-styles-global.html">
<link rel="import" href="bower_components/paper-style-modules/paper-styles-layout.html">
<link rel="import" href="bower_components/paper-style-modules/paper-styles-shadow.html">
<link rel="import" href="bower_components/paper-style-modules/paper-styles-typography.html">

<dom-module id="my-element">
  <template>
    <style include="paper-styles-global"></style>
    <style include="paper-styles-layout"></style>
    <style include="paper-styles-shadow"></style>
    <style include="paper-styles-typography"></style>
    <style>
      /* My other element styles */
    </style>

    ...
  </template>
</dom-module>

<script>
  Polymer({
    is: "my-element",
    ...
  });
</script>
```

### Installation

Install through bower.

    bower install --save zerodevx/paper-style-modules#style-modules






