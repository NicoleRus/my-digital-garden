## How are Vue components structured?

A Vue component contains three parts:
 - Script block: Javascript
 - Template block: HTML
 - Style: CSS

 ### Example

 ```js
 export default {
  mounted() {
    console.log('It works!')
  }
 }
 ```

 ```html
<template><h1>My Component title</h1></template>
 ```