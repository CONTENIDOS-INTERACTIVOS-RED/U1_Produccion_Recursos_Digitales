<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Plataformas de diseño de contenidos digitales'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-3.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema3/1.svg", data-aos="zoom-in")
      .col-lg-9.order-lg-1
        p(data-aos="fade-left") En el contexto de la educación virtual, el diseño de contenidos digitales es una competencia clave para docentes, diseñadores instruccionales y creadores de recursos educativos. Las plataformas de autoría permiten crear materiales más atractivos, interactivos y eficaces, para el aprendizaje autónomo (Martínez, 2015). A continuación, se verán cuatro herramientas ampliamente utilizadas en entornos educativos: H5P, Genially, Articulate y Canva. Cada una responde a diferentes necesidades pedagógicas, técnicas y visuales, como se presenta a continuación:
    
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/2.svg")
            .col-lg-7
              h5 H5P
              p H5P (HTML5 Package) es una plataforma de código abierto, que permite crear objetos de aprendizaje dinámicos, directamente desde el navegador. Entre sus tipos de contenido se encuentran: vídeos interactivos, cuestionarios, líneas de tiempo, presentaciones interactivas y juegos educativos. Uno de sus grandes beneficios es su integración con sistemas de gestión del aprendizaje (LMS) como Moodle, Canvas o WordPress, lo cual facilita la evaluación y seguimiento del estudiante.
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ventajas</b>. Gratuito, personalizable, con fuerte enfoque en la interactividad pedagógica. Alineado con metodologías activas.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Desventajas</b>. Requiere conocimientos básicos para su implementación técnica en un LMS y su apariencia puede ser más básica, en comparación con otras herramientas.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/3.png")
            .col-lg-7
              h5 Genially
              p Genially es una plataforma web que permite crear recursos visuales interactivos, como presentaciones, infografías, líneas de tiempo, mapas, juegos y experiencias de gamificación. No requiere conocimientos de programación y se destaca por sus plantillas visuales y opciones de animación.
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ventajas</b>. Interfaz amigable, variedad de plantillas, permite trabajar en equipo y facilita la incorporación de elementos interactivos con pocos clics. 
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Desventajas</b>. Algunas funciones están restringidas a cuentas de pago y su interactividad es más visual que funcional (por ejemplo, no permite capturar respuestas del estudiante fácilmente).
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/4.png")
            .col-lg-7
              h5 Articulate (Storyline 360 y Rise 360)
              p Articulate es un conjunto de herramientas profesionales para el diseño instruccional. Storyline 360 permite crear cursos e-learning altamente personalizados, con navegación no lineal, evaluaciones complejas y escenarios ramificados. Rise 360, por su parte, es una herramienta en línea para el desarrollo de cursos responsivos con diseño moderno y adaptativo.
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ventajas</b>. Potente en términos de interactividad y evaluación, ideal para formación corporativa o institucional con altos estándares de calidad.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Desventajas</b>. Requiere licencia, es más complejo de manejar y demanda tiempo para dominar sus funciones.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/5.png")
            .col-lg-7
              h5 Canva
              p Canva es una herramienta de diseño gráfico basada en la web, que facilita la creación de materiales visuales, como: presentaciones, carteles, infografías, publicaciones para redes sociales y documentos. Aunque no fue concebida como una plataforma educativa, se ha convertido en una opción popular para docentes que desean producir materiales atractivos sin necesidad de conocimientos de diseño.
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ventajas</b>. Interfaz muy intuitiva, biblioteca de plantillas y recursos visuales, opciones de trabajo colaborativo.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Desventajas</b>. Limitada en funciones interactivas y sin opciones avanzadas de seguimiento del aprendizaje.
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/6.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-2.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/7.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Estas plataformas presentan un equilibrio entre la facilidad de uso y la profundidad de la funcionalidad. Canva es increíblemente intuitivo, pero carece de interactividad avanzada, mientras que Articulate ofrece funciones potentes, pero requiere más capacitación. Los educadores deben considerar sus habilidades técnicas y la complejidad del contenido deseado, al elegir una plataforma. 
        p(data-aos="fade-left") Al comparar las descripciones, se revela un espectro donde la facilidad de uso, frecuentemente tiene un costo en términos de funciones avanzadas, y viceversa. Esto destaca un factor clave en la toma de decisiones para los educadores. H5P y Genially están explícitamente enfocados en la creación de contenido interactivo, lo que se alinea con la investigación que destaca la participación como un elemento crucial del aprendizaje digital efectivo. Esto refuerza el valor pedagógico de incorporar elementos interactivos en los recursos educativos. 
        p El énfasis en la "interactividad" en las descripciones de H5P y Genially, se conecta directamente con la investigación más amplia sobre los beneficios de la participación en el aprendizaje. Esto sugiere una fuerte alineación entre las características de estas herramientas y los principios pedagógicos establecidos. 
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/8.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-3.p-4.mb-5(data-aos="fade-left")
          p.mb-0 La perfecta integración de H5P con las plataformas LMS (mencionada en su descripción) es significativa, dado que los LMS normalmente son fundamentales para la entrega y gestión del aprendizaje en línea. Esto resalta la importancia de considerar la infraestructura tecnológica existente al seleccionar herramientas para la producción de recursos digitales. La mención explícita de la integración con LMS para H5P, señala una consideración práctica para los educadores que probablemente ya estén utilizando un LMS. Esta función agiliza la implementación y gestión del contenido de H5P.
        p(data-aos="fade-left") Observe en la siguiente tabla, las diferentes características como: facilidad de uso, enfoque, tipos de contenido, opciones interactivas, evaluación, integración LMS y precio. Además, las ventajas y desventajas.
    
    .titulo-figura.mb-4
      h5 Tabla 4.
      span Comparativa de plataformas de diseño de contenidos digitales
    .tabla-a.color-acento-botones.mb-5
      table
        thead
          tr
            th.bg-color-4.text-center.text-white Característica
            th.bg-color-4.text-center.text-white H5P
            th.bg-color-4.text-center.text-white Genially
            th.bg-color-4.text-center.text-white Articulate (Storyline 360 & Rise 360)
            th.bg-color-4.text-center.text-white Canva
        tbody.bg-color-6
          tr
            th Facilidad de uso.
            td Moderada.
            td Fácil.
            td Moderada a difícil.
            td Muy fácil.
          tr
            th Enfoque.
            td Interactividad.
            td Diseño visual e interactividad.
            td Aprendizaje electrónico avanzado.
            td Diseño gráfico y presentaciones simples.
          tr
            th Tipos de contenido.
            td Quizzes, videos interactivos, presentaciones, juegos, etc.
            td Presentaciones, infografías, juegos, videos, etc.
            td Cursos interactivos, escenarios ramificados, evaluaciones.
            td Presentaciones, infografías, gráficos para redes sociales.
          tr
            th Opciones interactivas.
            td Amplias (drag and drop, rellenar huecos, etc.).
            td Variadas (ventanas, tooltips, botones interactivos, etc.).
            td Extensas (activadores, capas, variables, etc.).
            td Limitadas (enlaces, animaciones básicas).
          tr
            th Evaluación.
            td Sí (variedad de tipos de preguntas).
            td Limitada (principalmente a través de elementos interactivos).
            td Sólida (múltiples tipos de preguntas, seguimiento detallado).
            td No.
          tr
            th Integración LMS.
            td Sí (LTI).
            td Sí (incrustación).
            td Sí (Scorm, Aicc, Xapi).
            td Sí (incrustación).
          tr
            th Precio.
            td Gratuito y de código abierto.
            td Freemium (versión gratuita limitada).
            td Basado en suscripción (relativamente costoso).
            td Freemium (versión gratuita limitada).
          tr
            th Ventajas.
            td Gratuito, código abierto, fuerte en interactividad, integración LMS.
            td Interfaz intuitiva, plantillas atractivas, fácil de compartir.
            td Amplias opciones de interactividad, funciones profesionales, sólida evaluación.
            td Muy intuitivo, vasta biblioteca de plantillas, colaborativo, asequible.
          tr
            th Desventajas.
            td Interfaz menos pulida, requiere LMS/web para alojamiento.
            td Versión gratuita limitada, menos interacciones complejas.
            td Curva de aprendizaje, costoso, Storyline es de escritorio.
            td Menos enfocado en interactividad compleja, evaluación limitada.

    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema3/9.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Reflexione. La selección de una plataforma debe basarse en el equilibrio entre la complejidad del contenido, el grado de interactividad deseado y las competencias tecnológicas del docente. Mientras Canva facilita la creación rápida de recursos visuales, herramientas como H5P o Articulate, permiten desarrollar experiencias de aprendizaje más profundas e interactivas. La integración con LMS también es un factor clave para asegurar la trazabilidad del proceso formativo.

    #t_3_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.1] Creación de videos educativos y <em>screencasts</em>
    
    .row.mb-5
      .col-lg-3.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema3/10.svg", data-aos="zoom-in")
      .col-lg-9.order-lg-1
        p(data-aos="fade-left") La creación de contenido audiovisual, es una habilidad esencial para educadores y estudiantes de los entornos virtuales. Las herramientas como Camtasia, OBS Studio y Powtoon, permiten generar recursos dinámicos y atractivos que facilitan el aprendizaje. Conocer sus características permite seleccionar la herramienta más adecuada, según el objetivo educativo, la audiencia y los recursos disponibles. 
    
    .bg-full-width.bg-fondo-2.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema3/11.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="4%" y="27.5%" numero="+")
                h5 Camtasia
                p Permite producir contenidos educativos con aspecto profesional. 
                
    
              .bg-color-white.box-shadow.p-3(x="93%" y="20%" numero="+")
                h5 Powtoon
                p Permite crear vídeos animados y presentaciones visuales.
    
              .bg-color-white.box-shadow.p-3(x="96%" y="64%" numero="+")
                h5 OBS Studio
                p Permite la grabación de video y transmisión en vivo.
    
    p.mb-5 Analice cada una de las herramientas, en cuanto a su funcionalidad y uso: 

    TabsC.color-primario.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Camtasia" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Camtasia
            p Es un <em>software</em> comercial de grabación de pantalla y edición de video que permite producir contenidos educativos con aspecto profesional.
            h5 Uso y funcionalidades:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Grabación de pantalla y cámara web.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Edición avanzada (línea de tiempo, efectos visuales, anotaciones, transiciones).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Integración de cuestionarios interactivos.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Biblioteca de música y gráficos libres de derechos.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Exportación en múltiples formatos.

            p Enlace a la herramienta <a href="https://www.techsmith.es/camtasia/" target="_blank">Camtasia</a>
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/12.svg', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="OBS Studio (Open Broadcaster <em>software</em>)." :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 OBS Studio (Open Broadcaster <em>software</em>).
            p Es un <em>software</em> gratuito y de código abierto, para grabación de video y transmisión en vivo, ampliamente utilizado por creadores de contenido y educadores.
            h5 Uso y funcionalidades:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Captura y mezcla en tiempo real, de vídeo/audio desde múltiples fuentes.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Creación de escenas con transiciones personalizadas.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Grabación local y transmisión a plataformas como YouTube o Twitch.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Configuración avanzada sin coste.

            p Enlace a la herramienta <a href="https://obsproject.com/" target="_blank">Open Broadcaster <em>software</em></a>
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/13.svg', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Powtoon" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Powtoon
            p Es una herramienta basada en la web, para crear videos animados y presentaciones visuales.
            h5 Uso y funcionalidades:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Interfaz de arrastrar y soltar.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Biblioteca de plantillas, personajes y objetos animados.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Integración de narración y música.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Exportación a video o presentación interactiva.

            p Enlace a la herramienta <a href="https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjc0qio7oCNAxVynFoFHey4DVIYABAAGgJ2dQ&co=1&gclid=Cj0KCQjwlMfABhCWARIsADGXdy_hFcCRc0sLBg_ulDinTt4yTiskygkYZ6b2QA2tXHqoo3aTlSCmZl4aAkagEALw_wcB&ei=vasSaPzlENKPwbkPkaWqkQ8&ohost=www.google.com&cid=CAESVuD2NUQbf-FL9lpBEVsuIzeWWLh2H3ne8ryYn3Kxuohhx8PIdPPlxgSwoiCFpumN3w2bDHSlakW4HFqD5leI4Cx59_nyrIInCtGJxfoOaGB7wX3VjuCH&sig=AOD64_3F8w5UeR8lu-bM25T0adSo0GJC0w&q&sqi=2&adurl&ved=2ahUKEwi8uKOo7oCNAxXSRzABHZGSKvIQ0Qx6BAgKEAE" target="_blank">Powtoon</a>
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/14.png', alt='', style="width: 100%;")
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/15.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") Las anteriores herramientas satisfacen diferentes necesidades de creación de video. Powtoon es ideal para explicaciones animadas, Camtasia para grabaciones de pantalla y ediciones pulidas, y OBS Studio, para producciones más complejas con múltiples fuentes y transmisión en vivo. Comprender estos matices, permite a los educadores elegir la herramienta adecuada para sus objetivos específicos (López-Meneses).
    
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Al analizar el enfoque principal y las características de cada herramienta, se revela su idoneidad para diferentes tipos de contenido de video. Esto ayuda a los educadores a alinear su elección de herramienta con sus objetivos de producción de video. 
    
    .bg-full-width.bg-color-7
      .p-4.p-md-5
        div.row.justify-content-center.align-items-stretch.mb-5
          div.col-lg-6.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/16.svg" alt="" style="width: 90px")
              p.mb-0.text-center Destaca como una opción gratuita y de código abierto, lo que hace que la creación de video sea más accesible.
        
          div.col-lg-6.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/17.svg" alt="" style="width: 90px")
              p.mb-0.text-center Ofrece una experiencia más optimizada y fácil de usar con activos integrados y funciones de edición avanzadas, lo que podría ser preferible para aquellos que buscan un aspecto más profesional con menos configuración técnica.
        
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/18.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Al comparar los precios y las funciones, se destaca el equilibrio entre accesibilidad (costo y complejidad) y capacidades profesionales. Este es un factor crucial para los educadores con diferentes presupuestos y habilidades técnicas. 
    
        .bg-color-2.p-5(data-aos="fade-left")
          p.mb-0 En la creación de video se enfatiza la efectividad de la multimedia para mejorar el aprendizaje y la retención de conocimientos. Esto subraya la importancia del video como medio para entregar contenido educativo. La prominencia de las herramientas de creación de video apoya directamente los beneficios del aprendizaje visual y la participación multimedia. Esto refuerza el valor pedagógico de incorporar video en los recursos digitales.
        
    #t_3_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.2] Recomendaciones generales para la creación de videos

    p.mb-5 Recomendaciones generales para Camtasia:

    .bg-full-width.bg-color-8
      .p-4.p-md-5
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0.order-lg-2
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/20.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Planifique su guion antes de grabar
                    p.text-center Definir claramente la estructura del video (introducción, desarrollo, cierre).
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/21.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Utilice las herramientas de anotación
                    p.text-center Agregar flechas, resaltados y textos, para reforzar ideas claves.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/22.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Aproveche la edición por capas
                    p.text-center Usar la línea de tiempo para sincronizar narración, video y efectos visuales.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/23.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Cuide la calidad del audio
                    p.text-center Usar un micrófono externo si es posible y elimine ruidos de fondo, en la edición.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/24.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Mantenga la duración del video entre 3 y 7 minutos
                    p.text-center Para conservar la atención del estudiante.
        
              .col-lg-4.order-lg-1
                figure
                  img(src='@/assets/curso/tema3/19.png', alt='')

        p.mb-5 Recomendaciones generales para OBS Studio:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema3/25.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        AcordionA(tipo="b")
          .div(titulo="Prepare sus escenas y fuentes antes de grabar")
            p Configure todo lo que va a mostrar (pantalla, cámara, audio)
          .div(titulo="Haga pruebas de grabación, previas")
            p Verifique calidad de imagen, nivel de audio y fluidez.
          .div(titulo="Utilice atajos de teclado")
            p Para iniciar y detener la grabación sin mostrar el panel de control.
          .div(titulo="Configure la resolución adecuada")
            p Se recomienda grabar en 1080p a 30 fps para videos educativos.
          .div(titulo="Evite sobrecargar la escena")
            p Use solo los elementos necesarios para no distraer al espectador.
    
    p.mb-5 Recomendaciones generales para Powtoon:

    .bg-full-width.bg-color-8
      .p-4.p-md-5
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/27.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Elija plantillas acordes con el tono del mensaje
                    p.text-center Asegure que el estilo visual sea apropiado para el tema.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/28.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Simplifique el contenido
                    p.text-center Evite recargar con demasiados textos o animaciones; priorice lo visual.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/29.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Sincronice bien la narración y las animaciones
                    p.text-center Use la línea de tiempo para ajustar tiempos y transiciones.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/30.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Incluya música de fondo, con volumen moderado
                    p.text-center Ayuda a mantener el ritmo, sin distraer.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/tema3/31.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Añada voz en <em>off</em> si es posible
                    p.text-center Le da un toque más personal y facilita la comprensión.
        
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema3/26.png', alt='')

    .bg-full-width.bg-color-6.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").order-2
                p Consejos comunes para todas las herramientas:
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Mantenga una buena iluminación, si graba su rostro (en OBS o Camtasia).
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Revise la ortografía en títulos, etiquetas y textos en pantalla.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Sea claro y conciso en sus explicaciones.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Cuide el ritmo del video: ni demasiado rápido ni muy lento.
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 Exporte el video en un formato estándar como .mp4 para asegurar compatibilidad.
              .col-lg-4(data-aos="zoom-in").order-1.mb-3.mb-lg-0
                img.img-fluid(src='@/assets/curso/tema3/32.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    p.mb-5 Observe en la siguiente tabla las principales características de cada herramienta: 

    .titulo-figura.mb-4
      h5 Tabla 5.
      span Características de herramientas de creación de videos educativos y <em>screencasts</em>
    .tabla-a.color-acento-botones.mb-5
      table
        thead
          tr
            th.bg-color-4.text-center.text-white Característica
            th.bg-color-4.text-center.text-white Camtasia
            th.bg-color-4.text-center.text-white OBS Studio (Open Broadcaster <em>software</em>)
            th.bg-color-4.text-center.text-white Powtoon
        tbody.bg-color-6
          tr
            th Uso principal.
            td Screencasting y edición profesional.
            td Grabación y transmisión en vivo.
            td Videos explicativos animados.
          tr
            th Grabación.
            td Pantalla, webcam, múltiples fuentes.
            td Pantalla, webcam, múltiples fuentes.
            td Limitado a la animación y elementos de la plataforma.
          tr
            th Edición.
            td Amplia (línea de tiempo, transiciones, efectos, anotaciones).
            td Básica (escenas, fuentes, transiciones).
            td Intuitiva (arrastrar y soltar, línea de tiempo).
          tr
            th Animación.
            td Limitada (transiciones y algunos efectos).
            td No.
            td Amplia (personajes, objetos, plantillas).
          tr
            th Edición de audio.
            td Sí (básica).
            td Sí (mezclador de audio).
            td Sí (integración de música y voz en off).
          tr
            th Formatos de exportación.
            td mp4, avi, wmv, mov, gif, m4a, etc.
            td mp4, flv, mkv, mov, ts, m3u8.
            td mp4, ppt, pdf, compartir en redes sociales.
          tr
            th Curva de aprendizaje.
            td Moderada.
            td Moderada a empinada.
            td Fácil.
          tr
            th Precio.
            td Licencia de pago único.
            td Gratuito y de código abierto.
            td Freemium (versión gratuita limitada).


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.scielo.org.mx/scielo.php?pid=S1665-61802020000100022&script=sci_arttext" target="_blank" rel="noopener noreferrer") López Gil, K. S., & Chacón Peña, S. (2020). Escribir para convencer: experiencia de diseño instruccional en contextos digitales de autoaprendizaje. Apertura (Guadalajara, Jal.), 12(1), 22-38. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.academia.edu/download/31764582/14.pdf" target="_blank" rel="noopener noreferrer") Agudelo, M. (2009). Importancia del diseño instruccional en ambientes virtuales de aprendizaje. Nuevas ideas en informática educativa, 5(2), 118-127.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=kSmU____uiU&ab_channel=INTEF" target="_blank" rel="noopener noreferrer") INTEF.(2020, 22 de julio). Diseño Instruccional [Video] YouTube

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
