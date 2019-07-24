<template>
  <div id="buttons-container">
    <button type="button" class="btn pkg-button  btn-md m-buttons">Virtual Campus Experience</button>
    <button type="button" class="btn pkg-button  btn-md m-buttons">Virtual Campus Experience Plus</button>
    <button type="button" class="btn pkg-button  btn-md m-buttons">Top of Funnel</button>
    <button type="button" class="btn pkg-button  btn-md m-buttons">Campus Promoter</button>
    <button type="button" class="btn pkg-button  btn-md m-buttons">Total Recruitment Cycle</button>

  </div>
</template>

<script>
export default {
  name: 'packagebutton',
  props: {
    msg: String
  }
}
</script>
- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@media (max-width:1024px){
  #buttons-container{
    display:none;
  }
}
.m-buttons{
  margin:5px;
}
.pkg-button{
  background-color:#333f48;
  color:white;
  border-radius:0.5rem;
  font-size:0.9rem;

}
.pkg-button:hover{
  background-color:#a3db00;

}


</style>
