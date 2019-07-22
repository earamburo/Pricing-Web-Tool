<template>
  <div id = "navbar" class="container-fluid">
    <img src="@/assets/SB_Logo_Green_White_RGB.png" class="img-responsive" alt="" id="logo"/>
  </div>
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
  max-height:40px;
}
</style>
