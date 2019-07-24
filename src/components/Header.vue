<template>
  <nav class="navbar navbar-light" id="navbar">
    <a class="navbar-brand text-white">
    SBLOGO
    </a>
    <form class="form-inline">
      <div class="form-group col-md-4" id="yearSelectContainer">
        <select class="custom-select mr-sm-2" id="yearSelect">
          <option selected>Years</option>
          <option value="1">One</option>
          <option value="2">Two</option>
          <option value="3">Three</option>
        </select>
      </div>
    </form>
  </nav>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#navbar{
  background-color: #333f48;

}
#logo{
  max-width:255px;
  max-height:60px;
}
#yearSelectContainer{
  margin-bottom:0px;
}
</style>
