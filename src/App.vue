<template>
  <div id="app">
    <img src="./assets/logo.png">
    <p>
      <router-link to="/foo">Foo</router-link>
      <router-link to="/bar">Bar</router-link>
      <router-link to="/">Hello</router-link>
    </p>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
body { background: mintcream; }

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  

}
</style>
