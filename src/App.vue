<template>
  <div id="app">
    <v-main-page />
  </div>
</template>

<script>
import vMainPage from './components/v-main-page';



export default {
  name: 'app',
  components: {
    vMainPage,
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
