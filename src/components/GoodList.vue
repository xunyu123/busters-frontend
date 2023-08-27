<template>

  <table class="table table-striped">
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
      <td>
        <button type="button" class="btn btn-primary btn-sm ">修改</button>
      </td>
      <td>
        <button type="button" class="btn btn-danger btn-sm ">删除</button>
      </td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
    </tbody>
  </table>

</template>

<script>
export default {
  name: 'UserList',
  components:{

  }
}


</script>

<style scoped>
.container{
  margin-top: 20px;
}
</style>