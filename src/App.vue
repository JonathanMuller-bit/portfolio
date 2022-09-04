<template>
  <div id="app">
    <HomeView class='logo'/>
  </div>
</template>
<script>
import HomeView from './views/HomeView.vue';
  export default {
    name: 'App',
    components: {
    HomeView,
}
  }
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

ul {
  list-style: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
  width: 100%;
  background-color: #202020;
  padding: 20px;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

.logo{
  width: 100%;
  height: 100%;
}
</style>
