<template>
  <div id="app" class="bg-white min-h-screen">
    <Header />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    Header,
    HelloWorld
  }
}
</script>

<style>
</style>
