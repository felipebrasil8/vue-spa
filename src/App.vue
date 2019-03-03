<template>

  <div>
    <h1>{{ titulo }}</h1>

    <img v-for="foto in fotos" :src="foto.url" :alt="foto.titulo">

  </div>

</template>

<script>

export default {

  data () {
    return {

      fotos: []

    }
  },
  created() {

    // buscaremos nossas fotos aqui
  }
}
</script>
<style>
</style>
