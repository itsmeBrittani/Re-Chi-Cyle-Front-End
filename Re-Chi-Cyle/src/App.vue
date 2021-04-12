<template>
<Header />
  <!-- <HelloWorld msg="Hello Vue 3 + Vite" /> -->
  <Landing msg="Welcome to Re.Chi.Cyle"/>
<Footer />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/header.vue'
import Footer from './components/footer.vue'
import Landing from './components/landing.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>