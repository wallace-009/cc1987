<template>
  <div id="app">
    <router-link to="/HelloWorld">HelloWorld</router-link>
    <router-link to="/Home">Home</router-link>
    <router-link to="/About01">About</router-link>
     <router-link to="/News">News</router-link>
     <img src="./assets/logo.png">
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
img{
  width: 50px;
}
</style>
