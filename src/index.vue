<template>
  <div id="app">
    <switchBetween
      @teDoen-click="choice = 'teDoen'"
      @incl-alGehaald-click="choice = 'incl-alGehaald'"
    />

    <div v-if="choice === 'teDoen'">
      <globaal/>
      <alleenMinor/>
    </div>

    <div v-if="choice === 'incl-alGehaald'">
      <h2>test</h2>
    </div>
  </div>
</template>

<script>
import switchBetween from "./components/switchBetween.vue"
import globaal from "./components/globaal.vue"
import alleenMinor from "./components/alleenMinor.vue"

export default {
  name: "app",
  data() {
    return {
      choice: "teDoen"
    }
  },
  components: {
    switchBetween,
    globaal,
    alleenMinor
  }
}
</script>

<style>

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  flex-direction: column;
  align-self: center;
  align-items: center;
  align-content: center;
}
</style>
