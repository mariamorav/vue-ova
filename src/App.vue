<template>
  <div id="app">
    <Header></Header>
    <Content></Content>
    <Footer></Footer>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Content from './components/Content.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Content
  }
}
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>