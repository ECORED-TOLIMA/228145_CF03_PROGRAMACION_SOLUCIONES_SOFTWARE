<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Interpretación y estructura del modelo relacional
    Separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.1 Entidades, atributos y relaciones
    Separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.2 Llaves primarias y foráneas
    Separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.3 Integridad de identidad e integridad referencial
    Separador
    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 3.4 Restricciones y consistencia de los datos
</template>

<script>
export default {
  name: 'Tema3',
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
