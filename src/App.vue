<template>
  <div id="app">
  
    <HeroJumbotron />
    <AppTitle />

    
  </div>
</template>

<script>
import HeroJumbotron from './components/HeroJumbotron.vue'
import AppTitle from './components/AppTitle.vue'

export default {
  name: 'App',
  components: {

    HeroJumbotron,
    AppTitle,
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

}
body{
  margin: 0;
  
}
</style>
