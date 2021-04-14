<template>
  <div class="feed">
    <h1>Últimas do blog</h1>
    <div class="feed-item">
        <h2>5 dicas para sua carreira profissional</h2>
        <p>Confira algumas dicas que podem ajudar a alavancar sua carreira como desenvolvedor front-end</p>
    </div>
    <div class="feed-item">
        <h2>5 dicas para sua carreira profissional</h2>
        <p>Confira algumas dicas que podem ajudar a alavancar sua carreira como desenvolvedor front-end</p>
    </div>
    <div class="feed-item">
        <h2>5 dicas para sua carreira profissional</h2>
        <p>Confira algumas dicas que podem ajudar a alavancar sua carreira como desenvolvedor front-end</p>
    </div>     
    <h2>Ver tudo</h2>
  </div>
</template>

<script>
export default {
  name: 'Home-feed'
}
</script>

<style scoped>

.feed{
  background-color: white;
  width: 500px; 
  margin: 0 auto;
  padding: 10px;
}

.feed-item{
  background-color: white ;
  width: 300px; 
  margin: 0 auto;
  padding: 10px;   
}

h1 { 
  color: #0e0d0df1; 
  font-family: 'Raleway',sans-serif; 
  font-size: 30px; 
  font-weight: 800; 
  line-height: 72px; 
  margin: 0 0 24px; 
  text-align: center; 
}

h2 { 
  color: #051250e1; 
  font-family: 'Raleway',sans-serif; 
  font-size: 18px; 
  font-weight: 300; 
  text-align: center; 
}

p { 
  color: #302e2ee3; 
  font-family: 'Raleway',sans-serif; 
  font-size: 13px; 
  font-weight: 100; 
  text-align: justify; 
}
</style>