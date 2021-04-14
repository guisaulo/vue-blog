<template>
  <Home 
  titleBlog="Seu nome"   
  biography="Coloque aqui sua biografia de forma resumida. Coloque aqui sua biografia de forma resumida. Coloque aqui sua biografia."/>
  <Home-feed />

</template>

<script>
import HomeFeed from './components/Home-feed.vue'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home,
    HomeFeed
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 20px;
}
</style>