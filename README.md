# The typewrite web-component
This is a Polymer web-component that mimics a type writer effect.
Feel free to use it in your projects or to fork and contribute to it.

----
### Updates
This Element is currently using Polymer 1 but will be updated shortly to the latest version.

### Features
The type-write-animation element has the following properties available that allow its customization:

1. An array for its text content
2. Character type speed
3. Character deletion speed
4. Time before write
5. Time before deletion
6. Color for cursor & text
7. Cursor type and blinking animation



<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="type-write-animation.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<type-write-animation text-array='["This is a demo...", "...of the element"]'></type-write-animation>
```
