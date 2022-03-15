<template>
  <div id="app">
    <NovoComponente/>
    <TesteIf />
    <TesteFor />
  </div>
</template>

<script>
import NovoComponente from './components/NovoComponente.vue'
import TesteIf from './components/TesteIf.vue'
import TesteFor from './components/TesteFor.vue'

export default {
  name: 'App',
  components: {
    NovoComponente,
    TesteIf,
    TesteFor
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
