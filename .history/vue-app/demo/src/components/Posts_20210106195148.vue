<template>
  <div>
    <table class="table table-striped mt-4">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
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
