<template>
  <div id="app">
    <NavBar />
    <router-view/>
    <FooterSec />
  </div>
</template>

<script>

// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'
import FooterSec from '@/components/FooterSec.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    FooterSec
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#app .bg-btn{
    background: #FA724C;
    border-radius: 50px;
    padding: 10px 20px;
  }
</style>
