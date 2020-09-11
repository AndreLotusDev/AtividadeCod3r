<template>
  <div id="app">
      <hr>
      <app-filmes filmeTitulo="Homem de ferro"/>
      <app-filmes filmeTitulo="Homem de ferro"/>
      <app-filmes filmeTitulo="Homem de ferro"/>
      <app-filmes filmeTitulo="Homem de ferro"/>
  </div>
</template>

<script>
import Filmes from './Filmes.vue'

export default {
  components: {'app-filmes': Filmes},
}
</script>

<style>

</style>