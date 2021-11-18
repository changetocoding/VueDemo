# Vue Starter Template for Bonsai Tree project

## Bonsai Tasks:
1. Update the products list page to use v-for directive to generate the list of products from the products array (in the data)
2. Create a products details page using vue router to pass the id as a prop to the component
3. Refactor products list page to use a component for each individual product card
4. Implement an order basket functionality similar to that on most e-commerce websites

## Project setup
```
cd my-project
npm install
```

### Compiles and hot-reloads for development
```
cd my-project
npm run serve
```
Open http://localhost:8080/ in your browser to view. This will also live update (hot-reload) as you save code files


### Vue devtools 
Install the vue devtools plugin: https://chrome.google.com/webstore/detail/vuejs-devtools


### Template for a new .vue files
You can use this template for a new .vue files
```html
<template>
  <div>

  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>

</style>
```

in router/index.js register it as a route with a path
```js
...
import About from '../views/About.vue'
import NewPage.vue from '../views/NewPage.vue'

...

const routes = [
  ...
  {
    path: '/newpage',
    component: NewPage
  }
]
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
