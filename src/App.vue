<template>
  <div id="app">
    <Hero/>
    <Title/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Title from './components/Title.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Title
  }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
