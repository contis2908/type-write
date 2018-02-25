[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/contis2908/type-write)

# The type-write web-component
This is a Polymer web-component that mimics a type writer effect. <br/>
Feel free to use it in your projects or to fork and contribute to it.

----
### Updates
This Element is currently using Polymer 1 but will be updated shortly to the latest version.

### Features
The type-write element has the following properties available that allow its customization:

1. An array for its text content
2. Character type speed
3. Character deletion speed
4. Time before write
5. Time before deletion
6. Color for cursor & text
7. Cursor type and blinking animation


### Basic Demo
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../polymer/polymer.html">
    <link rel="import" href="type-write.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<type-write text-array='["This is a demo...", "...of the type-write-animation element"]'></type-write>
```
