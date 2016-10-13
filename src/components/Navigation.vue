<template>
  <ul class="main-menu">
    <li><router-link to="/">Home</router-link></li>
    <li>About</li>
  </ul>
</template>

<script>
export default {
  components: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-menu{
  text-align: left;
}

.main-menu li{
  display:inline;
  text-decoration: none;
  margin-right: 30px;
}
</style>
