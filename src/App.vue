<template>
  <div id="app">
    <Header/>
    <Main :slides="slides"/>
    <Footer/>
    
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Main from './components/Main.vue'
// DATA
import slides from '@/assets/dc-comics';


export default {
  name: 'App',
  data(){
    console.log(slides)
    return {slides}
    
  },
  components: {
    Header,
    Footer,
    Main,
  },
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
