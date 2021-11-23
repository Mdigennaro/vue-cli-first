<template>
  <main>

    <p>
      <span class="start">Lorem</span> ipsum dolor sit amet consectetur adipisicing elit. <span class="after-point">Assumenda</span> corporis fugit reprehenderit expedita officia perspiciatis qui numquam soluta? <span class="after-ask">Quasi</span> , iusto tenetur illo autem magni cum suscipit numquam dolorum perspiciatis, laborum incidunt eligendi esse assumenda, mollitia ducimus facere qui. <span class="after-point">Impedit</span> , voluptatum unde? <span class="after-ask">Amet</span> iste excepturi eligendi harum deleniti consectetur earum quibusdam. <span class="after-point">Quod</span>  iste consectetur dicta nihil labore deserunt voluptatum odio minima atque eligendi, consequuntur distinctio doloremque porro incidunt, magnam impedit sit earum, culpa error rerum quisquam accusantium animi! <span class="after-exclamation">Nobis</span> quisquam ipsum aut aliquam? <span class="after-ask">Fugiat</span>, distinctio? <span class="after-ask">Ducimus</span> numquam, illum nostrum nulla nam magnam necessitatibus quae eaque! <span class="after-exclamation">Veniam</span> mollitia omnis necessitatibus sapiente iure.
    </p>

  </main>
</template>

<script>
export default {
  name: "Main"
}
</script>

<style>

main{
  width: 60%;
  margin: 0 auto;
}

.start, .after-point, .after-ask, .after-exclamation{
  font-weight: bold;
}

.start{
  color: green;
  background-color: yellow;
}

.after-point{
  color: red;
  background-color: greenyellow;
}

.after-ask{
  color: white;
  background-color: black;
}

.after-exclamation{
  color: yellow;
  background-color: red;
}

</style>