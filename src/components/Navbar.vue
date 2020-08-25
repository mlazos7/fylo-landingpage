<template>
  <div id="nav">
    <div class="logo">
      <img src="./../assets/logo.svg" alt="logo" />
    </div>
    <router-link to="/">Features</router-link>
    <router-link to="/about">Team</router-link>
    <router-link to="/about">Sign in</router-link>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#nav {
   margin: 0 auto;
  display: flex;
width: 1240px;
  font-family: "Raleway", sans-serif;
  .logo{
      display:flex;
      flex-grow: 1;
  }
  padding: 60px;
  a {
      
    display: flex;
    // flex-grow: 1;
    padding-left: 60px;
    font-weight: bold;
    color: white;
    font-size: 16px;

    // &.router-link-exact-active {
    //   color: #42b983;
    // }
  }
}
</style>