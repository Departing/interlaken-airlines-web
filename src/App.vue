<template>
  <div id="app" class='container'>
    <Navbar/>
    <HelloWorld/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
  }
}
</script>

<style>
</style>
