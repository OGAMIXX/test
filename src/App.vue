<template>
  <div id="app">
    <div>111</div>
    <div>222</div>
    <div>333</div>
    <!-- <img src="./assets/logo.png"> -->
    <router-view/>
    
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
