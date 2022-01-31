<template>
  <div class="hello">
    <div class="jumbotron">
      <img alt="Monke logo" src="../assets/monke.jpg">
      <h1>This is a Jumbotron!</h1>
      <h3>And i created it only with plane css and HTML because i don't know how to link bootstrap yet!</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  color: red ;
  text-align: center;
}
h3{
  color: darkred;
  text-align: center;
}
.jumbotron{
  width: 80vw;
  height: 80vh;
  background-color: lightblue;
  border-radius: 40px 40px;
  margin: 0 auto;
  padding: 10px 10px;
}
</style>
