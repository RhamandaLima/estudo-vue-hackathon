<template>
  <div id="app">
    <NovoComponente/>
    <TesteIf />
  </div>
</template>

<script>
import NovoComponente from './components/NovoComponente.vue'
import TesteIf from './components/TesteIf.vue'

export default {
  name: 'App',
  components: {
    NovoComponente,
    TesteIf
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
