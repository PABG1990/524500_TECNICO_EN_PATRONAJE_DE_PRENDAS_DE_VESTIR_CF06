<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Elaboración de prototipos en tejido de punto
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema2/img_1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La elaboración de prototipos en tejido de punto se enfoca principalmente en la elaboración de línea interior y línea deportiva, donde se desarrollan gran variedad de productos, pasando por prendas delicadas, de manipulación cuidadosa, debido al material y tamaño de las piezas. Requiere maquinaria básica, además contar con aditamentos como dosificadores de elástico en fileteadoras, recubridoras, encauchadora, guías y fólderes especiales para asegurar la calidad de las costuras. También se incluye en el proceso máquinas zigzadoras y presilladoras.
    p.mb-5 Los materiales utilizados requieren un manejo con mayor habilidad sobre todo en las prendas de tejido de punto, incluyendo los de composición de elastano.
    Separador  
    #t_2_1.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 2.1  Confección <i>panty</i> femenino
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-3 En el mercado existen cada vez mejores atributos y funcionalidades en este tipo de prendas, sirven de ejemplo, <i>pantys</i> control de abdomen, <i>pantys</i> 0 costuras, entre muchos otros.
        .cajon.color-acento-contenido.p-4.mb-3
          p.mb-0.fw-bold Las máquinas donde se realiza el ensamble son fileteadoras de tres hilos, recubridoras con dosificadores, fólderes sesgadores con dosificación de elástico, zigzadoras y presilladoras.
        ul.lista-ul--color
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones preparación: ] mariposa, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones ensamble: ] unir entrepierna, fijar mariposa, unir costados, sesgar pierna, sesgar cintura, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones de terminados: ] presillar costado, limpiar, revisar, empacar, entre otras
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema2/img_2.png')

    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 Panty tanga - Confección de ropa interior para damas
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/G4IGF6OvFSQ" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 Confección de ropa interior para damas
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/Ds5CtwVbaag" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
    Separador  
    #t_2_2.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 2.2  Confección <i>boxer</i> masculino
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-3 La prenda requiere máquina fileteadora de 3 hilos o con 4 hilos, con dosificadores de elástico, recubridoras con dosificador de elástico, presilladora. Este tipo de prendas se pueden ensamblar en la máquina flat seamer, que les da más seguridad a las costuras. 
        ul.lista-ul--color
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones preparación: ] unir realce, unir tiro, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones ensamble: ]  unir entre pierna, pierna, dobladillar pierna, fijar elástico, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones de terminados: ] presillar, limpiar, revisar, empacar, entre otras
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema2/img_3.png')


    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 <i>Boxer</i> pijamero - <i>Boxer</i> de hombre
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/3E8_mDzj8LU" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 <i>Boxer</i> de hombre
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/Y3tyM2WTpZ0" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm

    Separador  
    #t_2_3.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 2.3  Confección de camiseta tipo polo
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-3 En relación con la confección de la camiseta se debe contar con las máquinas básicas, plana, fileteadora y recubridora. Se recomienda utilizar la fileteadora con puntada de refuerzo (4 hilos).
        ul.lista-ul--color
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones preparación: ] pechera, cuello, bolsillo, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones ensamble: ]  unir por hombros, montar mangas, cerrar por costados, dobladillar ruedo, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones de terminados: ] ojalar, botonar, revisar, planchar, empacar, entre otras
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema2/img_4.png')


    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 Polo <i>Shirt</i> Production
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/QPor7WBIZNA" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 Como hacer camiseta polo hombre corte y confección
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/HJJp-lOu1E4" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm

    Separador  
    #t_2_4.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 2.4  Confección de pantalón de sudadera
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-3 En cuanto al pantalón de sudadera se utiliza además de maquinaria básica, máquinas especiales como encauchadora para sentar el elástico.
        ul.lista-ul--color
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones preparación: ] colocar bolsillo lateral, bolsillos posteriores, unir forro, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones ensamble: ] unir por entrepierna, unir por costados, pegar elástico incluyendo forro, dobladillar botas, entre otras
          li.color-primario
            i.fas.fa-plus
            | #[b Operaciones de terminados: ] revisar, empacar, entre otras
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema2/img_5.png')


    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 Cómo hacer un pantalón de sudadera entubado con cintas laterales, corte y confección
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/oZTVpkX7cuk" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
      .col-sm-12.col-lg-5
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-7.mb-sm-0
                  p.mb-0 Cómo hacer un pantalón de sudadera para mujer, corte y confección
                .col-sm-12.col-lg-5
                  a.boton.color-boton(href="https://www.youtube.com/embed/hlBctRHgSUw" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
    Separador  
    #t_2_5.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 2.5  Elaboración de conjunto deportivo <i>top</i> y <i>leggins</i>
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-3 Para la elaboración del <i>top</i> y de los <i>leggins</i> se utiliza además de maquinaria básica, máquinas especiales como encauchadora para sentar el elástico.
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-1.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-11
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-9.mb-sm-0
                  p.mb-0 Cómo hacer un pantalón de sudadera entubado con cintas laterales, corte y confección
                .col-sm-12.col-lg-3
                  a.boton.color-boton(href="https://www.youtube.com/embed/3xGfOwDybBs" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-1.d-none.d-lg-block
              img(src="@/assets/template/icono-video.svg")
            .col-sm-12.col-lg-11
              .row.justify-content-between.align-items-center
                .col-sm-12.col-lg-9.mb-sm-0
                  p.mb-0 Cómo hacer un pantalón de sudadera para mujer, corte y confección
                .col-sm-12.col-lg-3
                  a.boton.color-boton(href="https://www.youtube.com/embed/owM_WYtLwlc" target="_blank")
                    span.text-sistm Ir al video
                    i.fas.fa-camera.text-sistm
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema2/img_6.png')


  




















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
