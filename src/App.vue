<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <Test2/>
    <New/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Test2 from './components/Test2'
import New from './components/New'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Test2,
    New
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
