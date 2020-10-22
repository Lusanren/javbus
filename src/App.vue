<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" style="width: 200px;height: 200px;">
    <HelloWorld msg="Hi,Welcome!"/>
	<Download url="http://www.baidu.com" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Download from './components/Download.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
	Download
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
