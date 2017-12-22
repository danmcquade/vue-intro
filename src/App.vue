<template>
  <div id="app">
    <Intro />
    <Skills />
    <Portfolio />
  </div>
</template>

<script>
import Intro from './components/Intro'
import Skills from './components/Skills'
import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  components: {
    Intro,
    Skills,
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
