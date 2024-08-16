<template>
    <div>
      <router-link to="/video">Ir para Video Unico</router-link>
      <router-link to="/tabela">Ir para Tabela Diversos</router-link>
      <router-link to="/imagens">Ir para Imagens Diversas</router-link>
    </div>
  </template>  

<script>

export default {
  name: '   menuPrincipal',


  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
