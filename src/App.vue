<template>
  <div id="app">
    <Navbar />
    <router-view />
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
export default {
  components: {
    Navbar,
  },
};
</script>
<style lang="scss">
body {
  background-color: #1b2330;
  margin: 0;
  padding: 0;
}

#app {
  font-family: "Open Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center; 
  color: #ffffff;
}
</style>
