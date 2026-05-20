<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Modelado de bases de datos
    Separador
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 2.1 Diseño conceptual de bases de datos
    Separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 2.2 Modelo Entidad-Relación (ER)
    Separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 2.3 Diseño lógico de bases de datos
    Separador
    #t_2_4.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 2.4 Transformación del modelo conceptual al modelo lógico
    Separador
    #t_2_5.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 2.5 Diseño físico de bases de datos
    Separador
    #t_2_6.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 2.6 Normalización de bases de datos
</template>

<script>
export default {
  name: 'Tema2',
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
