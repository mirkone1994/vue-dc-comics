<template>
  <div id="app">
    <Header/>
    <Links/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Links from "./components/Links.vue"
import Main from "./components/Main.vue"
import Footer from "./components/Footer.vue"
export default {
  name: 'App',
  components: {
    Header,
    Links,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">
  * {
    padding: auto;
    margin: auto;
    box-sizing: border-box;
  }

</style>
