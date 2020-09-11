<template>
  <div>
      <hr>
      <h1>{{atualizar()}}</h1>
      <hr>
  </div>
</template>

<script>
export default {
    props: ['filmeTitulo'],

    methods:{
        atualizar()
        {
            return this.filmeTitulo += " - 1"
        }
    }
}
</script>

<style>

</style>