<template>
  <div id="app">
    <Home msg="Welcome to 1772 One Page"/>
    <About msg="Welcome to Your Vue.js App"/>
    <Timeline msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Home from './views/Home.vue';
import About from './views/About.vue';
import Timeline from "@/views/Timeline";

export default {
  name: 'App',
  components: {
    Home,
    About,
		Timeline
  }
}
</script>

<style>
  @import 'assets/styles/main.css';
</style>
