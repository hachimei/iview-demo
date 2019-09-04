<template>
  <div id="app">
    <formDemo />
  </div>
</template>

<script>
import formDemo from './components/formDemo'

export default {
  name: 'app',
  components: {
    formDemo,
  },
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
