<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <HelloWorld msg="Vue 全家桶">
       <h2 slot="a">测试具名插槽</h2>
       <h2 slot="b">测试具名插槽b</h2>
    </HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
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
