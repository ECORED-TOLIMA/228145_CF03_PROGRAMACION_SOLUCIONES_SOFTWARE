<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Lenguajes y manipulación de bases de datos
    Separador
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 4.1 Lenguajes DDL y DML
    Separador
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 4.2 Creación de bases de datos y tablas
    Separador
    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 4.3 Modificación de estructuras de tablas y columnas
    Separador
    #t_4_4.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 4.4 Inserción, actualización y eliminación de registros
    Separador
    #t_4_5.titulo-segundo.color-acento-contenido(data-aos="fade-left")
      h2 4.5 Eliminación de tablas y bases de datos
</template>

<script>
export default {
  name: 'Tema4',
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
