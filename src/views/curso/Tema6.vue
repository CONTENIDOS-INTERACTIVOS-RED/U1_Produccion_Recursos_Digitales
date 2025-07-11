<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'6. Mejora y optimización de materiales digitales según retroalimentación y análisis de datos'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-2.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema6/1.png', alt='')
        .col-lg.order-1.mb-3.mb-lg-0
          .p-4
            p.mb-0(data-aos="fade-up") La creación de un Recurso Educativo Digital (RED) no culmina con su primera versión o implementación. De hecho, este es solo el comienzo de un ciclo vital en el que la mejora continua y la optimización son fundamentales para asegurar su relevancia, efectividad y alineación con las necesidades cambiantes de los estudiantes y los contextos educativos. Este tema le guiará a través de los procesos para transformar la retroalimentación y los datos de uso en acciones concretas de mejora.

    #t_6_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.1] El Ciclo de Mejora Continua (PDCA/Deming) Aplicado a RED
    
    p.mb-5 El concepto de mejora continua, popularizado por W. Edwards Deming (Soberanis Pacheco, 2021), se materializa en el Ciclo PDCA (Plan-Do-Check-Act), también conocido como ciclo de Deming o ciclo de Shewhart. Este modelo iterativo de cuatro fases, es perfectamente aplicable a la optimización de RED:

    .bg-full-width.bg-fondo-3
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-10
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema6/2.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="2.8%" y="43.3%" numero="+")
                h5 Actuar (Act)
                p Con base en los resultados de la fase de verificación, se toman decisiones:
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si los cambios fueron exitosos y se alcanzaron los objetivos, se estandarizan las mejoras, se documentan y se implementan de forma generalizada en el RED.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si los cambios no produjeron los resultados esperados o surgieron nuevos problemas, se analizan las causas, se ajusta el plan y se inicia un nuevo ciclo PDCA.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si se identifican nuevas oportunidades de mejora, también se incorporan al siguiente ciclo de planificación.
    
              .bg-color-white.box-shadow.p-3(x="17.3%" y="8.5%" numero="+")
                h5 Planificar (Plan)
                p En esta fase, se identifican las áreas de mejora del RED basándose en la evaluación de su impacto, la retroalimentación de los usuarios (estudiantes, docentes), el análisis de datos de uso, o los cambios en los objetivos de aprendizaje o el currículo. Se establecen objetivos claros para la mejora, se definen las modificaciones específicas que se realizarán en el RED y se planifica cómo se implementarán y evaluarán estos cambios.
    
              .bg-color-white.box-shadow.p-3(x="97.2%" y="31%" numero="+")
                h5 Verificar (<em>Check</em>)
                p Una vez implementados los cambios, se evalúa su efectividad. Se recolectan datos para determinar si las modificaciones han logrado los objetivos planteados en la fase de planificación. ¿Mejoró la comprensión del estudiante? ¿Aumentó el engagement? ¿Se resolvieron los problemas de usabilidad identificados? Se comparan los resultados con los datos previos a la modificación.
    
              .bg-color-white.box-shadow.p-3(x="65.8%" y="55%" numero="+")
                h5 Hacer (<em>Do</em>)
                p Se implementan los cambios planificados en el RED. Esto puede implicar modificar contenidos, rediseñar actividades interactivas, mejorar la interfaz de usuario, añadir nuevos elementos, corregir errores, etc. Es recomendable realizar estos cambios en un entorno de prueba o con un grupo piloto si las modificaciones son sustanciales.
    
    .bg-full-width.bg-color-10.mb-5
      .px-4.px-md-5.py-4
        p.mb-0.text-white La aplicación sistemática de este ciclo fomenta una cultura de revisión y adaptación constante, donde el RED es visto como un producto dinámico que evoluciona y mejora con el tiempo, en lugar de una obra estática y definitiva. Este enfoque es vital en el ámbito de la tecnología educativa, donde las herramientas, las pedagogías y las necesidades de los usuarios están en permanente transformación.
    
    #t_6_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.2] Recolección sistemática de retroalimentación (<em>feedback</em>)
    
    .row.mb-5
      .col-lg-3.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema6/3.svg", data-aos="zoom-in")
      .col-lg-9.order-lg-1
        p(data-aos="fade-left") La retroalimentación de los usuarios es una de las fuentes de información más valiosas para la mejora de los RED. Para que sea útil, su recolección debe ser sistemática y planificada.
        p Fuentes de retroalimentación:
    
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema6/4.png")
            .col-lg-7
              h5 Estudiantes
              p Son los usuarios directos del RED y pueden ofrecer perspectivas cruciales sobre su claridad, utilidad, nivel de dificultad, atractivo y los problemas que encontraron. Su <em>feedback</em> puede recogerse a través de encuestas de satisfacción, comentarios en foros de discusión del EVA, entrevistas individuales o grupales, pruebas de usabilidad específicas, o incluso a través de canales informales si se crea un ambiente de confianza.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema6/5.png")
            .col-lg-7
              h5 Docentes / Pares
              p Otros educadores que utilizan o han revisado el RED pueden aportar una visión pedagógica experta, identificar posibles desajustes con el currículo, sugerir mejoras en las actividades o en la forma de integrar el RED. Esto puede lograrse mediante revisiones colaborativas, observaciones de clase (si el RED se usa en contextos híbridos), o en el marco de comunidades de práctica docente.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema6/6.png")
            .col-lg-7
              h5 Expertos en contenido y diseño
              p Especialistas en la materia del RED pueden validar la precisión y actualidad del contenido, mientras que expertos en diseño instruccional o diseño de interfaces pueden ofrecer recomendaciones sobre la estructura pedagógica, la usabilidad y la accesibilidad del recurso.
    
    p.mb-5 Métodos para recolectar <em>feedback</em> efectivo:
    
    .bg-full-width.bg-color-5
      .p-4.p-md-5
        TabsC.color-primario.mb-5
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Diseño de instrumentos" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0
                h4 Diseño de instrumentos
                p Utilizar una combinación de preguntas cerradas (para obtener datos cuantitativos sobre aspectos específicos) y preguntas abiertas (para recoger opiniones, sugerencias y explicaciones detalladas). Las preguntas deben ser claras, concisas y enfocadas en los aspectos que se desean mejorar.
        
              .col-md-8.col-lg-5.col-xl-4.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema6/7.png', alt='')
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Creación de un ambiente de confianza" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0
                h4 Creación de un ambiente de confianza
                p Es fundamental que los usuarios se sientan cómodos para expresar críticas constructivas sin temor a represalias. El anonimato en las encuestas puede ayudar, así como una comunicación clara sobre el propósito de la recolección de <em>feedback</em> (la mejora del recurso para beneficio de todos).
        
              .col-md-8.col-lg-5.col-xl-4.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema6/8.png', alt='')
        
        p.mb-5 Momentos claves para solicitar feedback:

        div.row.justify-content-center.align-items-stretch.mb-3
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/9.svg" alt="" style="width: 90px")
              h5.text-center Durante el pilotaje
              p.mb-0.text-center Antes de un lanzamiento a gran escala, probar el RED con un grupo reducido de usuarios y recoger sus impresiones es crucial para identificar problemas mayores.
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/10.svg" alt="" style="width: 90px")
              h5.text-center Durante el uso regular
              p.mb-0.text-center Integrar mecanismos para que los estudiantes puedan reportar problemas o hacer sugerencias mientras usan el RED (ejemplo, un botón de “feedback”). 
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/11.svg" alt="" style="width: 90px")
              h5.text-center Después de un uso extensivo o al finalizar una unidad/curso
              p.mb-0.text-center Solicitar una valoración más global de la experiencia con el RED.
    
    #t_6_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.3] Análisis de la retroalimentación y los datos de uso

    p.mb-5 El análisis de datos es una etapa fundamental para comprender la eficacia y la experiencia del uso de los Recursos Educativos Digitales (RED).

    .bg-full-width.bg-color-9.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Análisis de la retroalimentación y los datos de uso
            p.mb-4(data-aos="fade-right") En el PDF <b>Análisis de la retroalimentación y los datos de uso</b>, se explican métodos cualitativos y cuantitativos para interpretar comentarios de los usuarios y patrones de navegación en plataformas virtuales, con el fin de identificar oportunidades de mejora. Esta información, cuando se triangula adecuadamente, permite tomar decisiones informadas para optimizar tanto el diseño instruccional como la funcionalidad de los RED.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_4.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Análisis de la retroalimentación y los datos de uso.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema6/12.png', alt='')

    #t_6_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.4] Principios de diseño iterativo para la optimización de RED
    
    .bg-full-width.bg-color-7.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-6.order-lg-2.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema6/13.svg", data-aos="zoom-in")
          .col-lg-6.order-lg-1
            p(data-aos="fade-left").mb-4 Para conocer sobre la temática, lo invitamos a escuchar el siguiente podcast.
    
            TarjetaAudio.color-acento-botones.bg-color-white.mb-3(
              texto="Fundamentos de la innovación estratégica"
              tiempo
              :audio="require('../../assets/curso/podcast/podcast1.mp3')"
            )

    #t_6_5.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.5] Casos prácticos de optimización de RED
    
    p.mb-5 Para ilustrar cómo se aplican estos principios, consideremos algunos ejemplos:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema6/14.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        AcordionA(tipo="b")
          .div(titulo="Caso 1. Mejorar la navegabilidad")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Los estudiantes comentan que “es difícil encontrar la información” y las analíticas muestran que muchos abandonan el RED desde la página de inicio o navegan erráticamente. Los mapas de calor indican que no hacen clic en los enlaces del menú principal.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Rediseñar el menú de navegación para que sea más visible e intuitivo, usar etiquetas más claras, añadir un mapa del sitio o un índice interactivo. Probar el nuevo diseño con un grupo de usuarios antes de implementarlo para todos.

          .div(titulo="Caso 2. Ajustar el nivel de dificultad de actividades interactivas")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Muchos estudiantes se quejan de que un quiz es “demasiado difícil” y las tasas de respuestas correctas son muy bajas. Otros, en cambio, lo encuentran “muy fácil”.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Revisar las preguntas del quiz. Si es posible, ofrecer diferentes niveles de dificultad o pistas opcionales. Añadir retroalimentación más detallada para las respuestas incorrectas que explique el error. Considerar si el contenido previo preparó adecuadamente a los estudiantes para el quiz.
          .div(titulo="Caso 3. Añadir recursos de apoyo donde se detectan dificultades")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Las analíticas muestran que los estudiantes pasan mucho tiempo en una sección que explica un concepto complejo y, aún así, sus resultados en las actividades relacionadas son bajos. Los comentarios indican “necesito más ejemplos”.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Añadir un vídeo explicativo corto, un glosario de términos clave para esa sección, ejemplos resueltos adicionales, o un foro específico donde puedan plantear dudas sobre ese concepto.
          .div(titulo="Caso 4. Mejorar la claridad de las instrucciones")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Feedback/Dato</b>. Varios estudiantes preguntan “¿qué se supone que tengo que hacer aquí?” en una actividad que requiere el uso de una herramienta externa integrada en el RED.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Optimización</b>. Reescribir las instrucciones de la actividad para que sean más explícitas, paso a paso. Incluir capturas de pantalla o un breve videotutorial mostrando cómo usar la herramienta externa en el contexto de la tarea.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/15.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") Una vez realizadas las mejoras, es importante comunicar los cambios a los usuarios, especialmente si son significativos. Esto no solo les ayuda a aprovechar las nuevas funcionalidades o el contenido mejorado, sino que también demuestra que su feedback es valorado y tomado en cuenta, lo que puede fomentar una mayor disposición a participar en futuros procesos de retroalimentación.
        p.mb-5 Es importante reconocer que la resistencia al cambio (tanto por parte de los diseñadores que pueden sentirse apegados a su creación original, como de los usuarios que ya se habían acostumbrado a una versión anterior) puede ser una barrera para la mejora continua. 
        .bg-color-3.p-4(data-aos="fade-left")
          p.mb-0 Una cultura organizacional e institucional que valore la experimentación, que vea el “error” o el feedback crítico como una oportunidad de aprendizaje, y que asigne tiempo y recursos para los procesos de revisión y optimización, es crucial para superar estas barreras. La mejora continua de RED no es solo una responsabilidad individual del diseñador; se ve facilitada (o dificultada) por el contexto institucional y las políticas de apoyo a la innovación educativa. Esto tiene implicaciones para el liderazgo educativo y la gestión del cambio en las organizaciones que buscan fomentar la calidad en la educación digital.
        
    #t_6_6.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.6] Plataformas de aprendizaje y repositorios de RED
    
    p.mb-5 Existen diversos tipos de plataformas y sistemas donde puede alojar y distribuir sus RED, cada uno con sus propias características, ventajas y limitaciones:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/16.png", alt="").mb-4.mb-lg-0
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="Sistemas de Gestión de Aprendizaje (LMS - Learning Management Systems)")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. Moodle, Canvas, Blackboard, Google Classroom, Chamilo, Sakai.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Funcionalidades</b>. Son plataformas robustas diseñadas para administrar, distribuir y controlar actividades de formación online. Permiten organizar contenidos en cursos, gestionar usuarios (estudiantes y docentes), realizar seguimiento del progreso, facilitar la comunicación (foros, mensajería) e integrar herramientas de evaluación.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ventajas para RED</b>. Ofrecen un entorno estructurado y controlado para la distribución de RED a una audiencia específica (ejemplo, estudiantes de un curso). Permiten integrar los RED directamente en secuencias de aprendizaje y realizar seguimiento de su uso.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Limitaciones</b>. Suelen ser entornos cerrados, lo que puede limitar la visibilidad y el acceso a los RED fuera de la comunidad de usuarios registrados. La personalización de la apariencia puede ser limitada.

          .div(titulo="Repositorios educativos")
            p Son bibliotecas digitales diseñadas específicamente para almacenar, preservar y compartir Recursos Educativos Digitales y, por lo general, Recursos Educativos Abiertos (REA).
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Institucionales</b>. Gestionados por universidades u otras organizaciones educativas para sus propios miembros y, a menudo, para el público general (ejemplo, repositorios basados en Dspace o Eprints).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Temáticos o agregadores</b>. Se centran en áreas de conocimiento específicas o agregan RED de múltiples fuentes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. MERLOT (Multimedia Educational Resource for Learning and Online Teaching), OER Commons, Procomún (España), La Referencia (América Latina), Temoa (Tecnológico de Monterrey).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Propósito</b>. Facilitar el descubrimiento, acceso y reutilización de RED de calidad. Suelen contar con sistemas de metadatos para describir los recursos y facilitar su búsqueda.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Cómo buscar y contribuir</b>. Generalmente ofrecen interfaces de búsqueda avanzada. Para contribuir, suelen requerir el registro y la cumplimentación de formularios de metadatos que describen el recurso.
          .div(titulo="Plataformas de contenido específico y MOOCs")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Ejemplos</b>. YouTube (especialmente YouTube Edu), Vimeo (para videos); Khan Academy (microlecciones y ejercicios); Coursera, edX, MiríadaX (plataformas de Cursos Online Masivos y Abiertos - MOOCs, que distribuyen una gran cantidad de RED como parte de sus cursos).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Características</b>. Estas plataformas pueden tener un alcance masivo y estar especializadas en ciertos tipos de contenido (ejemplo, vídeo) o formatos de aprendizaje (ejemplo, cursos cortos). Algunas operan bajo modelos de negocio que pueden influir en cómo se accede o se reutiliza el contenido.
    
    p.mb-5 Criterios para seleccionar la plataforma o repositorio más adecuado:

    .bg-full-width.bg-color-8
      .p-4.p-md-5
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/18.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Tipo de RED
                    p.text-center ¿Es un video, un objeto SCORM, un PDF interactivo, una simulación? Algunas plataformas son más adecuadas para ciertos formatos.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/19.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Audiencia objetivo
                    p.text-center ¿Es para sus propios estudiantes en un curso cerrado (LMS)? ¿O busca un alcance global (repositorio OER, YouTube)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/20.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Objetivos de difusión
                    p.text-center ¿Quiere facilitar la reutilización y adaptación por otros (REA en repositorio)? ¿O principalmente controlar el acceso (LMS)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/21.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Licenciamiento
                    p.text-center ¿La plataforma permite o requiere ciertos tipos de licencias (ejemplo, Creative Commons)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/22.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Funcionalidades de seguimiento
                    p.text-center ¿Necesita rastrear el uso y el progreso de los estudiantes con el RED (LMS con SCORM/xAPI)?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/23.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Facilidad de uso y mantenimiento
                    p.text-center ¿Qué tan fácil es subir y gestionar los RED en la plataforma?
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/24.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Costos asociados
                    p.text-center Algunas plataformas pueden tener costos de suscripción o alojamiento.
        
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema6/17.png', alt='')
          
    #t_6_7.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.7] Estándares técnicos para la interoperabilidad y seguimiento
    
    p.mb-5 La estandarización técnica es esencial para asegurar que los Recursos Educativos Digitales (RED) puedan ser utilizados, compartidos y evaluados de manera eficaz en distintos entornos virtuales.

    .bg-full-width.bg-color-9.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Estándares técnicos para la interoperabilidad y seguimiento
            p.mb-4(data-aos="fade-right") En el PDF <b>Estándares técnicos para la interoperabilidad y seguimiento</b>, se abordan los principales marcos como SCORM, xAPI y LTI, así como la importancia de los metadatos en la gestión de contenidos digitales. Estos elementos garantizan no solo la compatibilidad entre plataformas, sino también un seguimiento más preciso del aprendizaje y una mejor organización de los recursos disponibles.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_5.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Estándares técnicos para la interoperabilidad y seguimiento.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema6/25.png', alt='')

    #t_6_8.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.8] Licenciamiento de RED: derechos de autor y contenido abierto
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/26.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") Cuando usted crea un RED, automáticamente posee los derechos de autor sobre esa obra (salvo que sea un trabajo por encargo con otras condiciones). Es fundamental que usted decida cómo quiere que otros puedan usar su creación (Chiarani, 2016).
    
        .bg-color-2.p-4(data-aos="fade-left")
          p.mb-0 Conceptos básicos de derechos de autor (Copyright). Otorgan al creador derechos exclusivos sobre la reproducción, distribución, adaptación y comunicación pública de su obra. Por defecto, todas las obras están protegidas por “todos los derechos reservados”, lo que significa que nadie puede usarlas sin permiso explícito del titular.
    
    h2(data-aos="fade-left") Licencias Creative Commons (CC). 
    p.mb-5 Son un conjunto de licencias de derechos de autor estandarizadas y gratuitas que permiten a los creadores compartir sus obras de manera flexible, especificando qué permisos otorgan a otros y bajo qué condiciones. Se basan en cuatro condiciones principales que se pueden combinar:

    div.bg-color-6.p-4.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-6
          figure
            img(src="@/assets/curso/tema6/27.png", data-aos="zoom-in")
      
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema6/28.png", alt="").mb-4.mb-lg-0
      .col-lg-8
        AcordionA(tipo="b")
          .div(titulo="BY (Atribución).")
            p Siempre se debe reconocer la autoría original de la obra. Esta condición está presente en todas las licencias CC.
          .div(titulo="SA (Compartir Igual – Share Alike).")
            p Si se crea una obra derivada (una adaptación o modificación del original), esta debe licenciarse bajo la misma licencia CC (o una compatible) que la obra original.
          .div(titulo="NC (No Comercial – Non-Commercial).")
            p La obra no puede ser utilizada con fines primordialmente comerciales.
          .div(titulo="ND (Sin Obras Derivadas – No Derivatives)")
            p No se permite modificar, transformar o crear obras derivadas a partir del original. Solo se puede copiar y distribuir la obra tal cual.

    p.mb-5 Combinaciones comunes de licencias CC:

    .bg-full-width.bg-color-8
      .p-4.p-md-5
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/30.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY
                    p.text-center La más abierta. Permite cualquier uso (incluso comercial y modificación) siempre que se dé atribución.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/31.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-SA
                    p.text-center Permite cualquier uso, pero las obras derivadas deben compartirse bajo la misma licencia.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/32.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-NC
                    p.text-center Permite uso no comercial, con atribución.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/33.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-NC-SA
                    p.text-center Permite uso no comercial, las obras derivadas deben ser no comerciales y compartirse bajo la misma licencia.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/34.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-ND
                    p.text-center Permite copiar y distribuir (incluso comercialmente), pero no modificar, con atribución.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema6/35.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 CC BY-NC-ND
                    p.text-center La más restrictiva de las CC. Permite copiar y distribuir solo para fines no comerciales y sin modificaciones, con atribución.
        
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema6/29.png', alt='')
    
    h2(data-aos="fade-left") ¿Cómo elegir la licencia CC adecuada?
    p.mb-5 Depende de sus objetivos. Si quiere la máxima difusión y reutilización, CC BY es ideal. Si le preocupa el uso comercial o quiere que las adaptaciones también sean abiertas, puede añadir NC o SA.

    .bg-full-width.bg-color-6.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").order-lg-2
                p Implicaciones de usar RED con licencias CC:
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Si utiliza un RED creado por otro bajo una licencia CC, debe respetar las condiciones de esa licencia (ejemplo, siempre atribuir, no usar comercialmente si es NC, etc.). 
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 La elección de una licencia para una RED no es una mera formalidad legal; es una declaración sobre su filosofía educativa y su compromiso con el conocimiento compartido y la equidad. Optar por una licencia CC abierta (como CC BY o CC BY-SA) facilita que otros educadores y estudiantes puedan acceder, adaptar, traducir, contextualizar y mejorar su RED. Esto se alinea con los principios del movimiento de Recursos Educativos Abiertos (REA/OER), que promueve el acceso libre y gratuito a materiales de enseñanza, aprendizaje e investigación. 
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Un RED abierto puede tener un impacto mucho mayor y más duradero que uno cerrado, al ser potenciado por una comunidad global. Fomentar el uso de licencias abiertas en la producción de RED puede ser una estrategia institucional clave para promover la innovación, la colaboración y el acceso equitativo al conocimiento. Como futuro diseñador curricular, es vital que usted esté formado para tomar estas decisiones de licenciamiento de manera informada y consciente de sus implicaciones.  <a href="https://unesdoc.unesco.org/ark:/48223/pf0000246687_spa" target="_blank"> (Ver la Declaración de París sobre los REA de la UNESCO, 2012).</a>


                
              .col-lg-4(data-aos="zoom-in").mb-3.mb-lg-0.order-lg-1
                img.img-fluid(src='@/assets/curso/tema6/36.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    #t_6_9.titulo-segundo(data-aos="flip-up")
      h2 #[span 6.9] Principios de accesibilidad web aplicados a RED
    
    p.mb-5 La accesibilidad y la difusión son aspectos fundamentales en la creación y uso de los Recursos Educativos Digitales (RED), ya que garantizan que todos los estudiantes puedan beneficiarse de ellos sin barreras y que su alcance sea amplio y significativo.

    .bg-full-width.bg-color-9.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Principios de accesibilidad web aplicados a RED
            p.mb-4(data-aos="fade-right") En el PDF <b>Principios de accesibilidad web aplicados a RED</b>, se abordan las pautas internacionales de accesibilidad (WCAG), las herramientas de verificación y su relación con el Diseño Universal para el Aprendizaje, así como estrategias clave para promover y diseminar estos recursos. Esta información permite comprender cómo diseñar RED más inclusivos, visibles y con verdadero impacto pedagógico.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_6.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Principios de accesibilidad web aplicados a RED.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema6/37.png', alt='')

    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.scielo.org.ar/scielo.php?pid=S1850-00132014000100005&script=sci_arttext" target="_blank" rel="noopener noreferrer") Aguilar Juárez, I., Ayala De la Vega, J., Lugo Espinosa, O., & Zarco Hidalgo, A. (2014). Análisis de criterios de evaluación para la calidad de los materiales didácticos digitales. Revista iberoamericana de ciencia tecnología y sociedad, 9(25), 73-89.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://dehesa.unex.es/handle/10662/7052" target="_blank" rel="noopener noreferrer") Sanabria Mesa, A. L., Álvarez Núñez, Q., & Peirats Chacón, J. (2017). Las políticas educativas en la producción y distribución de materiales didácticos digitales. 



            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=fplS9vfMzDs&ab_channel=KeisenConsultores  " target="_blank" rel="noopener noreferrer") Keisen Consultores. (2020, 18 de septiembre). 034 - Tip PDCA 2: Diferencia Ciclo PDCA vs Ciclo de Deming. [Video] YouTube 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=ZxZ4RFUPu7E&ab_channel=OpenEducationWeek%28OEWeek%29" target="_blank" rel="noopener noreferrer") Open Education Week (OEWeek). (2013, 12 de marzo). Pilar Saenz - Licencias Creative Commons para recursos educativos, ¿que son? ¿como usarlas?. [Video] YouTube    

       



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema6',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál de las siguientes opciones define mejor un Recurso Educativo Digital (RED)?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Un material didáctico impreso y digitalizado para su uso en línea.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Cualquier tipo de información que se encuentra en formato digital.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Todo material en formato digital diseñado con una intención y finalidad educativa.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Un software específico para la gestión de aulas virtuales. ',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Qué característica distingue principalmente a un RED interactivo?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'La inclusión de múltiples formatos de medios como video y audio.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'La capacidad de ser utilizado en diversos dispositivos electrónicos.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'La exigencia de la participación activa del estudiante a través de actividades o retroalimentación. ',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Su disponibilidad gratuita y sin restricciones de uso. ',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Cuál de las siguientes herramientas se utiliza principalmente para crear contenido interactivo en Recursos Educativos Digitales?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Un editor de texto plano.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Una plataforma de videoconferencias.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Una herramienta de autoría multimedia como H5P o Genially. ',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Un sistema operativo para computadoras.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué aspecto es fundamental para asegurar la accesibilidad de un Recurso Educativo Digital (RED)?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Utilizar animaciones complejas para ilustrar conceptos.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Garantizar que el contenido pueda ser percibido, operado y comprendido por todos los usuarios, incluyendo aquellos con discapacidades. ',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto:
                  'Incorporar la mayor cantidad de colores llamativos en el diseño.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Limitar el uso de texto para favorecer elementos visuales.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Cuál es el método más directo para evaluar la efectividad pedagógica de un Recurso Educativo Digital (RED)?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Contar el número de descargas del recurso.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Solicitar la opinión del creador del recurso.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Analizar el impacto del recurso en el logro de los objetivos de aprendizaje de los estudiantes. ',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Medir el tiempo que los estudiantes pasan utilizando el recurso. ',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
