<template>
  <div id="app">
    <jd-guider></jd-guider>
    <jd-main msg="Welcome to jiudongs's school"/>
  </div>
</template>

<script>
import JDMain from './components/main.vue'
import JDGuider from './components/guider.vue'

export default {
  name: 'App',
  components: {
    "jd-main":JDMain,
    "jd-guider":JDGuider
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
