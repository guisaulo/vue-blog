<template>
  <div class="nav">
    <ul>
      <li><a href="" rel="noopener">Blog</a></li>
      <li><a href="" rel="noopener">Sobre</a></li>
      <li><a href="" rel="noopener">Descrição</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
.nav{
  background-color: #083858d3;
  width: 1200px; 
  margin: 0 auto;
  padding: 10px;
}

.nav ul {
  list-style-type: none;
  padding: 0;
}

.nav li {
  display: inline-block;
  margin: 0 20px;
}

.nav a { 
  color: #ffffff; 
  text-decoration: underline; 
}

.nav a:hover { 
  color: #1c1c1c; 
  text-decoration: underline; 
}
</style>