<template>
  <div id="app">
    <my-counter></my-counter>
  </div>
</template>

<script>
import MyCounter from './components/MyCounter.vue'

export default {
  name: 'app',
  components: {
    MyCounter
  },

  data () {
    return {
      count: 0,
    }
  },

  created () {
    window.vm = this
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
