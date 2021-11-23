<template>
  <footer>
    <div>Made with <span class="heart">♥</span> by <span class="creator-m"> M.</span><span class="creator-d">D.</span><span class="creator-g">G.</span></div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style>

.heart{
  color: red;
}

.creator-m, .creator-d, .creator-g{
  font-weight: bold;
  background-color: rgb(21, 151, 194);
}

.creator-m{
  color: green;
}

.creator-d{
  color: white;
}

.creator-g{
  color: red;
}

</style>