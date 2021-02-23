<template>
  <div id="app">

    <HeaderBar msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HeaderBar from './components/header-bar.vue'

export default {
  name: 'App',
  components: {
    HeaderBar
  }
}
</script>

<style>
body{
  margin: 0;
}
</style>
