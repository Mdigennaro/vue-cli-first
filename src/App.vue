<template>

  <div id="app">
    
    <Title />
    <Main />
    <Footer />

  </div>

</template>

<script>
import Title from "./components/Title.vue"
import Main from "./components/Main.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {
    Title,
    Main,
    Footer
  }
}
</script>

<style>

#app{
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  text-align: center;
}

</style>
