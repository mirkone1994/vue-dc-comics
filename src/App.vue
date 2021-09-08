<template>
  <div id="app">
    <Header/>
    <Comics/>
    <Links/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Comics from "./components/Comics.vue"
import Links from "./components/Links.vue"
import Main from "./components/Main.vue"
import Footer from "./components/Footer.vue"
export default {
  name: 'App',
  components: {
    Header,
    Comics,
    Links,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">
  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Oswald', sans-serif;
  }
  .container {
    max-width: 1400px;
    margin: auto;
  }
  .row {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

</style>
