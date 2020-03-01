<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style>
*{
    font-family:Arial, Helvetica, sans-serif;
    color: #f8f8f8;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    width: 100vw;
    height: 100vh;
    background: #50b6bb;
}
</style>
