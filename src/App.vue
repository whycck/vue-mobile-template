<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Button type="primary" @click="sayLove">你好</Button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import { Button } from 'vant'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Button
  },
  methods: {
    sayLove () {
      console.log('你好, Vant')
    }
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
