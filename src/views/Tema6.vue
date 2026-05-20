<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 6
      h1 Procesamiento y almacenamiento de datos
    Separador
    #t_6_1.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 6.1 Cargas de trabajo transaccionales
    Separador
    #t_6_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 6.2 Cargas de trabajo analíticas
    Separador
    #t_6_3.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 6.3 Principios ACID y gestión de transacciones
    Separador
    #t_6_4.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 6.4 Tipos de almacenamiento de datos
</template>

<script>
export default {
  name: 'Tema6',
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
