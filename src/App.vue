<template>
  <!--<Header/>-->
  <router-view/>
  <!--<Footer/>-->  
</template>
<script>
import 'normalize.css'
//import Header from "./components/Header"
//import Footer from "./components/Footer"

export default {
  name: 'App',
  components: {
    //Header,
    //Footer,
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
</style>
