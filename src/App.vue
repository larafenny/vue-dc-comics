<template>
  <div id="app">
    <Header/>
    <Main/>
    <Icons/>
    <Footer/>


  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Icons from './components/Icons.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Icons,
    Footer
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
