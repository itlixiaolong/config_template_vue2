<template>
  <div id="app">
    <img
      src="./assets/logo.png"
      alt="111">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  props: {},
  data() {
    return {}
  },
  methods: {}
}
</script>

<style>
#app {
  margin-top: 60px;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  text-align: center;
}
</style>
