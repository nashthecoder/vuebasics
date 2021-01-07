<template>
  <div class="container">
    <table class="table table-striped mt-4">
  <thead>
    <tr>
      <th scope="col">User Id</th>
      <th scope="col">Id</th>
      <th scope="col">Title</th>
      <th scope="col">Body</th>

    </tr>
  </thead>
  <tbody>
    <tr v-for="post in posts" :key="post.id" >
      <th scope="row"></th>
      <td>{{post.id}}</td>
      <td>{{post.title}}</td>
      <td>{{post.body}}</td>
    </tr>
  </tbody>
</table>
    <button class="btn btn-primary">Click Me</button>

  </div>
</template>

<script>
export default {
  name: 'PostsExample',
  data(){
    return{
      posts: []
    }
  }

}
</script>

<style>

</style>
