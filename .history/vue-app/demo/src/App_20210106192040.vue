<template>
  <div id="app">
    <PostsExample />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import PostsExample from './components/Posts';

export default {
  name: 'App',
  components: {
    HelloWorld,
    PostsExample
  }
}
</script>

<style>
@import "../node_modules/bootstrap/dist/css/bootstrap.min.css"

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
