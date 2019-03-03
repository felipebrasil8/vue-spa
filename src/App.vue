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

      fotos: [
        { 
          url: 'https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcTwV4kVzT5McBdGSgqlVeRzubrNH_mOrrkKseDOGFURq20HmsrelEfMU7It',
          titulo: 'cachorro'
        },
        { 
          url: 'https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcTwV4kVzT5McBdGSgqlVeRzubrNH_mOrrkKseDOGFURq20HmsrelEfMU7It',
          titulo: 'cachorro2'
        }
      ]

    }
  },
  created() {

    // buscaremos nossas fotos aqui
  }
}
</script>
<style>
</style>
