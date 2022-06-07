<template>
  <div id="app">
    <TiTle/>
    <JumbotronHero/>
  </div>
</template>

<script>
import TiTle from './components/TiTle.vue'
import JumbotronHero from './components/JumbotronHero.vue'


export default {
  name: 'App',
  components: {
    TiTle,
    JumbotronHero
    
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


</style>
