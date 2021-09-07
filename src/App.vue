<template>
  <div id="app">
    <Header/>
    <Links/>
    <Main/>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Links from "./components/Links.vue"
import Main from "./components/Main.vue"
export default {
  name: 'App',
  components: {
    Header,
    Links,
    Main,
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
