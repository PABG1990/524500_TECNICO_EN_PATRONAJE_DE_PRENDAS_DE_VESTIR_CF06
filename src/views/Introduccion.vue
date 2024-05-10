<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.justify-content-center.mb-5
      .colsm-12.col-lg-9
        p.mb-5 La transición y globalización en el sector moda exige cada vez más calidad en el desarrollo de las prendas de vestir, unificando parámetros o estándares de calidad en los productos, buscando que cada proceso cumpla con los requerimientos establecidos, con el fin de minimizar el error y ser capaces de satisfacer las necesidades de los consumidores.
        .cajon.color-acento-contenido.p-4.mb-4
          p.fw-bold Actualmente, en el sector confección, diseño y moda se está haciendo la transición a nivel país en la preparación y capacitación de mano de obra calificada, a la vez que se implementa tecnología versátil que aporta al estándar competitivo internacional, de manera que se logre dar una respuesta rápida y eficaz a las exigencias del mercado; en este aspecto, el patronista juega un papel fundamental, pues debe estar preparado para cumplir a cabalidad con los procesos de producción o prototipado.
      .colsm-12.col-lg-3
        img(src='@/assets/curso/temas/introduccion/img_1.png', alt='')
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
