<template>
  <div class="container">
      <button class="btn"><a href="/proprofs">Proprofs</a></button>
      <button  class="btn"><a href="/flexiquiz">Flexi Quiz</a></button>
      <button  class="btn"><a href="/classmarker">ClassMarker</a></button>
  </div>
</template>
<script>
export default {}
</script>
<style scoped>
.container{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.btn{
  width: 100px;
  height: 30px;
  border: 1px solid black;
  margin-top: 20px;
}
a{
  text-decoration: none;
}
</style>
