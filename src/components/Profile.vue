<template>
  <div class="profile">
    <div class="profile-content">
      <img src="../assets/doge-meme.png" >
      <h1>Seu nome</h1>
      <p>Coloque aqui sua biografia de forma resumida. Coloque aqui sua biografia de forma resumida. Coloque aqui sua biografia.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Profile'
}
</script>

<style scoped>
.profile{
  background-color: #0b70b3e0;
  width: 1200px; 
  margin: 0 auto;
  padding: 10px;
}

.profile .profile-content{
  width: 400px;
  margin: auto;
}

.profile-content img{
  vertical-align: middle;
  width: 120px;
  height: 120px;
  border-radius: 50%;
}

.profile-content h1 { 
  color: #ffffff; 
  font-family: 'Raleway',sans-serif; 
  font-size: 40px; 
  font-weight: 800; 
  line-height: 72px; 
  margin: 0 0 24px; 
  text-align: center; 
  text-transform: uppercase; 
}

.profile-content p { 
  color: #f8f8f8; 
  font-family: 'Raleway',sans-serif; 
  font-size: 16px; 
  font-weight: 500; 
  line-height: 32px; 
  margin: 0 0 10px; 
}
</style>