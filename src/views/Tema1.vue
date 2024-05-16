<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Control de calidad
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Con el crecimiento de la industrialización se requería ejercer control en los procesos para disminuir los desperdicios y los reprocesos en la producción, cada vez con niveles de unidades más altas, necesitando estandarizar las características del producto fabricado.
            p.mb-0 A partir de lo mencionado, revisar la producción proporciona una mayor confianza por parte del cliente, mejora la competitividad y sirve como una herramienta en la administración de la empresa.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        p Es importante mencionar los principios de calidad para el control de la misma:
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-5
        img.mb-cus(src='@/assets/curso/temas/tema1/img_2.svg', alt='')
      .col-sm-12.col-lg-5
        ul.lista-ul--color
          li.color-primario
            i.fas.fa-plus
            | Mejora continua
          li.color-primario
            i.fas.fa-plus
            | Evitar inspecciones masivas
          li.color-primario
            i.fas.fa-plus
            | Relación de precio y calidad
          li.color-primario
            i.fas.fa-plus
            | Métodos modernos de capacitación y entrenamiento
          li.color-primario
            i.fas.fa-plus
            | Exigencia de la competitividad
          li.color-primario
            i.fas.fa-plus
            | Identificación del trabajador con sus funciones y su aporte a la calidad
          li.color-primario
            i.fas.fa-plus
            | Eliminación de barreras entre áreas
          li.color-primario
            i.fas.fa-plus
            | Establecer ruta de calidad
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-7
        p Acciones que permiten encaminar la empresa hacia el proceso de control de calidad.

    Separador  
    #t_1_1.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.1 Concepto de calidad
    p.mb-5(data-aos="zoom-in-left") Existen varias definiciones, y cada persona puede determinar un concepto propio, además de tener en cuenta las definiciones de los estudiosos en el tema, entre los cuales se encuentran:
    LineaTiempoB.color-secundario.mb-5(:datos="datosLineaTiempoB")(data-aos="zoom-in-left")
    .cajon.color-acento-contenido.p-4.mb-5(data-aos="zoom-in-left")
        p.mb-0.fw-bold Al tener en cuenta los términos de los estudiosos se puede determinar que satisfacción, cliente, necesidades, mercado y expectativas son las palabras comunes que engloban el concepto para concluir que la calidad es el nivel de satisfacción del cliente, cumpliendo con los requisitos, es decir, con las necesidades y expectativas del cliente.
    h3.titulo-tercero(data-aos="zoom-in-left") Concepto control de calidad
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-4 Una vez se tienen definidos los objetivos y los requisitos de calidad del producto se deben controlar las variaciones de esas características, cualidades o especificaciones exigidas por el cliente o de acuerdo con la norma.
        p.mb-4 Mejor llamado como control estadístico de la calidad es el proceso conformado por una serie de técnicas para analizar el comportamiento de las variaciones de los requisitos del producto, con el fin de establecer acciones que mejoren su calidad, en pro de aumentar las ventas y la productividad de la empresa.
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0.fw-bold El control de calidad no solo está encaminado a las inspecciones del producto terminado, también es importante realizar las inspecciones del producto durante el proceso de producción.
      .col-sm-12.col-lg-3
        img.d-none.d-lg-block(src='@/assets/curso/temas/tema1/img_8.png', alt='')
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3
        p.mb-3 El cliente es la persona que adquiere el producto o servicio, puede o no utilizarlo y es quien paga por ello.
        ul.lista-ul--color
          li.color-primario
            i.fas.fa-plus
            | #[b Interno:] trabajador.
          li.color-primario
            i.fas.fa-plus
            | #[b Externo:] recibe el producto. Tener en cuenta que quien lo usa es el consumidor del mismo.
      .col-sm-12.col-lg-3
        img.d-none.d-lg-block(src='@/assets/curso/temas/tema1/img_9.svg', alt='')

    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/curso/temas/tema1/img_10.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0.fw-bold ¿Qué es un requisito?
                  p Es la traducción de las necesidades y expectativas del cliente y se presenta en tres niveles:
    .row.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-4.mb-4
        .tarjeta-numerada.color-acento-contenido.p-5.h-anexo
          .tarjeta-numerada__numero
            .h2 1
          p.text-center 
            b Necesidades
          p.text-center Principal objetivo del producto, si no existen genera insatisfacción.
          ul.lista-ul--color
            li.color-primario
              i.fas.fa-plus
              | Ser funcional
            li.color-primario
              i.fas.fa-plus
              | Resolver el problema
            li.color-primario
              i.fas.fa-plus
              | Entrega oportuna
            li.color-primario
              i.fas.fa-plus
              | Respetar precio acordado
            li.color-primario
              i.fas.fa-plus
              | Tiempo de duración de vida útil
      
      .col-sm-12.col-lg-4.mb-4
        .tarjeta-numerada.color-acento-botones.p-5.h-anexo
          .tarjeta-numerada__numero
            .h2 2
          p.text-center 
            b Expectativas
          p.text-center Si se presentan en mayor medida genera satisfacción.
          ul.lista-ul--color
            li.color-primario
              i.fas.fa-plus
              | Darle importancia al cliente 
            li.color-primario
              i.fas.fa-plus
              | Trato cordial y amable al cliente
            li.color-primario
              i.fas.fa-plus
              | Hacer sentir importante al cliente
      
      .col-sm-12.col-lg-4.mb-4
        .tarjeta-numerada.color-primario.p-5.h-anexo
          .tarjeta-numerada__numero
            .h2 3
          p.text-center 
            b Superar expectativas
          p.text-center No esperado por el cliente (sorprenderle gratamente), incrementa el grado de satisfacción.
          ul.lista-ul--color
            li.color-primario
              i.fas.fa-plus
              | Asistencia técnica 
            li.color-primario
              i.fas.fa-plus
              | Descuentos
            li.color-primario
              i.fas.fa-plus
              | Tiempos de entrega
    .fullview
      .row.justify-content-center.align-items-center.mb-5.p-5(data-aos="zoom-in-left")
        .col-sm-12.col-lg-3
          img.d-none.d-lg-block(src="@/assets/curso/temas/tema1/img_11.svg")
        .col-sm-12.col-lg-7
          p.mb-5 Existen tipos de requisitos relacionados con:
          ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | Función del producto: referencia a su desempeño, responde a la pregunta ¿para qué sirve?
              li.color-primario
                i.fas.fa-plus
                | Características técnicas: cantidades, peso, tamaño, color, entre otras
              li.color-primario
                i.fas.fa-plus
                | Condiciones de pago y precio
              li.color-primario
                i.fas.fa-plus
                | Plazos de entrega
              li.color-primario
                i.fas.fa-plus
                | Especificaciones dadas por el cliente
              li.color-primario
                i.fas.fa-plus
                | Mantenimientos y vida útil: instrucciones de uso y términos de garantía
              li.color-primario
                i.fas.fa-plus
                | Legales: leyes y normas (rotulados, materiales, uso y residuos)
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
        .col-sm-12.col-lg-9           
          .cajon.color-acento-contenido.p-4.mb-4
            p.fw-bold.mb-0 Conforme con lo mencionado anteriormente, también podemos clasificar los requisitos de acuerdo con las características directas del producto, de la organización o de los externos, como el cliente y la normatividad.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
        .col-sm-12.col-lg-9
          p Dado que se presentan variaciones en los productos es preciso permitir tolerancias, que son márgenes permisibles de variación y aceptación.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
        .col-sm-12.col-lg-9
          h3.titulo-tercero Antecedentes y evolución de control de calidad
          p.mb-3 Al ubicarse de manera temporal en el cambio de la fabricación artesanal a la industrialización, derivado de la Revolución Industrial y de los cambios en la producción masificada, se presentó un auge en la industria del automóvil liderada por Henry Ford en la década de 1910, en la que se daba los inicios de la calidad en las inspecciones del producto terminado. 
          p.mb-0 Con el avance de la tecnología, de los estudios del trabajo y de la implementación de técnicas para aumentar la productividad, que buscaba la estandarización del producto, la calidad ganó importancia dentro del desempeño del negocio, es decir, a partir de los niveles de calidad del producto se empezó a satisfacer al cliente. Hoy en día, derivado de la cuarta Revolución Industrial, el proceso de control de calidad se viene automatizando para el análisis y predicción de fallas, sin olvidar que las personas siguen haciendo parte del proceso, al gestionar de manera integral la cadena de suministro. 

        .col-sm-12.col-lg-3
          img.d-none.d-lg-block(src="@/assets/curso/temas/tema1/img_12.png")
    SlyderA(tipo='b').bg01.p-sm-1.p-lg-5.mb-5(data-aos="zoom-in-left")
      .row.justify-content-center.px-5
        .col-sm-12.col-lg-4
          p.mb-5.fw-bold Inspecciones
          ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | A partir de década de 1910.
              li.color-primario
                i.fas.fa-plus
                | Especialización del trabajo.
              li.color-primario
                i.fas.fa-plus
                | Inspecciones producto terminado.
        .col-sm-12.col-lg-8
          img(src="@/assets/curso/temas/tema1/img_13.png")

      .row.justify-content-center.px-5
        .col-sm-12.col-lg-4
          p.mb-5.fw-bold Control de calidad
          ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | A partir de la Segunda Guerra Mundial, en los años 40.
              li.color-primario
                i.fas.fa-plus
                | Estudios de métodos y tiempos para mejorar eficiencia.
              li.color-primario
                i.fas.fa-plus
                | Procesos más especializados.
              li.color-primario
                i.fas.fa-plus
                | Desarrollo de estándares.
              li.color-primario
                i.fas.fa-plus
                | Uso de métodos de medición.
              li.color-primario
                i.fas.fa-plus
                | Muestreos, gráficos, sistema de información, manuales, instructivos, formatos.
        .col-sm-12.col-lg-8
          img(src="@/assets/curso/temas/tema1/img_14.png")
      
      .row.justify-content-center.px-5
        .col-sm-12.col-lg-4
          p.mb-5.fw-bold Aseguramiento de calidad
          ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | A partir de los años 60.
              li.color-primario
                i.fas.fa-plus
                | Garantía de calidad.
              li.color-primario
                i.fas.fa-plus
                | Cumplir con estándares.
              li.color-primario
                i.fas.fa-plus
                | Reducir defectos.
              li.color-primario
                i.fas.fa-plus
                | Creación de sistemas de calidad.
              li.color-primario
                i.fas.fa-plus
                | Auditorías internas y externas.
        .col-sm-12.col-lg-8
          img(src="@/assets/curso/temas/tema1/img_15.png")

      .row.justify-content-center.px-5
        .col-sm-12.col-lg-4
          p.mb-5.fw-bold Gestión de calidad
          ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | A partir de los años 80.
              li.color-primario
                i.fas.fa-plus
                | Participación de la dirección de la empresa.
              li.color-primario
                i.fas.fa-plus
                | Mejora continua.
              li.color-primario
                i.fas.fa-plus
                | Satisfacción del cliente.
        .col-sm-12.col-lg-8
          img(src="@/assets/curso/temas/tema1/img_16.png")

      .row.justify-content-center.px-5
        .col-sm-12.col-lg-4
          p.mb-5.fw-bold Calidad total
          ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Círculos de calidad:] trabajo en equipo.
              li.color-primario
                i.fas.fa-plus
                | #[b Desarrollo personal:] capacitación y entrenamiento.
              li.color-primario
                i.fas.fa-plus
                | Se involucra todas las áreas y todas las personas de la empresa.
        .col-sm-12.col-lg-8
          img(src="@/assets/curso/temas/tema1/img_17.png")

      .row.justify-content-center.px-5
        .col-sm-12.col-lg-4
          p.mb-5.fw-bold Excelencia de la igualdad
          ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | Suma de teorías y prácticas de calidad.
              li.color-primario
                i.fas.fa-plus
                | Liderazgo en el mercado.
              li.color-primario
                i.fas.fa-plus
                | Involucran los procesos. Mejora continua.
        .col-sm-12.col-lg-8
          img(src="@/assets/curso/temas/tema1/img_18.png")

    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-pdf-2.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Complementario - 14.3 Artículo
                .col-sm-auto
                  a.boton.color-boton(:href="obtenerLink('/downloads/maquinaria_herramientas_insumos_vf_compressed.pdf')" target="_blank")
                    span.text-sistm Descargar
                    i.fas.fa-file-download.text-sistm
    h3.titulo-tercero(data-aos="zoom-in-left") Control de calidad en la industria textil y confección
    p.mb-5(data-aos="zoom-in-left") Se controla la calidad con el fin de mantener y corregir los defectos, errores o no conformidad que se presenta durante la producción de la prenda. Por tanto, se desarrolla según las variables y atributos del producto. 
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        p Los beneficios de implementar las herramientas para el control de calidad son:
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3
        img.d-none.d-lg-block(src="@/assets/curso/temas/tema1/img_19.svg")

      .col-sm-12.col-lg-3
        ul.lista-ul--color
          li.color-primario
            i.fas.fa-plus
            | Reducción de costos
          li.color-primario
            i.fas.fa-plus
            | Reducción de defectos
          li.color-primario
            i.fas.fa-plus
            | Obtención de productos estandarizados
          li.color-primario
            i.fas.fa-plus
            | Disminución de desperdicios
          li.color-primario
            i.fas.fa-plus
            | Mejoras en los procesos
          li.color-primario
            i.fas.fa-plus
            | Aumento de la productividad
      
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0.fw-bold De acuerdo con lo anterior, el control de la calidad en la industria se realiza en los procesos y en los recursos que intervienen en la producción de la prenda, desde su diseño y patronaje; la materia prima, en este caso la tela; los insumos entre los que se destaca el hilo, el empaque, el embalaje y la entrega al cliente asociados a las características de cada proceso y de cada material.
    .row.justify-content-center.align-items-center.mb-1(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        p  El control de calidad se realiza en las siguientes fases:
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12.d-none.d-lg-block
        img(src="@/assets/curso/temas/tema1/img_102.svg")
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12.d-sm-block.d-lg-none
        img(src="@/assets/curso/temas/tema1/img_103.svg")

    
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        p  Mejora continua, con el fin de prever ocurrencias de la no conformidad, y facilitar la toma de decisiones.
    h3.titulo-tercero(data-aos="zoom-in-left") Automatización de control de calidad en la industria textil y confección
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-4 La calidad 4.0 está relacionada con la revolución digital, teniendo en cuenta las tecnologías big data, inteligencia artificial, machine learning, deep learning e internet de las cosas. La automatización de los procesos proporciona agilidad, más seguridad en los datos porque disminuye la presentación de información incorrecta, y más conocimiento sobre cada área de la empresa.
        p.mb-4 La implementación básica se refiere a la utilización de software especializado; de herramientas de calidad como los programas SPSS, Statgraphics Centurion o SAS; de recursos relacionados con internet de las cosas, por ejemplo, la geolocalización con aplicaciones con códigos QR, y las relacionadas con las herramientas Lean Manufacturing.
        .cajon.color-acento-contenido.p-4.mb-4
            p.fw-bold.mb-0 Con la integración de datos y su tratamiento avanzado se puede simular los procesos para mejorar la gestión de calidad. Además, las personas encargadas directamente de la calidad pueden desarrollar actividades de manera remota, sin necesidad de su presencia in situ en la empresa. También puede apoyar la planificación de auditorías en el mejoramiento de la implementación de la metodología 5S.
      .col-sm-12.col-lg-3
        img.d-none.d-lg-block(src="@/assets/curso/temas/tema1/img_20.png")




    Separador  
    #t_1_2.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.2 Gestión de calidad total    
    p.mb-5(data-aos="zoom-in-left") Para realizar una correcta gestión de la calidad en la empresa se debe tener en cuenta los siguientes enfoques:
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-4
        img.d-none.d-lg-block(src="@/assets/curso/temas/tema1/img_21.png")
      .col-sm-12.col-lg-6
        ol.lista-ol--cuadro
          li
            .lista-ol--cuadro__vineta
              span 1
            | #[b Enfoque al cliente:] conocer al cliente, requisitos y expectativas 
          li
            .lista-ol--cuadro__vineta
              span 2
            | #[b Enfoque estratégico:]  establecer objetivo de calidad como clave para la empresa, e incluirlo en su visión
          li
            .lista-ol--cuadro__vineta
              span 3
            | #[b Liderazgo enfocado:] compromiso positivo de la dirección de la empresa
          li
            .lista-ol--cuadro__vineta
              span 4
            | #[b Enfoque en procesos:] control de los procesos 
          li
            .lista-ol--cuadro__vineta
              span 5
            | #[b Orientación a las personas:] involucrar al personal y ofrecerle capacitación permanente, con el fin de aumentar el nivel de compromiso y satisfacción del cliente interno
          li
            .lista-ol--cuadro__vineta
              span 6
            | #[b Enfoque científico:] evaluación de la calidad con evidencias y datos, aplicación del método científico
          li
            .lista-ol--cuadro__vineta
              span 7
            | #[b Mejora continua, innovación y aprendizaje:] todo proceso es susceptible de mejoras, no consiste solo en corregir sino actuar de forma proactiva
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .cajon.color-acento-botones.p-4.mb-4
            p.mb-0.fw-bold La comunicación interna también debe estar bien organizada, contar con un sistema de comunicación adecuado para evitar duplicidades de información que afecten negativamente la gestión de la calidad.
    p.mb-5(data-aos="zoom-in-left") Para reconocer la gestión en los procesos se debe tener en cuenta el ciclo de Deming, sobre el cual se construyen los sistemas de gestión. En la siguiente figura se aprecia cómo se constituye el ciclo de calidad para la mejora continua.
    .row(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6.mx-auto.mb-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 1.
          span
            | Ciclo de Deming 
        img.img-a(src='@/assets/curso/temas/tema1/img_22.svg', alt='El diagrama presenta los pasos del ciclo: planear, hacer, verificar, actuar.')
       
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        h3.titulo-tercero Cultura de la calidad
        p.mb-4 Son los principios de calidad que rigen la forma de actuar de las personas que hacen parte de la organización, para que interactúen entre ellas y así lograr en equipo los objetivos propuestos.
        p Esta base definida en términos de valores y hábitos, del quehacer diario de todos los que trabajan en la empresa, requiere para su implementación la capacitación efectiva y constante, la interacción a través de una comunicación asertiva y eficaz para seguir construyendo una cultura de la calidad sólida; la metodología utilizada son los círculos de calidad desarrollados por Kauro Ishikawa. En la siguiente figura se aprecian sus componentes.
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_23.png')
    
    .fullview-blue
      .row.mb-5(data-aos="zoom-in-left")
        .col-sm-12.col-lg-8.mx-auto.p-5
          .titulo-sexto.color-acento-contenido
            h5 Figura 2.
            span
              | Circulo de calidad
          img.img-a(src='@/assets/curso/temas/tema1/img_24.svg', alt='En el diagrama del circulo de calidad  se aprecian sus componentes así:  Objetivos mejora continua del producto, integrantes son de la misma área, reuniones acordadas en horario diferente al laboral y en otro ambiente,  participación voluntaria, equipos de 3 a 15 personas')
    h3.titulo-tercero(data-aos="zoom-in-left") Metodología de mejoramiento continuo   
    p.mb-3(data-aos="zoom-in-left") La metodología se encuentra enmarcada dentro del ciclo de mejoramiento continuo, en el que se desarrollan trece pasos. De manera que todo el personal involucrado en la empresa debe participar para que el mejoramiento sea constante, ya que es un trabajo diario.
    p.mb-5(data-aos="zoom-in-left") Los elementos del Kaizen son:

    .row.justify-content-between.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
              figure
                img(src='@/assets/curso/temas/tema1/img_25.svg')
          h3.text-center.mb-0.text-primario Trabajo en equipo

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
              figure
                img(src='@/assets/curso/temas/tema1/img_26.svg')
          h3.text-center.mb-0.text-primario Disciplina personal

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
              figure
                img(src='@/assets/curso/temas/tema1/img_27.svg')
          h3.text-center.mb-0.text-primario Moral mejorada

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
              figure
                img(src='@/assets/curso/temas/tema1/img_28.svg')
          h3.text-center.mb-0.text-primario Círculos de calidad

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
                img(src='@/assets/curso/temas/tema1/img_29.svg')
          h3.text-center.mb-0.text-primario Sugerencias para las mejoras

    p.mb-3(data-aos="zoom-in-left") Para conocer sobre la metodología Kaizen, leer la estrategia Kaizen ubicada en las referencias bibliográficas (Lefcovich, 2009).
    p.mb-5(data-aos="zoom-in-left") La estrategia Kaizen fue desarrollada en Japón una vez terminada la II Guerra Mundial, la cual inicia con el análisis del problema; en la siguiente figura podemos observar los diferentes aspectos a tener en cuenta: 
    .row.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10.mx-auto
        .titulo-sexto.color-acento-contenido
          h5 Figura 3.
          span
            | Proceso para la solución de problemas
        img.img-a(src='@/assets/curso/temas/tema1/img_30.svg', alt='La imagen contiene los diferentes aspectos que se deben tener en cuenta para la solución de problemas ellos son:  Sentido común, revisión de diseño, trabajo en equipo, rapeo de procesos, habilidades de liderazgo, diseño de experimentos, flujogramas de despliegues, siete nuevas herramientas administrativas, análisis del árbol de fallas, análisis de valor e ingeniería de valor, six sigma, análisis del modo y efecto de la falla, control estadístico del proceso.')
    p.mb-5(data-aos="zoom-in-left") A continuación, se pueden observar los 13 pasos de la metodología, descritos en la siguiente tabla:
    .row.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10.mx-auto
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1.
          span
            | Pasos de la metodología Kaizen
    .tabla-b.color-acento-contenido.mb-5(data-aos="zoom-in-left")
      .tabla-b__header
        h5.mb-0 Pasos de la metodología Kaizen
      table
        caption Tabla tomada del SENA - Programa Técnico control calidad en confección industrial (2020).
        tr
          td(rowspan="10").fw-bold Planear
        tr
          td.fw-bold 1
          td Identificar el área que requiere mejora
          td Utilizar 5S y mapeo de flujo de valor
        tr
          td.fw-bold 2
          td Identificar/clarificar el objetivo Kaizen
          td Mejorar servicio, reducir defectos, mejorar productividad, entre otros
        tr
          td 3
          td Identificar los miembros del equipo Kaizen
          td Nombrar líder del equipo, miembros de la misma área y de diferente área
        tr
          td.fw-bold 4
          td Completar hoja de preparación del Kaizen
          td Realizar el guion de desarrollo del evento, debe ser aprobado por el líder de área
        tr
          td.fw-bold 5
          td Entender la situación actual
          td Documentar el flujo de información, calcular takt time, diagrama espagueti, y documentación
        tr
          td.fw-bold 6
          td Imaginar una situación ideal
          td Producir al ritmo takt time, introducir técnica poka yoke, eliminar tiempos de espera, analizar movimientos
        tr
          td.fw-bold 7
          td Cuantificar los resultados esperados
          td Determinar mediciones del evento, calcular resultados esperados
        tr
          td.fw-bold 8
          td Desarrollar estrategia Kaizen
          td Identificar obstáculos, utilizar simulaciones y pruebas
        tr
          td.fw-bold 9
          td  Desarrollar plan de acciones Kaizen
          td Documentar acciones, identificar recursos requeridos, establecer responsabilidades, fechas y tiempos
        tr
          td(rowspan="4").fw-bold Hacer
        tr
          td.fw-bold 10
          td Implementar Kaizen
          td Desarrollar el evento según lo planeado, mejorar métodos, modificar layout, observar comportamientos, realizar cambios
        tr
          td.fw-bold 11
          td Verificar los resultados a corto plazo
          td Seguimiento a los colaboradores, verificar progreso, seguimiento al proceso
        tr
          td.fw-bold 12
          td Documentar actividades Kaizen
          td Preparar formatos, registrar información, realizar registros fotográficos
        tr
          td.fw-bold Verificar<br>Actuar
          td.fw-bold 13
          td Confirmar los resultados a largo plazo
          td Realizar seguimiento con programa (a cargo del responsable del evento), presentar resultados y estandarizar, si no se obtiene el resultado deseado volver a iniciar.




    h3.titulo-tercero(data-aos="zoom-in-left") #[i Six sigma ]
    p.mb-5(data-aos="zoom-in-left") Es un modelo de gestión, el objetivo es el mejoramiento de los procesos; se conoce por su sigla en inglés DMAIC cuya traducción está asociada a definir, medir, analizar, mejorar y controlar.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        img.img-a(src='@/assets/curso/temas/tema1/img_31.svg')
    
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-link-2.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Para conocer más sobre el modelo le invitamos a visitar el sitio Web Leansolutions, al cual puede acceder a través del siguiente enlace:
                .col-sm-auto
                  a.boton.color-boton(:href="obtenerLink('/downloads/maquinaria_herramientas_insumos_vf_compressed.pdf')" target="_blank")
                    span.text-sistm Enlace Web
                    i.fas.fa-file-download.text-sistm
    p.mb-5(data-aos="zoom-in-left") En cada fase se utilizan herramientas para el análisis y creación de gráficos como histogramas, diagrama causa efecto, Pareto, gráficos de tendencias, análisis de correlación, capacidad del proceso, gráficos de control, entre otros.
    h3.titulo-tercero(data-aos="zoom-in-left") Costos de calidad
    p.mb-3(data-aos="zoom-in-left") La meta general de la empresa es ser rentable y obtener ganancias, por eso la relación de la calidad con el precio se debe analizar, concientizando al personal sobre su importancia.
    p.mb-5(data-aos="zoom-in-left") Es importante entender y concientizar al personal sobre el control de los costos de calidad. En la siguiente figura se puede observar los tipos de costos de calidad.
    .row.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9.mx-auto
        .titulo-sexto.color-acento-contenido
          h5 Figura 3.
          span
            | Tipos de Costos de Calidad
        img.img-a(src='@/assets/curso/temas/tema1/img_32.svg', alt='En el diagrama se  observan los tipos de costos de calidad:  Costo de  Calidad que comprende la Prevención y como ejemplo el mantenimiento de máquinas y capacitación de personal y la Evaluación como   ejemplo las  inspecciones, pruebas de laboratorio y auditorías internas y externas   y Costos de no calidad que comprenden los fallos internos  como la producción defectuosa, reprocesos, falda de productividad y paradas de producción y fallos externos  como devoluciones y demandas.')
    .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        h3.titulo-tercero(data-aos="zoom-in-left") Sistema de gestión de la calidad, Norma ISO 9001 versión 2015
        p.mb-5 El sistema de gestión de la calidad es una herramienta administrativa, cuenta con una estructura organizada para integrar todos los procesos, e incluye los elementos necesarios para lograr cumplir las necesidades y expectativas del cliente. Obtener la certificación es evidenciar la capacidad que tiene la empresa para cumplir con los requisitos. Una vez certificada la empresa su vigencia es de tres años, con auditorias de seguimiento y una vez pasados los tres años se debe realizar una auditoría de renovación.
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0.fw-bold La certificación es una constancia de valor a nivel internacional. El enfoque de la norma está basado en los riesgos, a través de los cuales la empresa demuestra la gestión de los riesgos y determina las acciones que pueden afectar la capacidad de proporcionar satisfacción al cliente y obtener los resultados esperados de la empresa.
      .col-sm-12.col-lg-4.d-none.d-lg-block
          img.img-a(src='@/assets/curso/temas/tema1/img_33.svg')
    
    .row.justify-content-center.align-items-center.mb-0.bg02(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        p.mb-0.py-4 La norma especifica qué debe hacerse, pero no cómo hacerlo. Para la norma es primordial que la información se encuentre documentada.
    .row.justify-content-center.align-items-center.mt-0.bg03.py-4(data-aos="zoom-in-left")
      .col-sm-12.col-lg-4.d-none.d-lg-block
          img.img-a(src='@/assets/curso/temas/tema1/img_34.png')
      .col-sm-12.col-lg-6
        h3.titulo-tercero(data-aos="zoom-in-left") Introducción
        .row.justify-content-center.mb-5
          .col-sm-12.col-lg-6
            ol.lista-ol--cuadro
              li
              .lista-ol--cuadro__vineta
                span 1
              | Objeto y campo de aplicación 
              li
              .lista-ol--cuadro__vineta
                span 2
              | Referencias normativas
              li
              .lista-ol--cuadro__vineta
                span 3
              | Términos y definiciones
              li
              .lista-ol--cuadro__vineta
                span 4
              | Contexto de la organización
              li
              .lista-ol--cuadro__vineta
                span 5
              | Liderazgo
          .col-sm-12.col-lg-6
            ol.lista-ol--cuadro
              li
              .lista-ol--cuadro__vineta
                span 6
              | Planificación
              li
              .lista-ol--cuadro__vineta
                span 7
              | Apoyo
              li
              .lista-ol--cuadro__vineta
                span 8
              | Operación
              li
              .lista-ol--cuadro__vineta
                span 9
              | Evaluación del desempeño
              li
              .lista-ol--cuadro__vineta
                span 10
              | Mejora
        img.img-a(src='@/assets/curso/temas/tema1/img_35.svg')

    
    
    
    Separador  
    #t_1_3.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.3 Puntos de control en el proceso de confección    
    h3.titulo-tercero(data-aos="zoom-in-left") Puntos de control en patronaje
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_36.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Se debe establecer diferencia entre los puntos de control y los puntos de control crítico para asegurar la garantía de calidad de la prenda. Una vez se analice el flujo de los procesos mediante los diagramas de árbol y flujogramas, se determina en el proceso y en la prenda, los puntos a inspeccionar según su relevancia y así se establece la clasificación.
    p.mb-4(data-aos="zoom-in-left") En el patronaje se debe inspeccionar número de piezas, ancho de costuras, medidas de patrón y de prenda terminada. Además, en las medidas en cortes para unión de piezas, cada lado a unir debe corresponder; se debe disponer del tiempo necesario para realizar la revisión sea en un patrón manual o en el programa especializado.
    p.mb-5(data-aos="zoom-in-left") En el momento de desarrollo del producto se debe realizar la inspección, de tal forma que se compare junto con la muestra, y así pueda ser aprobado y pasar a los procesos de producción.
    h3.titulo-tercero(data-aos="zoom-in-left") Puntos de control en trazo y corte
    p.mb-5(data-aos="zoom-in-left") Una vez desarrollado el trazo, antes de imprimir en el caso que sea digital, y antes de realizar el extendido de la tela se debe inspeccionar el trazo, revisando la correspondencia de piezas y distribución de tallas, teniendo en cuenta la orden de producción, el ancho de trazo y el ancho de tela.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-5 El corte se debe revisar una vez se termina de extender. Antes de iniciar el corte de las unidades de capas y alineación del tendido se debe inspeccionar la apariencia de la tela, también se debe tener cuidado con la separación del corte, sobre todo si se han extendido diferentes rollos de tela en el mismo corte, y verificar el cumplimiento de tiempos de reposo.
        .cajon.color-acento-contenido.p-4
          p.mb-0.fw-bold En la separación, tiqueteado y paqueteo de las piezas, el inspector de calidad debe revisar el corte de las piezas, al comparar con el patronaje de la pieza, contar las piezas del paquete, y verificar el sistema de amarre y rotulado. Es importante disponer de un puesto de trabajo para la inspección, con excelente luz y limpieza para determinar defectos en la tela y en el corte de las piezas. Es necesaria la correcta disposición de las piezas para evitar contaminaciones del paquete con otros colores de estas u otras referencias.
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_37.png')
    h3.titulo-tercero.mb-5(data-aos="zoom-in-left") Puntos de control en confección
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_38.png')
      .col-sm-12.col-lg-5
        p.mb-0 Al tener en cuenta que los procesos dentro de la confección de las prendas comprenden operaciones de preparación, ensamble y terminados, del mismo modo se establecen puntos de control en estas áreas, por tanto,  es importante determinar los puestos de calidad en donde se realizarán las inspecciones por parte del inspector de calidad; en el caso que el sistema de la planta sea modular, cada módulo debe disponer del puesto de calidad con las herramientas para realizar las mediciones y formatos definidos, además de una ubicación estratégica dentro del área.
      
    h3.titulo-tercero(data-aos="zoom-in-left") Puntos de control en el producto en proceso
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_39.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Aunque es muy importante el autocontrol que ejerce cada operario sobre lo que realiza para garantizar la calidad de su trabajo; de igual manera se debe llevar a cabo las inspecciones denominadas “en pie de máquina”, estas se realizan mientras la persona desarrolla las operaciones en su puesto de trabajo, con el fin de detectar de manera temprana defectos y establecer acciones de mejora. 
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .cajon.color-acento-botones.p-4.mb-4
            p.mb-0.fw-bold Cuando en el producto se realizan procesos de estampación o bordados se requiere establecer puntos de control de esos procesos, que son considerados críticos.
    h3.titulo-tercero(data-aos="zoom-in-left") Puntos de control en el producto terminado
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_40.png')
      .col-sm-12.col-lg-5
        p.mb-0  Al finalizar la confección en cada módulo de producción o línea de la referencia se revisa el producto terminado antes de realizar procesos de planchado, de lavandería, empaque y embalaje; pero igualmente se debe inspeccionar una vez se realice el planchado, si es requerido, y su empaque. Se debe establecer las medidas para la atención de prendas que no fueron aceptadas en las inspecciones y las acciones para su tratamiento.
    h3.titulo-tercero(data-aos="zoom-in-left") Puntos de control en confección de lote piloto
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_41.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 El lote piloto son unidades que se confeccionan con el fin de simular la producción de una referencia nueva; desarrollado el nuevo producto, es necesario realizar simulaciones para prever fallas en la producción; la información proporcionada una vez se realice el pilotaje brinda confianza sobre la viabilidad del producto y señala las estrategias a efectuar en el momento de la producción de la prenda.
    h3.titulo-tercero(data-aos="zoom-in-left") Puntos de control en compra de materiales e insumos
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-5
        p.mb-4 En las áreas de bodegas y almacenes se deben realizar las inspecciones necesarias antes de la integración del producto, donde se realiza el alistamiento de los insumos necesarios para la confección y se integran al paquete de las unidades cortadas según las unidades establecidas.
        .cajon.color-acento-botones.p-4.mb-4
            p.mb-0.fw-bold En el caso de las telas se puede apoyar su control con equipos como revisadores para inspeccionar los defectos.
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_42.png')
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-pdf-2.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Complementario - 14.3 Artículo
                .col-sm-auto
                  a.boton.color-boton(:href="obtenerLink('/downloads/maquinaria_herramientas_insumos_vf_compressed.pdf')" target="_blank")
                    span.text-sistm Descargar
                    i.fas.fa-file-download.text-sistm
    
    Separador  
    #t_1_4.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.4 Control de calidad en patronaje    
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_43.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 El control de los procesos consiste en comprender cuáles son las variaciones en las características del producto, encontrar las causas y tomar las decisiones para controlar la variabilidad, eliminando los errores, estandarizando el proceso y estableciendo mejoras para tener una variabilidad controlada.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .cajon.color-acento-botones.p-4
            p.mb-0.fw-bold En el proceso de patronaje, la persona responsable del patronaje de la prenda, junto con el auditor de calidad realizan la revisión del paquete de moldes o patrones que comprenden la pieza. Es importante revisarlos en físico, a pesar de que se desarrolle la prenda en un software especializado.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p Una vez se desarrolla la prenda la validación de los patrones debe estar contenida en un documento de revisión de patronaje.
    h3.titulo-tercero(data-aos="zoom-in-left") Requisitos  de calidad en patronaje
    p.mb-4(data-aos="zoom-in-left") Los productos tienen variables y atributos, las variables son características cuantitativas y los atributos son las cualidades no cuantificables, los cuales constituyen los requisitos de una prenda.
    p.mb-5(data-aos="zoom-in-left") Los requisitos además están clasificados de la siguiente manera:
    .row.justify-content-between.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
                img(src='@/assets/curso/temas/tema1/img_44.svg')
          h3.text-center.mb-3 Explícitos
          p.text-center.mb-0 Declarados por el cliente, según sus expectativas
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
                img(src='@/assets/curso/temas/tema1/img_45.svg')
          h3.text-center.mb-3 Implícitos
          p.text-center.mb-0 Necesarios para que cumplan su función
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
                img(src='@/assets/curso/temas/tema1/img_46.svg')
          h3.text-center.mb-3 Legales o reglamentarios
          p.text-center.mb-0 De acuerdo con el cumplimiento de las leyes
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-sm-2.col-lg-7
                img(src='@/assets/curso/temas/tema1/img_47.svg')
          h3.text-center.mb-3 Relacionados con la empresa
          p.text-center.mb-0 Según las políticas de la empresa
    p.mb-5(data-aos="zoom-in-left") Los requisitos para revisar en patronaje son:
    AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta tarjeta--purple")(data-aos="zoom-in-left")
      .row(titulo="Medidas")
        .col-12
          .row.justify-content-center
            .col-sm-12.col-lg-2
              img(src='@/assets/curso/temas/tema1/img_48.svg')
            .col-sm-12.col-lg-9
              p.mb-0 Del patrón con costuras y sin costuras para comparar medidas con la prenda terminada y correspondencia con la talla, además se debe revisar que las medidas de las piezas sean iguales al unir y que tengan simetría, se puede superponer las piezas para observar que coincidan a sus longitudes..row(titulo="")

      .row(titulo="Cantidad de piezas")
        .col-12
          .row.justify-content-center
            .col-sm-12.col-lg-2
              img(src='@/assets/curso/temas/tema1/img_49.svg')
            .col-sm-12.col-lg-9
              p.mb-0 Correspondencia de piezas respecto al diseño y al dibujo plano del patrón.
      
      .row(titulo="Señalización de pieza")
        .col-12
          .row.justify-content-center
            .col-sm-12.col-lg-2
              img(src='@/assets/curso/temas/tema1/img_50.svg')
            .col-sm-12.col-lg-9
              p.mb-0 Debe contener identificación de la prenda, no se debe prestar a dualidades de información, además debe indicar la cantidad a cortar en cada pieza.
      .row(titulo="Aplomos")
        .col-12
          .row.justify-content-center
            .col-sm-12.col-lg-2
              img(src='@/assets/curso/temas/tema1/img_51.svg')
            .col-sm-12.col-lg-9
              p.mb-0 Indicación clara de las líneas de aplomo de cada pieza.
      .row(titulo="Costuras")
        .col-12
          .row.justify-content-center
            .col-sm-12.col-lg-2
              img(src='@/assets/curso/temas/tema1/img_52.svg')
            .col-sm-12.col-lg-9
              p.mb-0 Márgenes de costura en cada pieza, y la correspondencia con la pieza a unir, por ejemplo, si en el hombro de la pieza del delantero el ancho es de 1 cm de margen de costura, en el hombro posterior debe corresponder a la misma medida.
      .row(titulo="Piquetes y puntos")
        .col-12
          .row.justify-content-center
            .col-sm-12.col-lg-2
              img(src='@/assets/curso/temas/tema1/img_54.svg')
            .col-sm-12.col-lg-9
              p.mb-0 Existencia de puntos y piquetes, alineando las piezas y correspondiendo la unión de puntos y piquetes.
      .row(titulo="Plantillas")
        .col-12
          .row.justify-content-center
            .col-sm-12.col-lg-2
              img(src='@/assets/curso/temas/tema1/img_55.svg')
            .col-sm-12.col-lg-9
              p.mb-0 Funcionalidad de la plantilla y sus medidas.  
    
   
    Separador  
    #t_1_5.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.5 Control de calidad en trazo y corte    
    p.mb-5(data-aos="zoom-in-left") En cada una de las actividades que se llevan a cabo en el área de trazo y corte se establecen controles para revisar y garantizar la calidad de las prendas.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-5 Las personas encargadas de cada actividad en el área deben establecer comunicación permanente y abierta para coordinar el proceso, debido a que el error en esta área se replica igualmente en la producción; por ello, es importante detectar el problema a tiempo, siendo primordial contar con la trazabilidad de la producción para ubicar fácilmente cada lote, poder intervenir oportunamente los productos a corregir y dar respuesta rápida con el fin de solucionar los inconvenientes presentados.
        .cajon.color-acento-contenido.p-4
          p.mb-0.fw-bold Los documentos utilizados en el área para controlar el corte, además de la orden de producción, son las inspecciones en corte para revisar cada actividad. También un formato que se puede anexar en el paqueteo en el que se validen las unidades de cada pieza en cada uno de los paquetes, siendo un apoyo visual importante en el alistamiento del proceso de confección.
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema1/img_56.png')

    h3.titulo-tercero(data-aos="zoom-in-left") Requisitos de calidad en trazo y corte
    p.mb-5(data-aos="zoom-in-left") Los requisitos a revisar en cada actividad son:
    TabsC.color-primario.mb-5(data-aos="zoom-in-left")
      .py-4.py-md-5(titulo="Trazo").bg04
        .row.justify-content-center.align-items-center.mb-5
          .col-sm-12.col-lg-3.d-none.d-lg-block
            img(src='@/assets/curso/temas/tema1/img_57.svg')
          .col-sm-12.col-lg-8
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Alineación de piezas: ] cada pieza debe estar contenida en el trazo conforme a la línea de aplomo
              li.color-primario
                i.fas.fa-plus
                | #[b Organización de piezas: ] con el fin de controlar los rendimientos de telas, es importante la disposición de las piezas, colocando una al lado de la otra y aprovechando líneas o curvas compartidas entre las piezas
              li.color-primario
                i.fas.fa-plus
                | #[b Cantidad de piezas: ] contar el número de piezas que corresponda a cada talla del producto
              li.color-primario
                i.fas.fa-plus
                | #[b Ancho de trazo: ] conforme al ancho útil de la tela
      .py-4.py-md-5(titulo="Tendido").bg04
        .row.justify-content-center.align-items-center.mb-5
          .col-sm-12.col-lg-3.d-none.d-lg-block
            img(src='@/assets/curso/temas/tema1/img_58.svg')
          .col-sm-12.col-lg-8
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Alineación de capas: ] respetar el margen colocado a partir de la base, es decir, la primera capa. También en los extremos debe alcanzar a cubrir el largo del trazo, sobre todo en trazos escalonados
              li.color-primario
                i.fas.fa-plus
                | #[b Uniformidad de tendido: ] el extendido de cada capa no debe tener arrugas
              li.color-primario
                i.fas.fa-plus
                | #[b Cantidad de capas: ] antes de cortar se debe contar el número de capas para que correspondan a las unidades a cortar, según la distribución del trazo
              li.color-primario
                i.fas.fa-plus
                | #[b Tiempos de reposo: ] sobre todo en tejidos de punto para evitar encogimiento, se tiene en cuenta la ficha técnica de la tela y se valida con pruebas que confirmen niveles de encogimiento, que se desarrollan una vez finalicen los tiempos de reposo
              li.color-primario
                i.fas.fa-plus
                | #[b Lado de tela: ] a partir del tipo de trazo se debe respetar el derecho de la tela
              li.color-primario
                i.fas.fa-plus
                | #[b Tela: ] defectos de tela, marcas, piques, marras, entre otras. Cuidar la combinación de rollos y de colores para evitar contaminación entre los colores, debido a los residuos de las fibras en el corte del tejido
    
      .py-4.py-md-5(titulo="Corte").bg04
        .row.justify-content-center.align-items-center.mb-5
          .col-sm-12.col-lg-3.d-none.d-lg-block
            img(src='@/assets/curso/temas/tema1/img_59.svg')
          .col-sm-12.col-lg-8
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Uniformidad: ] respetar el trazo de cada pieza, obedeciendo a curvas y rectas según sea el caso de cada parte de la pieza
              li.color-primario
                i.fas.fa-plus
                |#[b Simetrías: ] mantener las simetrías de cada pieza sosteniendo el colchón o bloque de telas, evitando que se corra para que no afecte la disposición de las capas inferiores
              li.color-primario
                i.fas.fa-plus
                | #[b Piquetes y puntos: ] ubicación de piquetes y en profundidad no mayor a 0,4 cm; en los puntos evitar que se corra la ubicación, y debe tener un tamaño razonable
              li.color-primario
                i.fas.fa-plus
                |#[b Corte de piezas de forro y entretela: ] revisar el material y que las piezas se corten conforme a la ficha técnica y a la programación de la producción

      .py-4.py-md-5(titulo="Tiqueteado").bg04
        .row.justify-content-center.align-items-center.mb-5
          .col-sm-12.col-lg-3.d-none.d-lg-block
            img(src='@/assets/curso/temas/tema1/img_60.svg')
          .col-sm-12.col-lg-8
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Ubicación: ] se coloca en el revés de la tela, en un lugar visible sin que afecte el ensamble
              li.color-primario
                i.fas.fa-plus
                | #[b Descripción: ] la información debe corresponder a cada pieza, contener el número consecutivo de la misma en orden, según el tendido, además debe incluir talla y referencia
      .py-4.py-md-5(titulo="Fusionado").bg04
        .row.justify-content-center.align-items-center.mb-5
          .col-sm-12.col-lg-3.d-none.d-lg-block
            img(src='@/assets/curso/temas/tema1/img_61.svg')
          .col-sm-12.col-lg-8
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Temperatura: ] que corresponda con el material a fusionar
              li.color-primario
                i.fas.fa-plus
                | #[b Tiempo: ] duración en la fusionadora
              li.color-primario
                i.fas.fa-plus
                | #[b Presión: ] ejercida en cada pieza para que la unión sea uniforme
              li.color-primario
                i.fas.fa-plus
                | #[b Alineación y posición: ] que se encuentre derecha y teniendo en cuenta si se debe dejar el ancho de costura
              li.color-primario
                i.fas.fa-plus
                | #[b Limpieza de la máquina: ] para evitar manchas en las prendas fusionadas
      .py-4.py-md-5(titulo="Paqueteado").bg04
        .row.justify-content-center.align-items-center.mb-5
          .col-sm-12.col-lg-3.d-none.d-lg-block
            img(src='@/assets/curso/temas/tema1/img_62.svg')
          .col-sm-12.col-lg-8
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Cantidad: ] unidades de acuerdo con lo determinado para incorporar a la producción, 10 o 20, se prefiere paquetes pequeños que facilitan el manejo, o más unidades según lo establecido por la empresa
              li.color-primario
                i.fas.fa-plus
                | #[b Amarre: ] en el doblado incluir todas las piezas del paquete, con un amarre resistente
              li.color-primario
                i.fas.fa-plus
                | #[b Identificación: ] rotulado de cada paquete con tarjetas que indiquen la información necesaria como talla, número de lote, cantidad, entre otras, que precisen el contenido del paquete
    
    Separador  
    #t_1_6.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.6 Control de calidad en confección    
    p.mb-5(data-aos="zoom-in-left") Tiene en cuenta la distribución de las operaciones, es decir, la hoja de ruta; operaciones de preparación, ensamble y terminados, cada proceso tiene un método, un tiempo estándar, descripción de la maquinaria, pies, guías, fólderes y aditamentos que se deben revisar.
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-5 En los puntos de revisión se realizan inspecciones, en las que se retienen prendas o piezas con defectos para analizar las causas y determinar acciones, así mismo, la revisión se lleva a cabo en los puestos de trabajo, donde la responsabilidad es de cada operario con el acompañamiento y apoyo del auditor de calidad en pie de máquina. Conforme corresponda la inspección se utilizan los formatos de producto terminado y en proceso.
        .cajon.color-acento-contenido.p-4
          p.mb-0.fw-bold Otros factores para tener en cuenta además de los anteriormente mencionados que son directos al proceso, son los factores ambientales como la iluminación, ventilación, temperatura, ruido, espacio, aseo, entre otros; y también los relacionados con el recurso humano como la capacitación del personal y las relaciones interpersonales, aspectos que inciden en los resultados de los productos y por ende, en la calidad de estos.
      .col-sm-12.col-lg-3
        img.d-none.d-lg-block(src='@/assets/curso/temas/tema1/img_63.png')
    p.mb-5(data-aos="zoom-in-left") También se pueden realizar pruebas o ensayos en laboratorios especializados que evalúen la prenda según normas nacionales e internacionales, una de ellas es la prueba de uso, en la que se compara los resultados planteados frente a los obtenidos.
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .tarjeta.color-acento-botones.px-5.py-4
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/curso/temas/tema1/img_64.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 En las pruebas se analizan las fibras, en cuanto a la cantidad, colorimétrica, peso, composición, cambios dimensionales después del lavado, resistencia a la rotura y al desgarre, elongación y elasticidad de la tela, recuperación a las arrugas, resistencia a la abrasión, solidez al color con el frote, al agua, al planchado, resistencia a la formación de motas (pilling), entre otras.
    
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        p.mb-0 En el siguiente cuadro se observa algunos ensayos con la norma relacionada que se pueden realizar a la prenda.
    
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
      .titulo-sexto.color-acento-contenido
          h5 Tabla 2.
          span
            | Pruebas de calidad en laboratorios para prenda terminada
    .tabla-b.color-acento-contenido.mb-5(data-aos="zoom-in-left")
      .tabla-b__header
          h5.mb-0 Pruebas de calidad en laboratorios para prenda terminada
      table
        caption Tabla Recuperada de: Material de formación - Equipo de desarrollo curricular Tec. Control Calidad en Confección Industrial - SENA 2020
        thead
          tr
            th.text-center Ensayo
            th.text-center Norma
        tbody
          tr
            td.w-100 Análisis cualitativo de fibras.
            td.w-100 NTC 1213/AATCC 20
          tr
            td Análisis cuantitativo de fibras.
            td NTC 481: 2012-12-12    ASTMD 629:2008
          tr
            td Cambio de oblicuidad en telas y deformación por torsión en prendas de vestir como resultado de lavado .
            td NTC 5121: 2002-10-30 <br> AATCC 179:2004
          tr
            td Cambios dimensionales en prendas después de lavado en máquina de uso doméstico.
            td NTC 2308 2017-10-18 <br>  AATCC 150 2012 <br> NTC 908: 2018-12-12 <br> AATCC135: 2015
          tr
            td Determinación de la absorción.
            td NTC 2397 / AATCC 79
          tr
            td Determinación de la elongación de tejidos elásticos angostos.
            td ASTMD 5278
          tr
            td Determinación de la humedad. 
            td NTC 1378
          tr
            td Determinación de la masa por unidad de área (peso) de tela.
            td NTC 230: 2010-07-28 <br>  ASTMD 3776/D3776M:2009
          tr
            td Determinación de la recuperación de las arrugas.
            td NTC 1199
          tr
            td Determinación de la resistencia a la formación de motas (Pilling) y otros 
            td NTC 2051-2: 2003-06-26 <br>  ASTMD 3512-02
          tr
            td Determinación de la resistencia a la penetración del agua. Método presión hidrostática. 
            td EN 20811
          tr
            td Determinación de la resistencia al deslizamiento de los hilos de una costura en telas de tejido plano. <br>Parte 1: método de abertura fija en una costura.
            td NTC 1386-1: 2006-11-30 <br> ISO 13936-1:2004
          tr
            td Determinación de la resistencia al estallido de textiles. 
            td NTC 2291/A8TMD3787
          tr
            td Determinación de la resistencia de las telas al desgarre. 
            td NTC 5634: 2008-11-26 <br> ASTMD2261: 2013 <br> NTC 313-2: 2009-12-16 <br> ASTMD 1424: 2009
          tr
            td Determinación de la resistencia de las telas al enganche — método de la maza.
            td NTC 2293/A8TMD3999
          tr
            td Determinación de la solidez del color a la sublimación. 
            td AATCC 117
          tr
            td Determinación de la solidez del color a los disolventes orgánicos. 
            td NTC 1068 /1SO 105-X05
          tr
            td Determinación de la solidez del color al agua clorada. Parte 1: solidez al agua de las piscinas. 
            td NTC 2292-1 / 150 105 E 03
          tr 
            td Determinación de la solidez del color al agua de mar.
            td NTC 850/AATCC 106
          tr 
            td Determinación de la solidez del color al planchado.
            td NTC 766 / ISO 105-X 11
          tr 
            td Determinación de la tendencia a la formación de motas y de pelusa.
            td NTC 2051-1: 2003-04-23<br> ISO 12945-1: 2000<br>NTC 2051-3 ASTMD 4969
          tr 
            td Determinación del ancho de las telas.
            td NTC 228: 2016-05-18<br> ASTM D3774:1996 (2012)
          tr 
            td Determinación del arco y del sesgo en tela de tejido plano y de punto.
            td NTC 3401
          tr 
            td Determinación del contenido de formaldehído. 
            td NORMA ISO 14184-1:2011
          tr 
            td Determinación del daño relacionado con la aguja causado por la costura, en tejido plano y en tejido de punto.
            td NTC 5893 / ASTM D1908
          tr 
            td Determinación del número de hilos de urdimbre y del número de hilos de trama, de tejidos planos.
            td NTC 427: 2018-08-15<br>ASTM D3775: 2017
          tr 
            td Determinación del número de hilos por unidad de longitud de tela, de tejidos de punto.
            td NTC 5656
          tr 
            td Determinación del número de hilos por unidad de longitud de tela, de tejidos de punto.
            td NTC 5656
          tr 
            td Determinación del título del hilo basado en especímenes de longitud corta.
            td NTC 5772 / ASTMD 1059
          tr 
            td Espesor. 
            td NTC 2599
          tr 
            td Evaluación colorimétrica. 
            td NTMD 0151- NTC 4873-2 Y 3
          tr 
            td Flamabilidad en ángulo de 45”. A
            td STM D 1230
          tr 
            td Flamabilidad horizontal. 
            td ASTMD 5132
          tr 
            td Flamabilidad horizontal. 
            td ASTMD 5132
          tr 
            td Flamabilidad vertical. 
            td 6067/ASTMD 6413
          tr 
            td Longitud de caída. 
            td BS 3356
          tr 
            td Longitud de caída. 
            td BS 3356
          tr 
            td Medición de la permeabilidad de los textiles al vapor de agua con fines de control de la calidad. 
            td NTC 6076/15015496
          tr 
            td Metales extraíbles (plomo, cobre, cadmio, níquel, cromo, cobalto, hierro, manganeso, cinc). 
            td NORMA ISO 17072-1:2011
          tr 
            td Método de ensayo para determinar la solidez del color a la transpiración. 
            td NTC 772: 2017-03-22 <br>AATCC 15:2002
          tr 
            td Método de ensayo para determinar la solidez del color al frote. 
            td NTC 786: 2017-03-22<br> AATCC 8:2016
          tr 
            td Método de ensayo para determinar la solidez del color al lavado en seco usando solvente percloroetileno. 
            td NTC 4160/1S0 105D01
          tr 
            td Método de ensayo para la determinación de la solidez del color al lavado doméstico e industrial. 
            td NTC 1155-3: 2017-10-18 <br>AATCC 61:2013   
          tr 
            td Método para determinar el transporte de humedad en textiles. 
            td AATCC 195
          tr 
            td Método para determinar la resistencia a la abrasión plana. 
            td ASTMD 4966
          tr 
            td Método para determinar la resistencia a la rotura y elongación de las telas. Método de la tira. 
            td NORMA NTC 754-2 / ASTM D5034
          tr 
            td Método para determinar la resistencia a la rotura y elongación de las telas. Método del agarre. 
            td NTC 754-1: 2013-10-16 <br>ASTM D5034: 2013
          tr 
            td Método para determinar la resistencia a las costuras en telas de tejido plano. 
            td ASTMD 1683
          tr 
            td Método para determinar la resistencia al desgarre trapezoidal. 
            td ASTM D 5587- NTC 2261/ ISO 9073-4
          tr 
            td Método para determinar las propiedades de estiramiento de telas de tejido de punto de bajo poder. 
            td ASTMD 2594
          tr 
            td Método para determinar las propiedades de estiramiento de telas de tejido plano elaboradas con hilos extensibles. 
            td NORMA NTC 5462 / ASTMD 3107
          tr 
            td Métodos de ensayo para telas no tejidas. Determinación de la masa  por unidad de área. 
            td NTC 2598 <br>ISO 9073-1
          tr 
            td Métodos de ensayo para telas no tejidas. Determinación de la resistencia al desgarre. 
            td NTC 2601 <br>ISO 9073-4
          tr 
            td Métodos de ensayo para telas no tejidas. Determinación del alargamiento y resistencia a la tensión. 
            td NTC 2600 <br>ISO 9073-3
          tr 
            td Métodos de ensayo para telas no tejidas. Determinación del espesor. 
            td NTC 2599 <br>ISO 9073-2
          tr 
            td Permeabilidad al agua por rociado. 
            td AATCC 22
          tr 
            td PH del extracto acuoso de textiles procesados en húmedo. 
            td NTC 5495/AATCC 81
          tr 
            td Porcentaje de rizo y contracción. 
            td ASTMD 3883
          tr 
            td Protección UV. 
            td AS/NZS 4399
          tr 
            td Resistencia a la abrasión de textiles. 
            td NORMA ASTMD 3884
          tr 
            td Resistencia a la tensión y elongación del papel y cartón. 
            td NTC 363
          tr 
            td Resistencia a las costuras en telas de tejido de punto. Método de la resistencia al estallido de textiles. 
            td NTC 2291/ASTMD3787
          tr 
            td Resistencia la abrasión. 
            td AATCC 93
          tr 
            td Solidez del color a la luz- luz solar. Valor hora. 
            td NTC 1479-2 1SO 105- B02
          tr 
            td Solidez del color a la saliva. 
            td ISO 20701
          tr 
            td Solidez del color al agua. 
            td AATCC 107:2013
          tr 
            td Solidez del color al frote circular. 
            td AATCC 116
          tr 
            td Textiles. Determinación de la resistencia al deslizamiento de los hilos de una costura en telas de tejido plano. 
            td  NTC 1386-2: 2006-11-30 <br>ISO 13936-2: 2004
    h3.titulo-tercero Requisitos de calidad en confección
    p.mb-5 Los requisitos que se deben cumplir en la confección y que son objetos de control son:
    .row.justify-content-around.align-items-center.mb-5
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src="@/assets/curso/temas/tema1/img_65.svg")
      .col-sm-12.col-lg-9
        .row.justify-content-between.align-items-center
          .col.mb-3.mb-sm-0
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Costura:] simetría, sin recogidos ni prenses, costuras rectas, respetar márgenes de costura, costura uniforme, marquilla de acuerdo con el cuidado de la prenda, remates uniformes, clase de costuras
              li.color-primario
                i.fas.fa-plus
                | #[b Tela:] con colores uniformes, tela sin arrugas, sin imperfecciones
              li.color-primario
                i.fas.fa-plus
                | #[b Ambiente del taller:] orden y limpieza en piso, puestos de trabajo
              li.color-primario
                i.fas.fa-plus
                | #[b Ajuste de maquinaria:] mantenimiento de la máquina y uso de aditamentos, pies, guías y fólderes, agujas, altura de dientes, presión del pie prénsatela, enhebrado, devanado de hilo, tensión del hilo
              li.color-primario
                i.fas.fa-plus
                | #[b Operario:] manipulación del material, métodos utilizados en la operación
              li.color-primario
                i.fas.fa-plus
                | #[b Instrucciones de cuidado y terminados:] según la norma, tener en cuenta los símbolos y la composición del material, incluidas en la etiqueta adherida en la prenda
    .row.justify-content-center.mb-2(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        p.fw-bold.text-center Listado de defectos:
    .row.justify-content-around.align-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_66.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Falta de tensión en costuras
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_67.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus Costuras recogidas
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_68.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Saltos de costuras
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_69.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Costuras sin pulir
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_70.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Costuras recogidas
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_71.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Costuras sueltas
    
    .row.justify-content-around.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_72.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Costuras rotas
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_73.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Cases de costura
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_74.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Remates nudosos
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_75.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Falta de simetría
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_76.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Rotura en prenda
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_77.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Costuras abiertas

    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_78.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Costuras retendas
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_79.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Salto de puntada
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_80.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Hilos sueltos


    .row.justify-content-center.mb-2(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        p.fw-bold.text-center Defectos en textiles

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_81.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus Manchas de aceite
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_82.png") 
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Mota en tejido
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_83.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Tejido contaminado
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_84.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus Agujero en el tejido
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_85.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus Falla de aguja
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_86.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Lycra rota
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_87.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Tejido barrado
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_88.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus Nudo en el tejido
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_89.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus Quiebres
      .col-sm-12.col-lg-2 
        img.mb-0(src="@/assets/curso/temas/tema1/img_90.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Desgaste
      .col-sm-12.col-lg-2 
        img.mb-0(src="@/assets/curso/temas/tema1/img_91.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  NEPS

    .row.justify-content-center.mb-2(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        p.fw-bold.text-center Defectos en insumos
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_92.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus Cremallera rota
      .col-sm-12.col-lg-2
        img.mb-0(src="@/assets/curso/temas/tema1/img_93.png")
        .text-center.bg05.px-1.py-1.align-content-center.mb-cus  Rotura en cordones, sesgos, cintas
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-10.bg06.py-3
        p.text-center.align-content-center.mb-0 Complementario 1 – Equipo de desarrollo curricular técnico Control calidad en confección industrial SENA, 2020, Listado de defectos
    
    Separador  
    #t_1_7.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.7 Control de calidad en terminados   
    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-3 En los terminados se incluyen procesos de planchado, empaque, embalaje y procesos de acabados como lavandería, estampación y bordado.
        p.mb-5 Puede ser que los procesos de acabados se desarrollen de manera externa a la empresa, es decir, contratando los servicios, por ello la importancia de los puntos de control cuando ingresan a la planta; se deben validar las prendas o piezas una vez se realicen los procesos.
        .cajon.color-acento-contenido.p-4
          p.mb-0.fw-bold El planchado es la última operación del proceso de producción, es necesario que las personas responsables de esta sección tengan los criterios claros para evaluar las prendas que pasarán a esta operación, para la posterior entrega al cliente.
      .col-sm-12.col-lg-3
        img.d-none.d-lg-block(src='@/assets/curso/temas/tema1/img_94.png') 
    h3.titulo-tercero(data-aos="zoom-in-left") Requisitos de calidad en acabados
    p.mb-5(data-aos="zoom-in-left") Los requisitos a revisar en cada una de las actividades del proceso de acabados son:
    .row.justify-content-around.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src="@/assets/curso/temas/tema1/img_95.svg")
      .col-sm-12.col-lg-9
        .row.justify-content-between.align-items-center
          .col.mb-3.mb-sm-0
            ul.lista-ul--color
              li.color-primario
                i.fas.fa-plus
                | #[b Planchado:] uniforme, quiebres según lo especificado, si se debe doblar que no genere arrugas, control en la temperatura para que no queme, limpieza, además del control en la presión y la humedad
              li.color-primario
                i.fas.fa-plus
                | #[b Empaque:] según lo establecido por la empresa, utilizar los recursos como el gancho, bolsa y etiqueta correspondiente
              li.color-primario
                i.fas.fa-plus
                | #[b Embalaje:] tener en cuenta el pedido del cliente, utilizando materiales como cajas, cinta de amarre o zuncho, cinta adhesiva, tensor para la cinta de amarre. Rotular para identificar el contenido, organizar el contenido
              li.color-primario
                i.fas.fa-plus
                | #[b Estampados:] uniformidad del dibujo y colores, posición y ubicación
              li.color-primario
                i.fas.fa-plus
                | #[b Bordados:] tensión del hilo, colores y letras que correspondan al diseño, posición y ubicación
              li.color-primario
                i.fas.fa-plus
                | #[b Rebordados:] alineación y ubicación al colocar pedrería u otros; el diseño debe corresponder al rebordado realizado
              li.color-primario
                i.fas.fa-plus
                | #[b Lavandería:] uniformidad de colores, que el proceso corresponda al solicitado, sin dañar costuras o tejido de la tela

    Separador  
    #t_1_8.titulo-segundo.color-primario(data-aos="zoom-in-left")
      h2 1.8 Control de calidad en insumos, materiales y textiles    
    p.mb-5(data-aos="zoom-in-left") La comunicación con la cadena de abastecimiento es muy importante para solucionar de manera eficiente los problemas derivados que puedan ocurrir en la producción de las prendas.
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_96.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Los espacios disponibles para recibir los diferentes elementos deben cumplir condiciones óptimas de ventilación, iluminación, seguridad, aseo y organización, ya que esto puede afectar los requerimientos de calidad en la cadena productiva. El control de inventarios está relacionado directamente con el control de calidad, para generar mejoras en toda la gestión de la empresa.
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        .cajon.color-acento-contenido.p-4
          p.mb-0.fw-bold.px-4 En las entradas del proceso de producción uno de los recursos son los insumos y materias primas, las revisiones respectivas responden a uno de los principios de calidad, que es hacer las cosas bien desde el principio, asegurando el flujo de los procesos, así mismo, al finalizar las operaciones de producción se requieren materiales para la entrega del producto al cliente, los cuales de igual manera se deben validar.
    h3.titulo-tercero(data-aos="zoom-in-left") Control de calidad en insumos
    p.mb-5(data-aos="zoom-in-left") Los requisitos necesarios para cumplir con las solicitudes de insumos son:
    .tarjeta--container.row.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-6.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema1/img_97.png', alt='Texto que describa la imagen')
        h2.text-center Disponibilidad
        p.mb-0.text-center El tiempo de obtención para su uso
      .col-sm-12.col-lg-6.tarjeta.color-acento-botones.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema1/img_98.png', alt='Texto que describa la imagen')
        h2.text-center Características propias
        p.mb-0.text-center Funcionalidad, composición, tamaño, peso, color, uniformidad de sus características
    p.mb-5(data-aos="zoom-in-left") En los casos de hilos se analizan propiedades como elasticidad, flexibilidad, durabilidad, resistencia a rotura, tenacidad, solidez al color, uniformidad de tono y grosor. En los elásticos es importante realizar pruebas de recuperación de su longitud, teniendo en cuenta el reposo y la tensión ejercida en su elongación.
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .tarjeta.color-acento-botones.px-5.py-4
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/curso/temas/tema1/img_64.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Es importante controlar desperdicios generados en la producción de los insumos, los cuales inciden en el costo del producto, de allí la importancia del control de los consumos en la planta.
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8 
        p.mb-0.px-0.mx-0 El siguiente cuadro muestra pruebas especializadas que se realizan para evaluar características de algunos insumos:
    .row.justify-content-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .titulo-sexto.color-acento-contenido
            h5 Tabla 3.
            span
              | Pruebas de calidad en laboratorios para insumos
    .tabla-b.color-acento-contenido.mb-5(data-aos="zoom-in-left")
      .tabla-b__header
        h5.mb-0 Pruebas de calidad en laboratorios para insumos
      table
        caption Tabla tomada del SENA - programa técnico Control calidad en confección industrial (2020)
        tr
          th.w-10-cus &nbsp;
          th Ensayo
          th Norma
        tr
          td(rowspan="13").fw-bold Cremallera
        tr
          td Análisis cualitativo.
          td NTC 1213/AATCC 20
        tr
          td Análisis cuantitativo.
          td NTC 481: 2012-12-12   <br>  ASTMD 629:2008
        tr
          td Resistencia del freno. 
          td NTC 2512 / BS 3084
        tr
          td Resistencia del deslizador de tira simple en cierres separables.
          td  NTC 2512 / BS 3084
        tr
          td Determinación de las medidas de longitud de los cierres. 
          td NTC 2512 / BS 3084
        tr
          td Resistencia a la carga lateral del cierre. 
          td NTC 2512 / BS 3084
        tr
          td Resistencia lateral del conjunto separable (pin y caja). 
          td NTC 2512 / BS 3084
        tr
          td Resistencia de la paleta del deslizador. 
          td NTC 2512 / BS 3084
        tr
          td Resistencia a la fijación del tope inferior por separación de la tira.
          td &nbsp;
        tr
          td Resistencia del tope superior.
          td  NTC 2512 / BS 3084
        tr
          td Resistencia de la caja retenedora. 
          td NTC 2512 / BS 3084
        tr
          td Método de ensayo para determinar la solidez del color al lavado en seco, usando solvente percloroetileno.
          td NTC 4160/1S0 105D01

        tr
          td(rowspan="6").fw-bold Botones
        tr
          td Análisis cualitativo.
          td NTC 1213/AATCC 20
        tr
          td Dimensiones.
          td NTC 2510
        tr
          td Evaluación tono a tono.
          td NTC 2510
        tr
          td Solidez del color al planchado.
          td NTC 2510
        tr
          td Solidez del color al planchado.
          td NTC 2510
        tr
          td(rowspan="20").fw-bold Hilos
        tr 
          td Análisis cualitativo. 
          td NTC 1213/AATCC 20
        tr 
          td Análisis cuantitativo. 
          td NTC 481: 2012-12-12 <br>ASTMD 629-2008
        tr 
          td Determinación de la densidad lineal del hilo (título de hilo) mediante el método de la madeja. 
          td NTC 842: 2011-05-18 <br>ASTM D1907: 2007
        tr 
          td Determinación de la humedad. 
          td NTC 1378
        tr 
          td Determinación del encogimiento en agua en ebullición. 
          td NTC 2089
        tr 
          td Determinación de las materias extraíbles. 
          td NTC 751
        tr 
          td Determinación de la pilosidad de hebras textiles. 
          td NTC 1153
        tr 
          td Método de ensayo para la uniformidad de hebras textiles, usando equipo de ensayo de capacitancia. 
          td NTC 1153
        tr 
          td Ensayo de propiedades, tensión de hilos, método monofilamento. 
          td NTC 386: 2011-05-18 <br>ASTM D 2256
        tr 
          td Determinación de la solidez del color al agua del mar. 
          td NTC 850/AATCC 106
        tr 
          td Solidez del color al agua. 
          td AATCC 107:2013
        tr 
          td Solidez del color al lavado en seco. 
          td NTC 4160/IS0 105D01

        tr
          td Método de ensayo para determinar la solidez del color a la transpiración. 
          td NTC 772: 2017-03-22 <br>AATCC 15
        tr 
          td Solidez del color al frote lineal. 
          td NTC 786 AATCC 8
        tr
          td Método de ensayo para la determinación de la solidez del color al lavado doméstico e industrial. 
          td NTC 1155-3: 2017-10-18<br>AATCC 61:2013
        tr
          td Solidez del color a la luz- luz solar. 
          td NTC 1479-2 ISO 105- B02
        tr
          td Determinación de torsiones. 
          td NTC 443-NTC 752
        tr
          td Formaldehído libre. 
          td ISO 14184-1:2011
        tr
          td Metales extraíbles (plomo, cobre, cadmio, níquel, cromo, cobalto, hierro, manganeso, cinc). 
          td ISO 17072-1:2011

    h3.titulo-tercero(data-aos="zoom-in-left") Control de calidad de materiales
    p.mb-2(data-aos="zoom-in-left") Los materiales que apoyan la producción como es el caso, en mayor medida, de la papelería, sus especificaciones técnicas deben corresponder a su aplicación en el proceso productivo.
    p.mb-5(data-aos="zoom-in-left") Para validar el uso de los materiales en las diferentes áreas se inspeccionan los siguientes requisitos:
    .row.justify-content-center.align-content-center.mb-5(data-aos="zoom-in-left")
        .col-sm-12.col-lg-5.align-content-center
          .tarjeta-avatar-b.mb-5.h-card.align-content-center
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/temas/tema1/img_99.png' alt='AvatarTop')
            .tarjeta.tarjeta--purple
              .p-4.align-content-center
                h4 Disponibilidad
                p.mb-0 El tiempo de obtención para su uso
        .col-sm-12.col-lg-5.align-content-center
          .tarjeta-avatar-b.mb-5.h-card.align-content-center
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/temas/tema1/img_100.png' alt='AvatarTop')
            .tarjeta.tarjeta--purple
              .p-4.align-content-center
                h4 Características propias
                p.mb-0 Funcionalidad, composición, tamaño, peso, color, uniformidad

    h3.titulo-tercero(data-aos="zoom-in-left") Control de calidad en textiles
    p.mb-3(data-aos="zoom-in-left") En el caso de los textiles, teniendo en cuenta las propiedades asociadas a su composición se realizan las inspecciones que pueden ser observadas con detenimiento, pero es necesario realizar pruebas de laboratorio que garanticen la calidad para su utilización.
    p.mb-5(data-aos="zoom-in-left") Se tienen en cuenta algunas de ellas como muestra el siguiente cuadro:
    .row.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10.mx-auto
        .titulo-sexto.color-acento-contenido
          h5 Tabla 4.
          span
            | Pruebas de calidad en laboratorios para textiles
        .tabla-b.color-acento-contenido.mb-5
          .tabla-b__header
            h5.mb-0 Pruebas de calidad en laboratorios para textiles
          table
            caption Tabla tomada del SENA - programa técnico Control calidad en confección industrial (2020)
            tr
              th Ensayo
              th Norma
            tr 
              td Análisis cualitativo de fibras.
              td NTC 1213/AATCC 20/ASTMD 276
            tr 
              td Análisis cuantitativo.
              td NTC 481: 2012-12-12   ASTMD 629:2008
            tr 
              td Coeficiente de fricción.
              td ASTMD 3412
            tr 
              td Determinación de la densidad lineal (título).
              td NTC 959
            tr 
              td Determinación de las materias extraíbles.
              td NTC 751
            tr 
              td Determinación de los rizos por unidad de longitud.
              td NTC 840
            tr 
              td Determinación de la resistencia a la tracción y alargamiento de fibras individuales.
              td NTC 959
            tr 
              td Libre de formaldehído.
              td ISO 14184-1:2011

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-sm-12.col-lg-9
        p.mb-3 La tela es la materia prima que más consume la prenda, por eso se debe revisar la uniformidad del color, sin deshilados, huecos, motas, contaminación de otros hilos, textura de acuerdo con el tejido, es decir, que no tenga arrugas no relacionadas con su textura, limpieza, anchos de tela parejos, y orillo de tela.
        p.mb-5 Es importante revisar el comportamiento del textil al contacto con el agua y las temperaturas, sobre todo las altas, dado el caso que la pieza necesite que se le realice fusionados, y lo relacionado al planchado. Al lavar la tela se puede observar la recuperación y formación de arrugas, la solidez del color para que no migre cuando se presenten combinaciones de colores en las piezas y uso de insumos.
        .cajon.color-acento-botones.p-4
          p.mb-0.fw-bold También se debe tener en cuenta en las fibras, los efectos del contacto con bacterias y microorganismos, su incidencia en la durabilidad. Asimismo, el contacto con fluidos corporales como sangre, saliva o sudoración (Alonso, 2015).
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema1/img_101.png') 

    .row.justify-content-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-8
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-sm-12.col-lg-2.d-none.d-lg-block
              img(src="@/assets/template/icono-pdf-2.svg")
            .col-sm-12.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Complementario 2 - Manual control de calidad en productos textiles y afines.
                .col-sm-auto
                  a.boton.color-boton(:href="obtenerLink('/downloads/maquinaria_herramientas_insumos_vf_compressed.pdf')" target="_blank")
                    span.text-sistm Descargar
                    i.fas.fa-file-download.text-sistm

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    datosLineaTiempoB: [
      {
        titulo: 'W. Edwards Deming ',
        texto:
          'Refiere el significado de calidad a la elaboración de un producto a bajo costo con características medibles que satisfagan al cliente.',
        icono: require('@/assets/curso/temas/tema1/img_3.svg'),
      },
      {
        titulo: 'Kaoru Ishikawa',
        texto:
          'Resalta el control de todos los procesos y de las personas de la empresa involucradas para obtener un producto más útil, más económico, y que satisfaga al consumidor final.',
        icono: require('@/assets/curso/temas/tema1/img_3.svg'),
      },
      {
        titulo: 'Armand V. Feigenbaum',
        texto:
          'Comprendió que el inicio de la calidad se encuentra en el diseño del producto y finaliza cuando el consumidor lo utiliza.',
        icono: require('@/assets/curso/temas/tema1/img_4.svg'),
      },
      {
        titulo: 'M. Juran ',
        texto:
          'Define calidad como un conjunto de características que satisfacen al cliente, sin tener errores.',
        icono: require('@/assets/curso/temas/tema1/img_5.svg'),
      },
      {
        titulo: 'Philip B. Crosby ',
        texto:
          'Asoció el concepto de calidad al cumplimiento de requisitos y de normas.',
        icono: require('@/assets/curso/temas/tema1/img_6.svg'),
      },
      {
        titulo: 'Valls',
        texto:
          'Resalta que la calidad se relaciona con el cumplimiento de los requisitos del cliente para lograr el desarrollo de la empresa.',
        icono: require('@/assets/curso/temas/tema1/img_7.svg'),
      },
    ],
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
