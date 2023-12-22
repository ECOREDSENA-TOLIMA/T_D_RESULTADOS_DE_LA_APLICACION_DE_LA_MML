<template lang="pug">
.curso-main-container.pb-3.tema1
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Presentación

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Definición

    .row.mb-5
      .col-md-5.mb-3
        figure
            img(src='@/assets/curso/temas/tema1/img-1.png', alt='')

      .col-md-7 
        p La metodología de elaboración de proyectos bajo el enfoque de Marco Lógico (MML) es en sí, una herramienta para la ordenación de información relacionada con un proyecto, basada en el razonamiento lógico; es decir, donde a partir de unas observaciones asumidas como verdaderas, se puede inferir, en ambos sentidos (causas o efectos), otras que, en consecuencia, también serán verdaderas y que se denominan hipótesis. 
        .row.justify-content-center.align-items-center.mb-4
          .col-lg-10.mb-5.mb-lg-0
            .bloque-texto-b.color-secundario.p-4
              .bloque-texto-b__texto
                i.fas.fa-quote-left
                h3.mb-0 El Marco Lógico (ML) se usa principalmente para la indagación de problemas, diseño, ejecución y evaluación de proyectos
                i.fas.fa-quote-right
                span - Ortegón et al. 2005
                
        p El ML cuenta con una herramienta principal que es la Matriz de Marco Lógico (MML). Si bien la matriz es destacable, el enfoque es más completo, pues recoge instrumentos desde el análisis original hasta el análisis prospectivo del proyecto. La MML es el producto de la aplicación del método, que puede visualizarse en las siguientes etapas o fases claramente diferenciadas:

    .row
      .col-md-10.mb-3
        p.mb-5 <strong>1. El análisis de interesados</strong> permite identificar las partes interesadas de un proyecto o intervención de manera directa o indirecta y positiva o negativamente, es decir, busca, identificar quienes se verán implicados con la intervención del proyecto tanto beneficiándose como siendo perjudicados, de manera directa o por sus efectos, de manera indirecta.
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Tabla 1.] <em>Matriz de análisis de interesados</em>
        .tabla-a.color-acento-contenido 
          table
            thead
              tr
                th GRUPOS DE INTERÉS
                th INTERESES
                th PROBLEMAS PERCIBIDOS
                th Enlace
            tbody
              tr
                td 
                td 
                td 
                td 
              tr
                td 
                td 
                td 
                td 
              tr
                td 
                td 
                td 
                td 

      .col-md-2.mb-3
        figure
          img(src='@/assets/curso/temas/tema1/img-2.svg', alt='Imagen decorativa')

    p.mb-5 <strong>2. El análisis</strong> causal o <strong>identificación de problemas,</strong> denominado <strong>árbol de problemas</strong> donde se identifican las causas que son la raíz del árbol, el problema central o a solucionar que representa el tronco del árbol y sus efectos que se ubican en las ramas.

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Árbol de problemas</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-3-1.svg', alt='En la figura 1 se muestra el árbol de problemas en las raíces se encuentran las causas, en el tronco el problema central y en las ramas y hojas los efectos.')
          figcaption Nota. Tomado y adaptado de Coneval.

    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-8.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Árbol de problemas</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-3-2.svg', alt='En la figura 1 se muestra el árbol de problemas en las raíces se encuentran las causas, en el tronco el problema central y en las ramas y hojas los efectos.') 
          figcaption Nota. Tomado y adaptado de Coneval.
    
    p.mb-5 El anterior esquema gráfico o árbol de problemas es insumo y base para la elaboración de:
    
    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 2.] <em>Esquema de árbol de problemas</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-4-1.svg', alt='En la figura 2 se expone un esquema del árbol de problemas que visualiza las causas mediante líneas ascendentes hacia el problema central, así como los efectos que se desprenden de este último.')
          figcaption Nota. Tomado y adaptado de Researchgate.

    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-8.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 2.] <em>Esquema de árbol de problemas</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-4-2.svg', alt='En la figura 2 se expone un esquema del árbol de problemas que visualiza las causas mediante líneas ascendentes hacia el problema central, así como los efectos que se desprenden de este último.') 
          figcaption Nota. Tomado y adaptado de Researchgate.
    
    .row.justify-content-center.align-items-center.mb-5
      .col-12(data-aos="fade-down-right")
        .tarjeta.tarjeta.p-4.mt-4(style="background-color:#CDF5E2")(data-aos="flip-up")
          .row.justify-content-center.align-items-center 
            .col-lg-3.mb-3
              figure(data-aos="fade-right")
                img(src='@/assets/curso/temas/tema1/img-5.svg', alt='Texto que describa la imagen')
            .col-lg-9
              p <strong>3.</strong> Luego con el panorama completo del problema central se proponen en consenso 3 diferentes <strong>alternativas de solución,</strong> donde se debe realizar un análisis validando su efectividad para solucionar el problema central y todas las situaciones problémicas que se generan.
              p Para identificar las alternativas de solución se debe tener en cuenta el árbol de problemas, el análisis de interesados y finalmente, será viable la alternativa que tenga mayor impacto en la solución, garantice su resultado, requiera menor tiempo de ejecución e inversión.
    
    p.mb-5 <strong>4.</strong> El análisis de objetivos y fines, denominado <strong>árbol de objetivos</strong> donde las situaciones problémicas identificadas en el árbol de problemas se transforman en objetivos a alcanzar y estrategias a implementar para su realización, que gráficamente será:

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 3.] <em>Árbol de Objetivos</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-6-1.svg', alt='En la figura 3 se expone un esquema del árbol de objetivos que visualiza en el tronco los medios, en el inicio de las ramas la situación deseada, en la parte alta de las ramas los fines y en la copa del árbol los resultados.')

    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-8.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 3.] <em>Árbol de Objetivos</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-6-2.svg', alt='En la figura 3 se expone un esquema del árbol de objetivos que visualiza en el tronco los medios, en el inicio de las ramas la situación deseada, en la parte alta de las ramas los fines y en la copa del árbol los resultados.') 

    p.mb-5 La relación existente entre el árbol de problemas y el árbol de objetivos es:

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 4.] <em>Relación entre árbol de problemas y árbol de objetivos</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-7-1.svg', alt='En la figura 4 se muestra la relación entre las partes del árbol de problemas y las partes del árbol de objetivos, siendo el primero la base para el desarrollo del segundo.')
          figcaption Nota. Tomado y adaptado de Proyecto educativo Tingo.

    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-8.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 4.] <em>Relación entre árbol de problemas y árbol de objetivos</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-7-2.svg', alt='En la figura 4 se muestra la relación entre las partes del árbol de problemas y las partes del árbol de objetivos, siendo el primero la base para el desarrollo del segundo.') 
          figcaption Nota. Tomado y adaptado de Proyecto educativo Tingo.

    p Es decir, que el problema central será el objetivo central del proyecto, las causas serán los medios o estrategias que se deben implementar para dar solución al problema y alcanzar el objetivo y, por último, los fines serán los objetivos específicos del proyecto, los cuales al ser alcanzados uno a uno, darán respuesta a cada problema menor o causa identificada en el árbol de problemas, por lo cual desaparecerán sus efectos.
    p.mb-5 Es importante tener en cuenta que la redacción de los objetivos deberá ser en “verbos en infinitivo” es decir, terminados en ar, er, ir. Ejemplo: realizar, consolidar, planear, gestionar, establecer, inferir, distinguir. Al definir los objetivos con claridad se facilita el seguimiento y la medición del avance de los objetivos en cada etapa.

    .row.mb-4
      .col-md-2.mb-3
        figure
            img(src='@/assets/curso/temas/tema1/img-8.svg', alt='')
      .col-md-10
        p 5. Matriz de planificación de marco lógico: en la elaboración de la matriz de marco lógico se requiere conocer todo el proceso que se ha llevado a cabo desde el análisis de interesados lo que permite conocer a mayor profundidad el problema, causas y efectos, y de esta manera se plantearán los aspectos o componentes necesarios que permitan evidenciar la efectividad de la intervención o proyecto.
        p A continuación, se presenta el esquema de matriz de marco lógico.

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 5.] <em>Matriz de planificación de marco lógico </em>
        figure
          img(src='@/assets/curso/temas/tema1/img-9-1.svg', alt='En la figura 5 se muestra la matriz de planificación de marco lógico, que incluye en las columnas el resumen narrativo, indicadores, medios de verificación y supuestos; y en las filas fin, propósito, componentes y actividades.')
          figcaption Nota. Tomado y adaptado de Legalidad por México.

    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-8.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 5.] <em>Matriz de planificación de marco lógico </em>
        figure
          img(src='@/assets/curso/temas/tema1/img-9-2.svg', alt='En la figura 5 se muestra la matriz de planificación de marco lógico, que incluye en las columnas el resumen narrativo, indicadores, medios de verificación y supuestos; y en las filas fin, propósito, componentes y actividades.') 
          figcaption Nota. Tomado y adaptado de Legalidad por México.

    p.mb-5 Es importante que al construir esta matriz se tenga en cuenta la lógica para el análisis e interpretación de la matriz, sin lo cual esta estrategia perderá su validez como lo muestra el siguiente ejemplo:

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 6.] <em>Lógica para el análisis e interpretación de la matriz de planificación de marco lógico</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-10.svg', alt='En la figura 6 se muestra un ejemplo de la interpretación de la matriz de planificación de marco lógico, señalando las relaciones entre los objetivos con los supuestos.')
          figcaption Nota. Tomado y adaptado de Pinterest.

    .row.mt-5.mb-2
      .col-10.col-md-10.col-lg-12.movil
        a.anexo.mb-4(:href="obtenerLink('/downloads/anexo_1_Figura6_Logica_para_el_analisis_e_interpretacion_de_la_matriz_de_planificacion_de_marco_logico.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p <strong>Descargar.</strong> Figura 6, Lógica para el análisis e interpretación de la matriz de planificación de marco lógico.

    p.mb-5 Con la figura anterior se evidencia la relación entre cada aspecto o componente de la matriz, como un análisis de lo particular a lo general que permite evidenciar el paso a paso para dar solución a lo que inicialmente fue identificado como problema central, así:

    .row.justify-content-center.align-items-center.mb-5
      .col-10(data-aos="fade-down-right")
        .cajon.color-primario.p-4(style="background-color:#CDF5E2")
          .row.mb-0
            .col-md-2.mb-3
              figure
                  img(src='@/assets/curso/temas/tema1/img-11.svg', alt='')
            .col-md-10
              p La actividad realizada es evaluada mediante indicadores los cuales informarán el porcentaje de avance de su realización, los medios de verificación son las evidencias que permiten a cualquier interesado verificar su realización y como esto ha dado un resultado que para el momento de su ejecución deja de ser un supuesto.

    p.mb-5 Por esta razón, el análisis será horizontal y ascendente y estarán interconectados con los resultados hasta llegar al propósito del proyecto, lo que garantiza una intervención integral y efectiva al problema identificado.

    Separador 

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Elementos que componen el enfoque de marco lógico

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 7.] <em> Diagrama de relación entre los principales componentes del enfoque de marco lógico</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-12-1.svg', alt='En la figura 7 se muestra un diagrama de la relación entre los principales componentes del marco lógico, incluye el árbol de problemas, el árbol de alternativas y la matriz de marco lógico.')
          figcaption Nota. Tomado de la guía para la formulación de proyectos de inversión del sector agropecuario de la FAO (2017).

    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-8.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 7.] <em> Diagrama de relación entre los principales componentes del enfoque de marco lógico</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-12-2.svg', alt='En la figura 7 se muestra un diagrama de la relación entre los principales componentes del marco lógico, incluye el árbol de problemas, el árbol de alternativas y la matriz de marco lógico.') 
          figcaption Nota. Tomado de la guía para la formulación de proyectos de inversión del sector agropecuario de la FAO (2017).

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 8.] <em>Resumen narrativo del proyecto</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-13-1.svg', alt='En la figura 8 se muestra el resumen narrativo de un proyecto el cual contiene por medio de una tabla: el fin, el propósito, los resultados esperados y las actividades.')
          figcaption Nota. Tomado de la guía para la formulación de proyectos de inversión del sector agropecuario de la FAO (2017).

    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-8.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 8.] <em>Resumen narrativo del proyecto</em>
        figure
          img(src='@/assets/curso/temas/tema1/img-13-2.svg', alt='En la figura 8 se muestra el resumen narrativo de un proyecto el cual contiene por medio de una tabla: el fin, el propósito, los resultados esperados y las actividades.') 
          figcaption Nota. Tomado de la guía para la formulación de proyectos de inversión del sector agropecuario de la FAO (2017).

    Separador 

    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Pasos para elaborar la MML

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-12.desktop(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/img-14-1.svg', alt='En la figura 8 se muestra el resumen narrativo de un proyecto el cual contiene por medio de una tabla: el fin, el propósito, los resultados esperados y las actividades.')
          
    .row.justify-content-center.align-items-center.mt-5.mb-4
      .col-10.col-md-10.col-lg-12.movil(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema1/img-14-2.svg', alt='En la figura 8 se muestra el resumen narrativo de un proyecto el cual contiene por medio de una tabla: el fin, el propósito, los resultados esperados y las actividades.') 
    
    Separador 

    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Recomendaciones para desarrollar la MML

    .row.mb-4
      .col-md-2.mb-3
        figure
            img(src='@/assets/curso/temas/tema1/img-15.svg', alt='')
      .col-md-10
        p El resumen narrativo del proyecto corresponde a la primera columna del marco lógico. Establece los cuatro niveles jerárquicos entre:
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1
            | El fin (objetivo general del proyecto), 
          li 
            .lista-ol--cuadro__vineta
              span 2
            | El propósito (objetivo específico del proyecto),
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Los resultados esperados (componentes del proyecto) 
          li 
            .lista-ol--cuadro__vineta
              span 4
            | Las actividades. Permite responder a las siguientes cuestiones: ¿cuál es la finalidad del proyecto?, ¿qué impactos y efectos directos se espera lograr con el proyecto?, ¿qué bienes o servicios deberán ser producidos? y ¿qué se hará para producir dichos bienes o servicios? 

    Separador 
    
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Herramientas digitales se pueden utilizar para la elaboración de la MML

    .row.mt-5.mb-4.align-items-stretch(data-aos="fade-right")
      .col-lg-6.col-md-12
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/img-16.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul(style="background-color:#CDF5E2")
            .p-5
              p <strong>Paquetes ofimáticos de Microsoft, OpenOffice o de Macros.</strong>

      .col-lg-6.col-md-12
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/img-17.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul(style="background-color:#CDF5E2")
            .p-5
              p <strong>Plantillas de organización de proyectos de los paquetes ofimáticos.</strong>

    Separador 

    #t_1_6.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.6 Ejemplo de la MML

    .row.justify-content-center.align-items-center.mb-4
      .col-10.col-md-10.col-lg-12.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 9.] <em>Ejemplo de MML de un proyecto agropecuario</em>
        figure
          img.mb-3(src='@/assets/curso/temas/tema1/img-18.svg', alt='En la figura 9 se muestra un ejemplo de la metodología de marco lógico de un proyecto agropecuario, incluye la descripción del proyecto, los indicadores, medios de verificación y los supuestos.')
          figcaption Nota. Tomado del libro “Diseño de proyectos de inversión con el enfoque de marco lógico, Medina. (2009).

    .row.mt-5.mb-2
      .col-10.col-md-10.col-lg-12.movil
        a.anexo.mb-4(:href="obtenerLink('/downloads/anexo_2_Figura_9_Ejemplo_de_MML_de_un_proyecto_agropecuario.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p <strong>Descargar.</strong> Figura 9, Ejemplo de MML de un proyecto agropecuario.







</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
