<template>
  <div id="app">
    <planA msg='yeet'/>
    <alleenMinor msg='yeet2'/>
  </div>
</template>

<script>
import planA from './components/planA.vue'
import alleenMinor from './components/alleenMinor.vue'

export default {
  name: 'app',
  components: {
    planA,
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
