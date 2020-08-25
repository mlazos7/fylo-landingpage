<template>
  <div class="home">
    <div class="intro-image">
      <img src="./../assets/illustration-intro.png" alt="">
    </div>
    <h1>All your files in one secure location, <br/> accessible anywhere.</h1>
    <h2>Fylo stores all your most important files in one secure<br/>location. Access them wherever you need, share and<br/>collaborate with friends family, and co-workers.</h2>
    <div class="fylo-button">
      <p><b>Get Started</b></p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {
    
  }
}
</script>

<style lang="scss" scoped>
h1{
  padding-top: 60px;
  font-size: 40px;
  font-family: "Raleway", sans-serif;
}
h2{
  padding-top: 30px;
  font-size: 20px;
}

.fylo-button{
display:flex;
align-items: center;
justify-content: center;
margin: 0 auto;
margin-top: 40px;
  width: 280px;
  min-height: 56px;
  background-color: #41B2D0;
  border-radius: 36px;
  color: white;
  p{
    padding: 0px;
  }
}
</style>
