<template>
  <div id="app">
    <globaal msg='yeet'/>
    <alleenMinor msg='yeet2'/>
  </div>
</template>

<script>
import globaal from './components/globaal.vue'
import alleenMinor from './components/alleenMinor.vue'

export default {
  name: 'app',
  components: {
    globaal,
    alleenMinor
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
