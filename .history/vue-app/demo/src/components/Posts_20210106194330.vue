<template>
  <div>

    <button class="btn btn-primary">Click Me</button>

  </div>
</template>

<script>
export default {
  name: 'PostsExample',
  data(){
    return{
      posts: [
        {id:1, title: 'Post 1'},
        {id:2, title: 'Post 2'},
        {id:3, title: 'Post 3'},
        {id:4, title: 'Post 4'},
      ]
    }
  }

}
</script>

<style>

</style>
