<template>
  <navbar/>
  <router-view/>
</template>

<script>
import Navbar from './components/Navbar.vue';
  export default{
    components:{
      Navbar
    }
  }
</script>

<style>
#app {
  font-family: 'Dream Avenue';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}
</style>
