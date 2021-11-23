<template>

  <div id="app">
    
    <Title />
    <main>M</main>
    <footer>F</footer>

  </div>

</template>

<script>
import Title from "./components/Title.vue"

export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style>

#app{
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  text-align: center;
}

</style>
