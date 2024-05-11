<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Control de calidad
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Con el crecimiento de la industrialización se requería ejercer control en los procesos para disminuir los desperdicios y los reprocesos en la producción, cada vez con niveles de unidades más altas, necesitando estandarizar las características del producto fabricado.
            p.mb-0 A partir de lo mencionado, revisar la producción proporciona una mayor confianza por parte del cliente, mejora la competitividad y sirve como una herramienta en la administración de la empresa.
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-6
        p Es importante mencionar los principios de calidad para el control de la misma:
    
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-5
        img(src='@/assets/curso/temas/tema1/img_2.svg', alt='')
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
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-7
        p Acciones que permiten encaminar la empresa hacia el proceso de control de calidad.

    Separador  
    #t_1_1.titulo-segundo.color-primario
      h2 1.1 Concepto de calidad
    p.mb-5 Existen varias definiciones, y cada persona puede determinar un concepto propio, además de tener en cuenta las definiciones de los estudiosos en el tema, entre los cuales se encuentran:
    LineaTiempoB.color-secundario.mb-5(:datos="datosLineaTiempoB")
    .cajon.color-acento-contenido.p-4.mb-5
        p.mb-0.fw-bold Al tener en cuenta los términos de los estudiosos se puede determinar que satisfacción, cliente, necesidades, mercado y expectativas son las palabras comunes que engloban el concepto para concluir que la calidad es el nivel de satisfacción del cliente, cumpliendo con los requisitos, es decir, con las necesidades y expectativas del cliente.
    h3.titulo-tercero Concepto control de calidad
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-9
        p.mb-4 Una vez se tienen definidos los objetivos y los requisitos de calidad del producto se deben controlar las variaciones de esas características, cualidades o especificaciones exigidas por el cliente o de acuerdo con la norma.
        p.mb-4 Mejor llamado como control estadístico de la calidad es el proceso conformado por una serie de técnicas para analizar el comportamiento de las variaciones de los requisitos del producto, con el fin de establecer acciones que mejoren su calidad, en pro de aumentar las ventas y la productividad de la empresa.
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0.fw-bold El control de calidad no solo está encaminado a las inspecciones del producto terminado, también es importante realizar las inspecciones del producto durante el proceso de producción.
      .col-sm-12.col-lg-3
        img(src='@/assets/curso/temas/tema1/img_8.png', alt='')
    .row.justify-content-center.align-items-center.mb-5
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
        img(src='@/assets/curso/temas/tema1/img_9.svg', alt='')

    .row.justify-content-center.mb-5
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
    .row.mb-5
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
      .row.justify-content-center.align-items-center.mb-5.p-5
        .col-sm-12.col-lg-3
          img(src="@/assets/curso/temas/tema1/img_11.svg")
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
    .row.justify-content-center.align-items-center.mb-5
        .col-sm-12.col-lg-9           
          .cajon.color-acento-contenido.p-4.mb-4
            p.fw-bold.mb-0 Conforme con lo mencionado anteriormente, también podemos clasificar los requisitos de acuerdo con las características directas del producto, de la organización o de los externos, como el cliente y la normatividad.
    .row.justify-content-center.align-items-center.mb-5
        .col-sm-12.col-lg-9
          p Dado que se presentan variaciones en los productos es preciso permitir tolerancias, que son márgenes permisibles de variación y aceptación.
    .row.justify-content-center.align-items-center.mb-5
        .col-sm-12.col-lg-9
          h3.titulo-tercero Antecedentes y evolución de control de calidad
          p.mb-3 Al ubicarse de manera temporal en el cambio de la fabricación artesanal a la industrialización, derivado de la Revolución Industrial y de los cambios en la producción masificada, se presentó un auge en la industria del automóvil liderada por Henry Ford en la década de 1910, en la que se daba los inicios de la calidad en las inspecciones del producto terminado. 
          p.mb-0 Con el avance de la tecnología, de los estudios del trabajo y de la implementación de técnicas para aumentar la productividad, que buscaba la estandarización del producto, la calidad ganó importancia dentro del desempeño del negocio, es decir, a partir de los niveles de calidad del producto se empezó a satisfacer al cliente. Hoy en día, derivado de la cuarta Revolución Industrial, el proceso de control de calidad se viene automatizando para el análisis y predicción de fallas, sin olvidar que las personas siguen haciendo parte del proceso, al gestionar de manera integral la cadena de suministro. 

        .col-sm-12.col-lg-3
          img(src="@/assets/curso/temas/tema1/img_12.png")
    SlyderA(tipo='b').bg01.p-5.mb-5
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

    .row.justify-content-center
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
    h3.titulo-tercero Control de calidad en la industria textil y confección
    p.mb-5 Se controla la calidad con el fin de mantener y corregir los defectos, errores o no conformidad que se presenta durante la producción de la prenda. Por tanto, se desarrolla según las variables y atributos del producto. 
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-6
        p Los beneficios de implementar las herramientas para el control de calidad son:
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-3
        img(src="@/assets/curso/temas/tema1/img_19.svg")

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
      
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-9
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0.fw-bold De acuerdo con lo anterior, el control de la calidad en la industria se realiza en los procesos y en los recursos que intervienen en la producción de la prenda, desde su diseño y patronaje; la materia prima, en este caso la tela; los insumos entre los que se destaca el hilo, el empaque, el embalaje y la entrega al cliente asociados a las características de cada proceso y de cada material.
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-6
        p  El control de calidad se realiza en las siguientes fases:
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-6
        p  PENDIENTE
    
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-8
        p  Mejora continua, con el fin de prever ocurrencias de la no conformidad, y facilitar la toma de decisiones.
    h3.titulo-tercero Automatización de control de calidad en la industria textil y confección
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-9
        p.mb-4 La calidad 4.0 está relacionada con la revolución digital, teniendo en cuenta las tecnologías big data, inteligencia artificial, machine learning, deep learning e internet de las cosas. La automatización de los procesos proporciona agilidad, más seguridad en los datos porque disminuye la presentación de información incorrecta, y más conocimiento sobre cada área de la empresa.
        p.mb-4 La implementación básica se refiere a la utilización de software especializado; de herramientas de calidad como los programas SPSS, Statgraphics Centurion o SAS; de recursos relacionados con internet de las cosas, por ejemplo, la geolocalización con aplicaciones con códigos QR, y las relacionadas con las herramientas Lean Manufacturing.
        .cajon.color-acento-contenido.p-4.mb-4
            p.fw-bold.mb-0 Con la integración de datos y su tratamiento avanzado se puede simular los procesos para mejorar la gestión de calidad. Además, las personas encargadas directamente de la calidad pueden desarrollar actividades de manera remota, sin necesidad de su presencia in situ en la empresa. También puede apoyar la planificación de auditorías en el mejoramiento de la implementación de la metodología 5S.
      .col-sm-12.col-lg-3
        img(src="@/assets/curso/temas/tema1/img_20.png")




    Separador  
    #t_1_2.titulo-segundo.color-primario
      h2 1.2 Gestión de calidad total    
    p.mb-5 Para realizar una correcta gestión de la calidad en la empresa se debe tener en cuenta los siguientes enfoques:
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-4
        img(src="@/assets/curso/temas/tema1/img_21.png")
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
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-10
        .cajon.color-acento-botones.p-4.mb-4
            p.mb-0.fw-bold La comunicación interna también debe estar bien organizada, contar con un sistema de comunicación adecuado para evitar duplicidades de información que afecten negativamente la gestión de la calidad.
    p.mb-5 Para reconocer la gestión en los procesos se debe tener en cuenta el ciclo de Deming, sobre el cual se construyen los sistemas de gestión. En la siguiente figura se aprecia cómo se constituye el ciclo de calidad para la mejora continua.
    .row
      .col-sm-12.col-lg-6.mx-auto.mb-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 1.
          span
            | Ciclo de Deming 
        img.img-a(src='@/assets/curso/temas/tema1/img_22.svg', alt='El diagrama presenta los pasos del ciclo: planear, hacer, verificar, actuar.')
       
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-9
        h3.titulo-tercero Cultura de la calidad
        p.mb-4 Son los principios de calidad que rigen la forma de actuar de las personas que hacen parte de la organización, para que interactúen entre ellas y así lograr en equipo los objetivos propuestos.
        p Esta base definida en términos de valores y hábitos, del quehacer diario de todos los que trabajan en la empresa, requiere para su implementación la capacitación efectiva y constante, la interacción a través de una comunicación asertiva y eficaz para seguir construyendo una cultura de la calidad sólida; la metodología utilizada son los círculos de calidad desarrollados por Kauro Ishikawa. En la siguiente figura se aprecian sus componentes.
      .col-sm-12.col-lg-3
        img.img-a(src='@/assets/curso/temas/tema1/img_23.png')
    
    .fullview-blue
      .row.mb-5
        .col-sm-12.col-lg-8.mx-auto.p-5
          .titulo-sexto.color-acento-contenido
            h5 Figura 2.
            span
              | Circulo de calidad
          img.img-a(src='@/assets/curso/temas/tema1/img_24.svg', alt='En el diagrama del circulo de calidad  se aprecian sus componentes así:  Objetivos mejora continua del producto, integrantes son de la misma área, reuniones acordadas en horario diferente al laboral y en otro ambiente,  participación voluntaria, equipos de 3 a 15 personas')
    h3.titulo-tercero(data-aos='fade-right') Metodología de mejoramiento continuo   
    p.mb-3 La metodología se encuentra enmarcada dentro del ciclo de mejoramiento continuo, en el que se desarrollan trece pasos. De manera que todo el personal involucrado en la empresa debe participar para que el mejoramiento sea constante, ya que es un trabajo diario.
    p.mb-5 Los elementos del Kaizen son:

    .row.justify-content-between.align-items-center.mb-5
      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/img_25.svg')
          h3.text-center.mb-0.text-primario Trabajo en equipo

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/img_26.svg')
          h3.text-center.mb-0.text-primario Disciplina personal

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/img_27.svg')
          h3.text-center.mb-0.text-primario Moral mejorada

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema1/img_28.svg')
          h3.text-center.mb-0.text-primario Círculos de calidad

      .col-sm-12.col-lg-2
        .tarjeta--boton.color-primario.p-4.h-anexo-2
          .row.justify-content-center.mb-3
            .col-7
                img(src='@/assets/curso/temas/tema1/img_29.svg')
          h3.text-center.mb-0.text-primario Sugerencias para las mejoras

    p.mb-3 Para conocer sobre la metodología Kaizen, leer la estrategia Kaizen ubicada en las referencias bibliográficas (Lefcovich, 2009).
    p.mb-5 La estrategia Kaizen fue desarrollada en Japón una vez terminada la II Guerra Mundial, la cual inicia con el análisis del problema; en la siguiente figura podemos observar los diferentes aspectos a tener en cuenta: 
    .row.mb-5
      .col-sm-12.col-lg-10.mx-auto
        .titulo-sexto.color-acento-contenido
          h5 Figura 3.
          span
            | Proceso para la solución de problemas
        img.img-a(src='@/assets/curso/temas/tema1/img_30.svg', alt='La imagen contiene los diferentes aspectos que se deben tener en cuenta para la solución de problemas ellos son:  Sentido común, revisión de diseño, trabajo en equipo, rapeo de procesos, habilidades de liderazgo, diseño de experimentos, flujogramas de despliegues, siete nuevas herramientas administrativas, análisis del árbol de fallas, análisis de valor e ingeniería de valor, six sigma, análisis del modo y efecto de la falla, control estadístico del proceso.')
    p.mb-5 A continuación, se pueden observar los 13 pasos de la metodología, descritos en la siguiente tabla:
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-6
        p  PENDIENTE
    h3.titulo-tercero(data-aos='fade-right') #[i Six sigma ]
    p.mb-5 Es un modelo de gestión, el objetivo es el mejoramiento de los procesos; se conoce por su sigla en inglés DMAIC cuya traducción está asociada a definir, medir, analizar, mejorar y controlar.
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-10
        img.img-a(src='@/assets/curso/temas/tema1/img_31.svg')
    
    .row.justify-content-center
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
    p.mb-5 En cada fase se utilizan herramientas para el análisis y creación de gráficos como histogramas, diagrama causa efecto, Pareto, gráficos de tendencias, análisis de correlación, capacidad del proceso, gráficos de control, entre otros.
    h3.titulo-tercero(data-aos='fade-right') Costos de calidad
    p.mb-3 La meta general de la empresa es ser rentable y obtener ganancias, por eso la relación de la calidad con el precio se debe analizar, concientizando al personal sobre su importancia.
    p.mb-5 Es importante entender y concientizar al personal sobre el control de los costos de calidad. En la siguiente figura se puede observar los tipos de costos de calidad.
    .row.mb-5
      .col-sm-12.col-lg-9.mx-auto
        .titulo-sexto.color-acento-contenido
          h5 Figura 3.
          span
            | Tipos de Costos de Calidad
        img.img-a(src='@/assets/curso/temas/tema1/img_32.svg', alt='En el diagrama se  observan los tipos de costos de calidad:  Costo de  Calidad que comprende la Prevención y como ejemplo el mantenimiento de máquinas y capacitación de personal y la Evaluación como   ejemplo las  inspecciones, pruebas de laboratorio y auditorías internas y externas   y Costos de no calidad que comprenden los fallos internos  como la producción defectuosa, reprocesos, falda de productividad y paradas de producción y fallos externos  como devoluciones y demandas.')
    .row.justify-content-center.align-items-center
      .col-sm-12.col-lg-8
        h3.titulo-tercero(data-aos='fade-right') Sistema de gestión de la calidad, Norma ISO 9001 versión 2015
        p.mb-5 El sistema de gestión de la calidad es una herramienta administrativa, cuenta con una estructura organizada para integrar todos los procesos, e incluye los elementos necesarios para lograr cumplir las necesidades y expectativas del cliente. Obtener la certificación es evidenciar la capacidad que tiene la empresa para cumplir con los requisitos. Una vez certificada la empresa su vigencia es de tres años, con auditorias de seguimiento y una vez pasados los tres años se debe realizar una auditoría de renovación.
        .cajon.color-acento-botones.p-4.mb-4
          p.mb-0.fw-bold La certificación es una constancia de valor a nivel internacional. El enfoque de la norma está basado en los riesgos, a través de los cuales la empresa demuestra la gestión de los riesgos y determina las acciones que pueden afectar la capacidad de proporcionar satisfacción al cliente y obtener los resultados esperados de la empresa.
      .col-sm-12.col-lg-4
          img.img-a(src='@/assets/curso/temas/tema1/img_33.svg')
    
    .row.justify-content-center.align-items-center.mb-0.bg02
      .col-sm-12.col-lg-10
        p.mb-0.py-4 La norma especifica qué debe hacerse, pero no cómo hacerlo. Para la norma es primordial que la información se encuentre documentada.
    .row.justify-content-center.align-items-center.mt-0.bg03.py-4
      .col-sm-12.col-lg-4
          img.img-a(src='@/assets/curso/temas/tema1/img_34.png')
      .col-sm-12.col-lg-6
        h3.titulo-tercero(data-aos='fade-right') Introducción
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
    #t_1_3.titulo-segundo.color-primario
      h2 1.3 Puntos de control en el proceso de confección    
    h3.titulo-tercero(data-aos='fade-right') Puntos de control en patronaje
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_36.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Se debe establecer diferencia entre los puntos de control y los puntos de control crítico para asegurar la garantía de calidad de la prenda. Una vez se analice el flujo de los procesos mediante los diagramas de árbol y flujogramas, se determina en el proceso y en la prenda, los puntos a inspeccionar según su relevancia y así se establece la clasificación.
    p.mb-4 En el patronaje se debe inspeccionar número de piezas, ancho de costuras, medidas de patrón y de prenda terminada. Además, en las medidas en cortes para unión de piezas, cada lado a unir debe corresponder; se debe disponer del tiempo necesario para realizar la revisión sea en un patrón manual o en el programa especializado.
    p.mb-5 En el momento de desarrollo del producto se debe realizar la inspección, de tal forma que se compare junto con la muestra, y así pueda ser aprobado y pasar a los procesos de producción.
    h3.titulo-tercero(data-aos='fade-right') Puntos de control en trazo y corte
    p.mb-5 Una vez desarrollado el trazo, antes de imprimir en el caso que sea digital, y antes de realizar el extendido de la tela se debe inspeccionar el trazo, revisando la correspondencia de piezas y distribución de tallas, teniendo en cuenta la orden de producción, el ancho de trazo y el ancho de tela.
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-9
        p.mb-5 El corte se debe revisar una vez se termina de extender. Antes de iniciar el corte de las unidades de capas y alineación del tendido se debe inspeccionar la apariencia de la tela, también se debe tener cuidado con la separación del corte, sobre todo si se han extendido diferentes rollos de tela en el mismo corte, y verificar el cumplimiento de tiempos de reposo.
        .cajon.color-acento-contenido.p-4
          p.mb-0.fw-bold En la separación, tiqueteado y paqueteo de las piezas, el inspector de calidad debe revisar el corte de las piezas, al comparar con el patronaje de la pieza, contar las piezas del paquete, y verificar el sistema de amarre y rotulado. Es importante disponer de un puesto de trabajo para la inspección, con excelente luz y limpieza para determinar defectos en la tela y en el corte de las piezas. Es necesaria la correcta disposición de las piezas para evitar contaminaciones del paquete con otros colores de estas u otras referencias.
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_37.png')
    h3.titulo-tercero.mb-5(data-aos='fade-right') Puntos de control en confección
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_38.png')
      .col-sm-12.col-lg-5
        p.mb-0 Al tener en cuenta que los procesos dentro de la confección de las prendas comprenden operaciones de preparación, ensamble y terminados, del mismo modo se establecen puntos de control en estas áreas, por tanto,  es importante determinar los puestos de calidad en donde se realizarán las inspecciones por parte del inspector de calidad; en el caso que el sistema de la planta sea modular, cada módulo debe disponer del puesto de calidad con las herramientas para realizar las mediciones y formatos definidos, además de una ubicación estratégica dentro del área.
      
    h3.titulo-tercero(data-aos='fade-right') Puntos de control en el producto en proceso
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_39.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 Aunque es muy importante el autocontrol que ejerce cada operario sobre lo que realiza para garantizar la calidad de su trabajo; de igual manera se debe llevar a cabo las inspecciones denominadas “en pie de máquina”, estas se realizan mientras la persona desarrolla las operaciones en su puesto de trabajo, con el fin de detectar de manera temprana defectos y establecer acciones de mejora. 
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-8
        .cajon.color-acento-botones.p-4.mb-4
            p.mb-0.fw-bold Cuando en el producto se realizan procesos de estampación o bordados se requiere establecer puntos de control de esos procesos, que son considerados críticos.
    h3.titulo-tercero(data-aos='fade-right') Puntos de control en el producto terminado
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_40.png')
      .col-sm-12.col-lg-5
        p.mb-0  Al finalizar la confección en cada módulo de producción o línea de la referencia se revisa el producto terminado antes de realizar procesos de planchado, de lavandería, empaque y embalaje; pero igualmente se debe inspeccionar una vez se realice el planchado, si es requerido, y su empaque. Se debe establecer las medidas para la atención de prendas que no fueron aceptadas en las inspecciones y las acciones para su tratamiento.
    h3.titulo-tercero(data-aos='fade-right') Puntos de control en confección de lote piloto
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_41.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 El lote piloto son unidades que se confeccionan con el fin de simular la producción de una referencia nueva; desarrollado el nuevo producto, es necesario realizar simulaciones para prever fallas en la producción; la información proporcionada una vez se realice el pilotaje brinda confianza sobre la viabilidad del producto y señala las estrategias a efectuar en el momento de la producción de la prenda.
    h3.titulo-tercero(data-aos='fade-right') Puntos de control en compra de materiales e insumos
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-5
        p.mb-4 En las áreas de bodegas y almacenes se deben realizar las inspecciones necesarias antes de la integración del producto, donde se realiza el alistamiento de los insumos necesarios para la confección y se integran al paquete de las unidades cortadas según las unidades establecidas.
        .cajon.color-acento-botones.p-4.mb-4
            p.mb-0.fw-bold En el caso de las telas se puede apoyar su control con equipos como revisadores para inspeccionar los defectos.
      .col-sm-12.col-lg-3.d-none.d-lg-block
        img.img-a(src='@/assets/curso/temas/tema1/img_42.png')
    .row.justify-content-center
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
    #t_1_4.titulo-segundo.color-primario
      h2 1.4 Control de calidad en patronaje    
    .row.justify-content-center.mb-5
      .col-sm-12.col-lg-9
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/temas/tema1/img_43.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-4 El control de los procesos consiste en comprender cuáles son las variaciones en las características del producto, encontrar las causas y tomar las decisiones para controlar la variabilidad, eliminando los errores, estandarizando el proceso y estableciendo mejoras para tener una variabilidad controlada.
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-8
        .cajon.color-acento-botones.p-4
            p.mb-0.fw-bold En el proceso de patronaje, la persona responsable del patronaje de la prenda, junto con el auditor de calidad realizan la revisión del paquete de moldes o patrones que comprenden la pieza. Es importante revisarlos en físico, a pesar de que se desarrolle la prenda en un software especializado.
    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-9
        p Una vez se desarrolla la prenda la validación de los patrones debe estar contenida en un documento de revisión de patronaje.
    h3.titulo-tercero(data-aos='fade-right') Requisitos  de calidad en patronaje
    p.mb-4 Los productos tienen variables y atributos, las variables son características cuantitativas y los atributos son las cualidades no cuantificables, los cuales constituyen los requisitos de una prenda.
    p.mb-5 Los requisitos además están clasificados de la siguiente manera:
    .row.justify-content-between.align-items-center.mb-5
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-7
                img(src='@/assets/curso/temas/tema1/img_44.svg')
          h3.text-center.mb-3 Explícitos
          p.text-center.mb-0 Declarados por el cliente, según sus expectativas
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-7
                img(src='@/assets/curso/temas/tema1/img_45.svg')
          h3.text-center.mb-3 Implícitos
          p.text-center.mb-0 Necesarios para que cumplan su función
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-7
                img(src='@/assets/curso/temas/tema1/img_46.svg')
          h3.text-center.mb-3 Legales o reglamentarios
          p.text-center.mb-0 De acuerdo con el cumplimiento de las leyes
      .col-sm-12.col-lg-3
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-7
                img(src='@/assets/curso/temas/tema1/img_47.svg')
          h3.text-center.mb-3 Relacionados con la empresa
          p.text-center.mb-0 Según las políticas de la empresa
    p.mb-5 Los requisitos para revisar en patronaje son:
    AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta tarjeta--purple")
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
    #t_1_5.titulo-segundo.color-primario
      h2 1.5 Control de calidad en trazo y corte    
    
    Separador  
    #t_1_6.titulo-segundo.color-primario
      h2 1.6 Control de calidad en confección    
    
    Separador  
    #t_1_7.titulo-segundo.color-primario
      h2 1.7 Control de calidad en terminados    
    
    Separador  
    #t_1_8.titulo-segundo.color-primario
      h2 1.8 Control de calidad en insumos, materiales y textiles    
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
