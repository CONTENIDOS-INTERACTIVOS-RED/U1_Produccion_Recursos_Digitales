<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'4. Herramientas para la gamificación y evaluación: Kahoot, Quizizz, Mentimeter'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/1.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") En la educación mediada por tecnologías digitales, la gamificación ha emergido como una estrategia efectiva para aumentar la motivación, el compromiso y la participación activa del estudiantado. Aplicada al entorno educativo, la gamificación implica el uso de dinámicas, mecánicas y elementos propios de los juegos (como recompensas, puntuaciones o competencia amistosa) para enriquecer procesos de enseñanza-aprendizaje. En este escenario, herramientas como Kahoot, Quizizz y Mentimeter, han ganado popularidad por su capacidad de transformar evaluaciones tradicionales en experiencias interactivas, atractivas y participativas. 
    
        .bg-color-3.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema4/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Estas plataformas permiten a los docentes diseñar cuestionarios, encuestas y juegos, en tiempo real, que promueven la retroalimentación inmediata, el aprendizaje colaborativo y la autoevaluación. Además, favorecen el desarrollo de habilidades como el pensamiento crítico, la toma de decisiones rápida y la retención de información clave. 
        p Su accesibilidad y facilidad de uso las convierten en aliadas valiosas, tanto para la educación virtual como para la presencial.
        h5 Conozca cada una de estas plataformas:
    
    TabsC.color-primario.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Kahoot" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Kahoot
            p Plataforma de aprendizaje basada en juegos, que utiliza cuestionarios de opción múltiple y otras actividades interactivas para involucrar a los estudiantes y evaluar su comprensión, de una manera divertida y competitiva (Suelves, 2018).
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Uso en gamificación y evaluación</b>. Permite crear y organizar cuestionarios en vivo, encuestas y sondeos; los estudiantes participan utilizando sus propios dispositivos; ofrece un sistema de clasificación y puntuación para la gamificación y genera informes para la evaluación.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Enlace de la herramienta. <a href="https://kahoot.it/" target="_blank">Aquí</a>
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema4/3.svg', alt='')
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Quizizz" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Quizizz
            p Plataforma de aprendizaje basada en juegos, que ofrece funciones similares a Kahoot, con opciones para cuestionarios a ritmo del estudiante, lecciones interactivas e informes más detallados (Rodríguez, 2019).
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Uso en gamificación y evaluación</b>. Permite crear cuestionarios y lecciones; ofrece opciones para juegos en vivo o tareas asincrónicas; incluye varios tipos de preguntas; utiliza memes y temas para aumentar la participación y proporciona informes detallados sobre el rendimiento de los estudiantes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Enlace de la herramienta. <a href="https://quizizz.com/?lng=es-ES" target="_blank">Aquí</a>
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema4/4.svg', alt='')
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Mentimeter" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Mentimeter
            p Herramienta de presentación interactiva que permite a los presentadores crear encuestas, nubes de palabras, sesiones de preguntas y respuestas y cuestionarios para involucrar a su audiencia y recopilar comentarios en tiempo real.
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Uso en gamificación y evaluación</b>. Permite crear presentaciones interactivas con varios tipos de preguntas; visualización en tiempo real de las respuestas; opciones para cuestionarios y competiciones; útil para la evaluación formativa y la participación de la audiencia.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema4/5.svg', alt='')
      
    p.mb-5 Estas herramientas aprovechan los principios de la gamificación para hacer que el aprendizaje sea más atractivo y agradable, lo que se alinea con la investigación que destaca el impacto positivo de las experiencias de aprendizaje interactivas y divertidas en la motivación y la retención de conocimientos. 

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema4/6.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-1.p-4.mb-3(data-aos="fade-left")
          p.mb-0 La funcionalidad principal de estas herramientas se basa en la mecánica de los juegos, lo que respalda directamente el principio pedagógico de que la gamificación mejora la participación y la motivación en el aprendizaje. 
          p El énfasis de Mentimeter en la retroalimentación y visualización en tiempo real, junto con la puntuación inmediata en Kahoot y Quizizz, se alinea con la importancia de la retroalimentación oportuna en el proceso de aprendizaje. Estas herramientas brindan valiosas oportunidades para la evaluación formativa y permiten a los instructores evaluar la comprensión de los estudiantes en tiempo real. 
        p(data-aos="fade-left") Las características de estas herramientas que proporcionan retroalimentación inmediata, tanto a estudiantes como a instructores, respaldan directamente el beneficio pedagógico de la evaluación oportuna para guiar el aprendizaje. Si bien las tres herramientas ofrecen enfoques gamificados, tienen enfoques y características ligeramente diferentes:
    
    .bg-full-width.bg-color-7
      .p-4.p-md-5
        div.row.justify-content-center.align-items-stretch.mb-5
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema4/7.svg" alt="" style="width: 90px")
              p.mb-0.text-center Kahoot se utiliza frecuentemente, para cuestionarios rápidos y competitivos.
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema4/8.svg" alt="" style="width: 90px")
              p.mb-0.text-center Quizizz ofrece más opciones y personalización a ritmo del estudiante.
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema4/9.svg" alt="" style="width: 90px")
              p.mb-0.text-center Mentimeter es versátil para presentaciones interactivas y encuestas rápidas.
        
        p Esta variedad permite a los educadores elegir la herramienta que mejor se adapte a sus objetivos de aprendizaje específicos y a las preferencias de sus estudiantes. Al comparar los matices de cada herramienta, se revela que atienden a necesidades pedagógicas y estilos de aprendizaje ligeramente diferentes dentro de la categoría más amplia de gamificación y evaluación.

    .titulo-figura.mb-4
      h5 Tabla 6.
      span Comparativa de herramientas para la gamificación y evaluación
    .tabla-a.color-acento-botones.mb-5
      table
        thead
          tr
            th.bg-color-4.text-center.text-white Característica
            th.bg-color-4.text-center.text-white Kahoot
            th.bg-color-4.text-center.text-white Quizizz
            th.bg-color-4.text-center.text-white Mentimeter
        tbody.bg-color-white
          tr
            th Uso principal.
            td Cuestionarios en vivo, encuestas, sondeos.
            td Cuestionarios a ritmo del estudiante, lecciones interactivas.
            td Presentaciones interactivas, encuestas, cuestionarios.
          tr
            th Tipos de preguntas.
            td Opción múltiple, verdadero/falso, puzzle, encuesta, nube de palabras, lluvia de ideas.
            td Opción múltiple, verdadero/falso, rellenar el espacio en blanco, encuesta, abierta.
            td Opción múltiple, nube de palabras, escala, abierta, ranking, matriz de seis, 2x2.
          tr
            th Elementos gamificación.
            td Puntos, tabla de líderes, música, temporizador.
            td Puntos, tabla de líderes, memes, temas, temporizador, avatares.
            td Puntos (opcional en quiz), temporizador (opcional en quiz).
          tr
            th Informes y analíticas.
            td Informes básicos.
            td Informes detallados por estudiante y pregunta.
            td Resumen de resultados en tiempo real.
          tr
            th Opciones integración.
            td Sí (varias plataformas).
            td Sí (Google Classroom, LMS).
            td Sí (incrustación en presentaciones).
          tr
            th Ritmo del estudiante.
            td No (principalmente en vivo).
            td Sí.
            td No (principalmente en vivo).
          tr
            th Personalización.
            td Limitada.
            td Amplia (temas, memes, música).
            td Moderada (temas, imágenes).
          tr
            th Precio.
            td Freemium (versión gratuita limitada).
            td Freemium (versión gratuita limitada).
            td Freemium (versión gratuita limitada).

    
      
    #t_4_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 4.1] Diseño de experiencias de aprendizaje inmersivas con realidad aumentada y virtual
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/10.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") El avance de las tecnologías inmersivas ha abierto nuevas posibilidades para transformar los entornos educativos, permitiendo experiencias de aprendizaje más significativas, interactivas y personalizadas. La Realidad Aumentada (RA) y la Realidad Virtual (RV) se destacan como herramientas claves para diseñar entornos donde los estudiantes no solo acceden a la información, sino que interactúan con ella de manera activa y sensorial. 
    
        .bg-color-2.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema4/11.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Estas tecnologías facilitan la visualización de conceptos abstractos, la simulación de escenarios complejos y la exploración de contextos inaccesibles en el aula tradicional.
        p Incorporar RA y RV en el diseño instruccional de los Recursos Educativos Digitales (RED), implica un cambio de paradigma hacia metodologías centradas en la experiencia, donde el estudiante asume un rol más activo y comprometido en su proceso formativo. Desde viajes virtuales por el cuerpo humano hasta recorridos históricos o simulaciones de laboratorios científicos, estas herramientas potencian la comprensión, la retención del conocimiento y el aprendizaje significativo.
    
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/9cqLwqWDCzs?si=F1b2M6SlLRnGqFf9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .bg-full-width.bg-color-6.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left")
                h2 Beneficios educativos de la RA y la RV
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Favorecen la comprensión de conceptos complejos y abstractos.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Aumentan la motivación y el compromiso del estudiante.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Permiten aprender mediante la práctica, incluso en contextos imposibles de replicar en la realidad.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Estimulan la memoria visual y la capacidad de análisis.
                h2 Desafíos y limitaciones
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Costo del <em>hardware</em> y <em>software</em>, especialmente en RV.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Requiere habilidades técnicas para el desarrollo de contenidos.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Accesibilidad: no todos los estudiantes cuentan con los dispositivos adecuados.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Curva de aprendizaje en el uso de herramientas y plataformas.
              .col-lg-4(data-aos="zoom-in").mb-3.mb-lg-0
                img.img-fluid(src='@/assets/curso/tema4/12.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    p.mb-5 A manera de repaso, sobre este tema, lo invitamos a consultar la siguiente tabla, en donde se exponen las ventajas, desventajas y aplicaciones de la RA y RV.

    .titulo-figura.mb-4
      h5 Tabla 7.
      span Comparativa de ventajas y desventajas de la Realidad Aumentada y Virtual en la educación
    .tabla-a.color-acento-botones.mb-5
      table
        thead
          tr
            th.bg-color-4.text-center.text-white Característica
            th.bg-color-4.text-center.text-white Realidad Aumentada (RA)
            th.bg-color-4.text-center.text-white Realidad Virtual (RV)
        tbody.bg-color-6
          tr
            td Ventajas.
            td Mejora la percepción del mundo real, costo relativamente menor, accesible a través de dispositivos comunes (smartphones, tabletas), mayor facilidad de integración en el aula.
            td Inmersión total, simulación de entornos complejos, experiencias que de otro modo serían imposibles o peligrosas, mayor potencial para el aprendizaje experiencial.
          tr
            td Desventajas.
            td Inmersión limitada, interacción con el mundo real puede ser una distracción, desarrollo de contenido puede ser complejo.
            td Costo del equipo (visores, controladores), puede causar mareos o desorientación en algunos usuarios, requiere un entorno controlado, desarrollo de contenido puede ser muy especializado.
          tr
            td Aplicaciones.
            td Visualización de modelos 3D, exhibiciones interactivas, juegos educativos en el mundo real, superposición de información contextual.
            td Viajes de campo virtuales, simulaciones de entrenamiento (medicina, ingeniería), exploración de entornos históricos o fantásticos, aprendizaje basado en escenarios.


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.redalyc.org/pdf/368/36815128007.pdf" target="_blank" rel="noopener noreferrer") Pérez, M. G., & Sánchez, I. O. (2010). Atención a la e-accesibilidad y usabilidad universal en el diseño formativo. Pixel-Bit. Revista de Medios y Educación, (36), 89-99. 

            

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/PRZfExDtVOU?si=ghNWTgW_TjaDNMMg" target="_blank" rel="noopener noreferrer") Giménez A. (2020, 25 de marzo) Video 1 - Orientaciones sobre recursos digitales accesibles [video] YouTube. 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
