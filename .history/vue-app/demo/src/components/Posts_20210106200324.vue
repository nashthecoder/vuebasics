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
      <th scope="row">1</th>
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
      posts: [
        {id:1, title: 'Post 1', body: "this is the text body"},
        {id:2, title: 'Post 2', body: "this is the text body"},
        {id:3, title: 'Post 3', body: "this is the text body"},
        {id:4, title: 'Post 4', body: "this is the text body"},
      ]
    }
  }

}
</script>

<style>

</style>
