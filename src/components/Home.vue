<template>
  <div class="header">
    <ul>
      <li><a href="" target="_blank" rel="noopener">Blog</a></li>
      <li><a href="" target="_blank" rel="noopener">Sobre</a></li>
      <li><a href="" target="_blank" rel="noopener">Descrição</a></li>
    </ul>
    <div class="profile">
      <img src="../assets/doge-meme.png" >
      <h1>{{ titleBlog }}</h1>
      <p>{{biography}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    titleBlog: String,
    biography: String
  }
}
</script>

<style scoped>

.header{
  background-color: #0b70b3e0;
  width: 1200px; 
  margin: 0 auto;
  padding: 10px;
}

.profile{
  width: 500px; 
  margin: 0 auto;
  padding: 10px;   
}

img{
  vertical-align: middle;
  width: 150px;
  height: 150px;
  border-radius: 50%;
}

h1 { 
  color: #ffffff; 
  font-family: 'Raleway',sans-serif; 
  font-size: 40px; 
  font-weight: 800; 
  line-height: 72px; 
  margin: 0 0 24px; 
  text-align: center; 
  text-transform: uppercase; 
}

p { 
  color: #f8f8f8; 
  font-family: 'Raleway',sans-serif; 
  font-size: 16px; 
  font-weight: 500; 
  line-height: 32px; 
  margin: 0 0 10px; 
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a { 
  color: #c8c8c8; 
  text-decoration: underline; 
}

a:hover { 
  color: #1c1c1c; 
  text-decoration: underline; 
}

</style>