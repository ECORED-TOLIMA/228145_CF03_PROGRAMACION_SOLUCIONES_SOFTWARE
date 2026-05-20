<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Gestión y administración de bases de datos
    Separador
    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 5.1 Sistemas gestores de bases de datos
    Separador
    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 5.2 Configuración básica de sistemas gestores de bases de datos
    Separador
    #t_5_3.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 5.3 Herramientas de modelado de bases de datos
</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
