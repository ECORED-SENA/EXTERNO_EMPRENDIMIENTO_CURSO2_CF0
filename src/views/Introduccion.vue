<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    figure.mt-4#inicio
      img(src='@/assets/template/tema-0-1.png', alt='Texto que describa la imagen')
    .row
      .col-12.px-5
        .row.rounded-15.bg-blanco-deg.pb-5.pt-3.mt-n4   
          .col-1.col-lg-2
          .col-2.col-lg-2.d-none.d-md-flex.border-top-amarillo.mt-2
          .col-md-6.col-lg-4.text-center.mb-4
            .h4 Ruta de navegación del MOOC
          .col-2.col-lg-2.d-none.d-md-flex.border-top-amarillo.mt-2
          .col-1
    .row.px-5.mt-n5
      .col-6.col-md-4.col-xl-2.px-4.px-xl-3.indicador__container
        a.boton.row.h-100.px-3.box-shadow.rounded-15.py-3.bg-blanco(href="#navegar")
          figure.px-4.px-xl-3.d-none.d-md-flex
            img(src='@/assets/template/tema-0-2.svg', alt='Texto que describa la imagen').px-5.px-xl-3
          .h4.text-center.px-0.text-small.px-3.mt-2 ¿Cómo navegar este MOOC?
      .col-6.col-md-4.col-xl-2.px-4.px-xl-3
        a.boton.row.h-100.px-3.box-shadow.rounded-15.py-3.bg-blanco(href="#dirigido")
          figure.px-4.px-xl-3.d-none.d-md-flex
            img(src='@/assets/template/tema-0-3.svg', alt='Texto que describa la imagen').px-5.px-xl-3
          .h4.text-center.px-0.text-small.px-3.mt-2 ¿A quién va dirigido?
      .col-6.col-md-4.col-xl-2.px-4.px-xl-3
        a.boton.row.h-100.px-3.box-shadow.rounded-15.py-3.bg-blanco(href="#competencia")
          figure.px-4.px-xl-3.d-none.d-md-flex
            img(src='@/assets/template/tema-0-4.svg', alt='Texto que describa la imagen').px-5.px-xl-3
          .h4.text-center.px-0.text-small.px-3.mt-2 ¿Cuál es la competencia?
      .col-6.col-md-4.col-xl-2.px-4.px-xl-3.mt-3.mt-xl-0
        a.boton.row.h-100.px-3.box-shadow.rounded-15.py-3.bg-blanco(href="#metodologia")
          figure.px-4.px-xl-3.d-none.d-md-flex
            img(src='@/assets/template/tema-0-5.svg', alt='Texto que describa la imagen').px-5.px-xl-3
          .h4.text-center.px-0.text-small.px-3.mt-2.pb-xl-0 ¿Qué metodología sigue?
      .col-6.col-md-4.col-xl-2.px-4.px-xl-3.mt-3.mt-xl-0
        a.boton.row.h-100.px-3.box-shadow.rounded-15.py-3.bg-blanco(href="#fases")
          figure.px-4.px-xl-3.d-none.d-md-flex
            img(src='@/assets/template/tema-0-6.svg', alt='Texto que describa la imagen').px-5.px-xl-3
          .h4.text-center.px-0.text-small.px-3.mt-2 ¿Cuáles son la fases del proyecto?
      .col-6.col-md-4.col-xl-2.px-4.px-xl-3.mt-3.mt-xl-0
        a.boton.row.h-100.px-3.box-shadow.rounded-15.py-3.bg-blanco(href="#requisitos")
          figure.px-4.px-xl-3.d-none.d-md-flex
            img(src='@/assets/template/tema-0-7.svg', alt='Texto que describa la imagen').px-5.px-xl-3
          .h4.text-center.px-0.text-small.px-3.mt-2.pb-xl-0 ¿Qué requisitos debo cumplir?
    .row.mt-5#navegar.mx-0
      .col-8.col-md-5.col-lg-4.col-xl-3.bg-azul-oscuro.py-2.align-self-center
        .h4.text-white ¿Cómo navegar este MOOC?
      a.col-2.mt-4.offset-5.offset-lg-6.offset-xl-7(href="#inicio")
        figure.px-1.px-lg-2.px-xl-2
          img(src='@/assets/template/arrow.svg').px-1.px-lg-4.px-xl-5
      p.mt-4 Visualiza el video de introducción de navegación del MOOC
      figure.mt-4
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/X40s2LFASXQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.mt-5#dirigido.mx-0.border-top-gris
      .col-10.col-lg-8.col-xl-7.bg-azul-oscuro.py-2.mt-4.align-self-center
        .h4.text-white ¿A quién va dirigido este MOOC y qué saberes previos requiere?
      a.col-2.mt-4.offset-lg-2.offset-xl-3(href="#inicio")
        figure.px-1.px-lg-2.px-xl-2
          img(src='@/assets/template/arrow.svg').px-1.px-lg-4.px-xl-5
    .row.mt-5.position-relative(data-aos="fade")
      .col-5.position-absolute.mt-lg-5.d-none.d-lg-flex
        figure.mt-lg-5.mt-xl-0
          img(src='@/assets/template/tema-0-8.png', alt='Texto que describa la imagen').px-4.px-xl-5
      .col-12.col-lg-9.py-5.px-5.offset-0.offset-lg-3.bg-gris-claro.rounded-15
        .row
          .col-12.col-lg-10.offset-lg-2.px-4
            p Este #[strong MOOC] está dirigido a jóvenes que quieren emprender una idea de negocio o que ya se identifican como emprendedores.
            p.mt-3 Buscamos jóvenes que estén motivados a hacer realidad su proyecto y ser emprendedores digitales. Por ello, no se requieren saberes previos.
            .cajon.color-acento-botones.p-4.mt-3
              p Pueden participar bachilleres, técnicos, tecnólogos o profesionales de cualquier núcleo básico del conocimiento.
    .row.mt-5#competencia.mx-0.border-top-gris
      .col-10.col-lg-7.col-xl-6.bg-azul-oscuro.py-2.mt-4.align-self-center
        .h4.text-white ¿Cuál es la competencia y propósitos de este MOOC?
      a.col-2.mt-4.offset-lg-3.offset-xl-4(href="#inicio")
        figure.px-lg-2.px-xl-1
          img(src='@/assets/template/arrow.svg').px-lg-4.px-xl-5
    .row.mt-5(data-aos="flip-left")
      .col.col-lg-8
        .h4 Competencia
        p.mt-4 Promueve el emprendimiento juvenil y la cultura emprendedora de acuerdo a las habilidades y competencias personales que favorezcan la toma de decisiones y la aplicación de técnicas de negociación.
        .h4.mt-5 Propósitos
        ul.lista-ul.mt-3
          li.mt-2
            i.fas.fa-angle-right
            | Planear los objetivos personales de acuerdo a tu meta, sueño o proyecto de  emprendimiento.
          li.mt-2
            i.fas.fa-angle-right
            | Identificar las amenazas y debilidades en el proceso de toma de decisiones.
          li.mt-2 
            i.fas.fa-angle-right
            | Diseñar la estrategia emprendedora de acuerdo con los objetivos propuestos.
          li.mt-2
            i.fas.fa-angle-right
            | Sustentar el plan de acción teniendo en cuenta los elementos de una estrategia emprendedora.
      .col-4.d-none.d-lg-flex
        figure
          img(src='@/assets/template/tema-0-9.png', alt='Texto que describa la imagen')
    .row.mt-5#metodologia.mx-0.border-top-gris
      .col-8.col-lg-6.col-xl-4.bg-azul-oscuro.py-2.mt-4.align-self-center
        .h4.text-white  ¿Qué metodología sigue el MOOC?
      a.col-2.mt-4.offset-2.offset-lg-4.offset-xl-6(href="#inicio")
        figure.px-lg-2.px-xl-1
          img(src='@/assets/template/arrow.svg').px-lg-4.px-xl-5
    p.mt-4 En este MOOC se emplean las siguientes metodologías de trabajo:
    .row.mt-4.px-4(data-aos="slide-left")
      .col-5.d-none.d-xl-flex.align-self-center
        figure
          img(src='@/assets/template/tema-0-10.png', alt='Texto que describa la imagen')
      .col-12.col-xl-7.px-5
        .row.rounded-15.py-4.border-gris.bg-gris-deg
          .col-11.col-lg-10.offset-1.offset-lg-2.position-relative.px-4.border-right-azul-4
            p #[strong Autodirección del aprendizaje] de manera que puedes recorrer los contenidos y realizar la mayoría de las actividades de aprendizaje en los horarios y en la forma que mejor se adapte a tus necesidades.
            figure.position-absolute(style="top:-20%; left:-27%").d-none.d-xl-flex.mt-xl-3
              img(src='@/assets/template/tema-0-11.svg', alt='Texto que describa la imagen').w-20.px-3.px-xl-0
        .row.rounded-15.py-4.border-gris.bg-gris-deg.mt-4
          .col-11.col-lg-10.offset-1.offset-lg-2.position-relative.px-4.border-right-rosa-4
            p #[strong Storytelling basado en casos de emprendimiento], en la que mediante la narración se presentan de manera integrada los conceptos de la unidad. 
            figure.position-absolute(style="top:-20%; left:-27%").d-none.d-xl-flex
              img(src='@/assets/template/tema-0-12.svg', alt='Texto que describa la imagen').w-20.px-3.px-xl-0
        .row.rounded-15.py-4.border-gris.bg-gris-deg.mt-4
          .col-11.col-lg-10.offset-1.offset-lg-2.position-relative.px-4.border-right-azul-4
            p.py-3 #[strong Actividades de interacción] en las que podrás construir tu proyecto final fase a fase en cada unidad.  
            figure.position-absolute(style="top:-28%; left:-27%").d-none.d-xl-flex.mt-xl-3
              img(src='@/assets/template/tema-0-13.svg', alt='Texto que describa la imagen').w-20.px-3.px-xl-0
        .row.rounded-15.py-4.border-gris.bg-gris-deg.mt-4
          .col-11.col-lg-10.offset-1.offset-lg-2.position-relative.px-4.border-right-rosa-4
            p.py-3 #[strong Foro Networking] al que podrás acceder y encontrar colegas, socios o mentores para tus ideas de negocio.
            figure.position-absolute(style="top:-8%; left:-27%").d-none.d-xl-flex
              img(src='@/assets/template/tema-0-14.svg', alt='Texto que describa la imagen').w-20.px-3.px-xl-0
    .row.mt-5
      .col-8.col-md-6.col-lg-4.offset-2.offset-md-3.offset-lg-4.bg-azul-deg.py-2
        .h4.text-center.text-white Requerimientos tecnológicos
    
    TabsC.color-acento-botones.mt-5(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Requisitos o conocimientos informáticos")
        .row
          .col-12.col-lg-6.align-self-center
            .h4 Requisitos o conocimientos informáticos
            p.mt-3 Se recomienda que tengas instalado multimedia/parlantes para poder revisar los contenidos audiovisuales. 
          .col-6.d-none.d-lg-flex
            figure
              img(src='@/assets/template/tema-0-15.png', alt='Texto que describa la imagen')
      .py-3.py-md-4(titulo="Conexión a internet")
        .row
          .col-6.d-none.d-lg-flex
            figure
              img(src='@/assets/template/tema-0-17.png', alt='Texto que describa la imagen')
          .col-12.col-lg-6.align-self-center
            .h4 Conexión a internet
            p.mt-3 Es necesario que el dispositivo que dispongas esté conectado a internet con suficiente ancho de banda, al menos de 5Mbps (Megabits por segundo).
      .py-3.py-md-4(titulo="Software necesarios")
        .row
          .col-12.col-lg-6.align-self-center
            .h4 Software necesarios
            p.mt-3 Dentro del recorrido de aprendizaje por el curso se encuentran diferentes formatos de archivos. Para poder visualizar correctamente estos archivos, o abrirlos según los casos, es necesario que tenga instalados en el dispositivo los programas que relacionamos a continuación:
            .tarjeta.color-primario.p-3.mt-4.bg-gris-deg.px-5.px-lg-2
              .row.justify-content-around.align-items-center
                .col-3.col-sm-2.col-lg-1(style="width:19.33%; margin-left: -50px;").d-none.d-lg-flex
                  img(src="@/assets/template/tema-0-19.png")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0.px-0
                      h3.mb-1.text-sistema Navegador Google Chrome
                      p.text-small.text-sistema Navegador más usado en la actualidad por su sencillez y rapidez.
                    .col-sm-auto.me-4
                      a.boton.color-acento-contenido(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download
          .col-6.d-none.d-lg-flex.align-self-center
            figure
              img(src='@/assets/template/tema-0-18.png', alt='Texto que describa la imagen')
          .tarjeta.color-primario.p-3.mt-4.bg-gris-deg.px-5
            .row.justify-content-around.align-items-center
              .col-3.col-sm-2.col-lg-1(style="width:10%; margin-left: -70px;").d-none.d-lg-flex
                img(src="@/assets/template/tema-0-20.png")
              .col
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0.px-0
                    h3.mb-1.text-sistema Adobe Acrobat Reader
                    p.text-small.text-sistema Acrobat Reader es un visor de archivos de texto en un formato muy extendido en la red. Si no tiene Acrobat Reader instalado en el ordenador sigue estos pasos.
                  .col-sm-auto
                    a.boton.color-acento-contenido(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download
    .row.mt-5#fases.mx-0.border-top-gris
      .col-10.bg-azul-oscuro.py-2.mt-4.align-self-center
        .h4.text-white  ¿Cuáles son las fases del proyecto, qué evidencias debo entregar y cómo se evalúan?
      a.col-2.mt-4(href="#inicio")
        figure.px-lg-2.px-xl-1
          img(src='@/assets/template/arrow.svg').px-lg-4.px-xl-5
    .row.mt-5(data-aos="slide-right")
      .col-12.col-lg-7
        p El proyecto está estructurado en cuatro fases que aportan la construcción de la idea de negocio.
        LineaTiempoD.color-primario.mt-4
          p.text-small(numero="1" titulo="Fase 1. Crear mi modelo de emprendimiento") #[strong Evidencia de aprendizaje:] audio de presentación de la idea de negocio  – #[strong.text-azul 10 puntos.] 
          
          p.text-small(numero="2" titulo="Fase 2. Aplicar el análisis   DOFA al modelo de mi emprendimiento") #[strong Evidencia de aprendizaje:] imagen de la Matriz DOFA del emprendimiento – #[strong.text-azul 10 puntos.] 
          
          p.text-small(numero="3" titulo="Fase 3 Estructurar la estrategia de mi emprendimiento") #[strong Evidencia de aprendizaje:] documento de la estrategia de emprendimiento  – #[strong.text-azul 10 puntos.]
          
          p.text-small(numero="4" titulo="Fase 4 ¡Al ruedo! Presentar el Plan de acción de mi  emprendimiento") #[strong Evidencia de aprendizaje:] Evidencia de aprendizaje: presentación del plan de acción del emprendimiento – #[strong.text-azul 70 puntos.]
      .col-5.d-none.d-lg-flex
        figure
          img(src='@/assets/template/tema-0-21.png', alt='Texto que describa la imagen')
    .cajon.color-acento-botones.p-4.mt-4
      p En las unidades 1, 2 y 3 debes entregar las evidencias de aprendizaje como requisito y en la fase 4 te debes concentrar en presentar el Plan de acción de tu emprendimiento, que será retroalimentado al final del curso por el tutor que te acompaña.
    .row.mt-5#requisitos.mx-0.border-top-gris
      .col-10.col-lg-7.col-xl-6.bg-azul-oscuro.py-2.mt-4.align-self-center
        .h4.text-white ¿Qué requisitos debo cumplir para certificarme?
      a.col-2.mt-4.offset-lg-3.offset-xl-4(href="#inicio")
        figure.px-lg-2.px-xl-1
          img(src='@/assets/template/arrow.svg').px-lg-4.px-xl-5
    p.mt-5 Para obtener el certificado del curso deberás alcanzar un mínimo de 70 puntos de los 100 posibles. El puntaje lo obtienes al completar las siguientes actividades:
    .row.mt-5.d-none.d-lg-flex(data-aos="fade-right")
      .col-3
        .row.mt-5.px-4
          .col-12.text-center.rounded-20.box-shadow.px-1
            figure.px-5.mt-n5.d-none.d-xl-flex
              img(src='@/assets/template/tema-0-23.svg', alt='Texto que describa la imagen').px-3
            .h4.mt-4.mt-xl-3 Fase 1
            p.mt-3.mb-5.px-3 Audio de presentación de tu idea de negocio. #[br] #[strong 10 puntos]
        .row.mt-5.px-4
          .col-12.text-center.rounded-20.box-shadow.px-1.mt-5
            figure.px-5.mt-n5.d-none.d-xl-flex
              img(src='@/assets/template/tema-0-23.svg', alt='Texto que describa la imagen').px-3
            .h4.mt-4.mt-xl-3 Fase 2
            p.mt-3.mb-5.px-3 Imagen de la Matriz DOFA de tu emprendimiento. #[br] #[strong 10 puntos]

      .col-6
        figure.d-none.d-md-flex
          img(src='@/assets/template/tema-0-22.png', alt='Texto que describa la imagen').w-75.margin-0-auto
      .col-3
        .row.mt-5.px-4
          .col-12.text-center.rounded-20.box-shadow.px-1
            figure.px-5.mt-n5.d-none.d-xl-flex
              img(src='@/assets/template/tema-0-23.svg', alt='Texto que describa la imagen').px-3
            .h4.mt-4.mt-xl-3 Fase 3
            p.mt-3.mb-5.px-3 Cuadro de tu estrategia de emprendimiento. #[br]  #[strong 10 puntos]
        .row.mt-5.px-4
          .col-12.text-center.rounded-20.box-shadow.px-1.mt-5.pb-4
            figure.px-5.mt-n5.d-none.d-xl-flex
              img(src='@/assets/template/tema-0-23.svg', alt='Texto que describa la imagen').px-3
            .h4.mt-4.mt-xl-3 Fase 4
            p.mt-3.mb-5.px-3 Presentación del plan de acción de tu emprendimiento. #[br] #[strong 70 puntos]
    
    .row.mt-4.d-flex.d-lg-none
      LineaTiempoD.color-primario
        .row(numero="1" titulo="Fase 1")
          p Infografía de las competencias emprendedoras dentro del contexto de oportunidades. - #[strong 10 puntos]

        .row(numero="2" titulo="Fase 2") 
          p Publicación de un reel en Instagram de tu idea de negocio – #[strong 10 puntos]

        .row(numero="3" titulo="Fase 3")
          p Canvas de tu idea de negocio con la integración de herramientas digitales –  #[strong 10 puntos]

        .row(numero="4" titulo="Fase 4")
          p Elevator Pitch de tu idea de negocio – #[strong 70 puntos]
          


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.fa-angle-right:before
  color: #E9027D
</style>
