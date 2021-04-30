<template>
  <NavBar/>
  <Home/>
</template>

<script>
import NavBar from './components/NavBar'
import Home from './pages/Home'

export default {
  name: 'App',
  components: {
    NavBar,
    Home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 10px;
}
</style>