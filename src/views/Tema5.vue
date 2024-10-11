<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Los ácidos grasos Omega 3, 6 y 9

    .bg-color-3.p-4(data-aos="fade-up").brounded.mb-5
      .d-flex.align-items-center.justify-content-center
        p.mb-0.me-4 Los ácidos grasos omega-3 y omega-6 son poliinsaturados, mientras que el omega-9 es monoinsaturado. Estos ácidos son esenciales para el cuerpo, ya que participan en la formación de membranas celulares, hormonas, y en el buen funcionamiento del sistema inmunológico y neuronal.
        img(src="@/assets/curso/tema5/45.svg", style="width: 100%; max-width: 60px;")

    .titulo-tres.mb-4(data-aos="flip-up").mb-4
      h4 Omega 3 

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p(data-aos="fade-up").mb-4
          | El omega-3 es un ácido graso poliinsaturado esencial para el organismo, ya que el cuerpo no puede producirlo por sí mismo. Es conocido por sus beneficios en la salud cardiovascular, cerebral y antiinflamatoria. Se encuentra en alimentos como pescados grasos, aceites de pescado, semillas de lino y nueces, y ayuda a reducir el riesgo de enfermedades del corazón y mejorar la función cognitiva.
        p(data-aos="fade-up").mb-4
          | Las fuentes dietéticas de omega-3 son: 

        .bg-color-8.p-4(data-aos="fade-up").brounded.mb-4
          p(data-aos="fade-up").mb-2 #[strong EPA y DHA]
          p(data-aos="fade-up").mb-0 Se encuentran en pescados de agua fría como salmón, caballa, halibut, sardinas, atún y arenque.

        .bg-color-3.p-4(data-aos="fade-up").brounded.mb-4
          p(data-aos="fade-up").mb-2 #[strong Ácido linolénico (LNA)]
          p(data-aos="fade-up").mb-0 Presente en semillas de lino, aceite de linaza, aceite de canola, aceite de soja, semillas de calabaza, y nueces.

        p(data-aos="fade-up").mb-4 Además, el aceite de hígado de bacalao ha sido conocido por sus beneficios para la salud durante siglos, especialmente entre las personas que viven en zonas costeras.

      .col-lg-4
        img(src="@/assets/curso/tema5/46.png", style="width: 100%; max-width: 413px;").mx-auto


    .titulo-tres.mb-4(data-aos="flip-up").mb-4
      h4 Casos en dietas actuales

    p(data-aos="fade-up").mb-4
      | En las #[strong dietas actuales], el equilibrio entre los ácidos grasos omega-3 y omega-6 es un tema importante debido a su impacto en la salud.

    .bg-full-width.bg-fondo-4
      .px-4.px-md-5.pb-5
        .row.justify-content-center
          .col-lg-5.mb-5(data-aos="zoom-in-up")
            .custom-image-card-3.bg-color-5
              img.custom-image-card-3__image(src="@/assets/curso/tema5/47.png" alt="")
              .custom-image-card__text.p-4
                .bg-color-6.d-inline-block.p-2.mb-3
                  h5.text-center.mb-0 #[strong Dieta típica americana]
                p.mb-0 En promedio, se consume entre 14 y 30 veces más omega-6 que omega-3, lo que ha sido relacionado con un aumento en trastornos inflamatorios. Este desequilibrio puede estar vinculado al incremento de enfermedades inflamatorias y crónicas en los Estados Unidos.
          .col-lg-5.mb-5(data-aos="zoom-in")
            .custom-image-card-3.bg-color-5
              img.custom-image-card-3__image(src="@/assets/curso/tema5/48.png" alt="")
              .custom-image-card__text.p-4
                .bg-color-6.d-inline-block.p-2.mb-3
                  h5.text-center.mb-0 #[strong Dieta mediterránea]
                p.mb-0 Esta dieta ofrece un equilibrio más saludable entre los omega-3 y omega-6, lo que ha sido asociado con menores tasas de enfermedades cardíacas. La dieta mediterránea incluye alimentos ricos en omega-3 como granos enteros, frutas y verduras frescas, pescado, aceite de oliva, ajo y un consumo moderado de vino. Además, incorpora ácidos grasos omega-9, que se ha demostrado que reducen los riesgos de cáncer y enfermedades cardíacas.

    .bg-full-width.bg-fondo-2
      .px-4.px-md-5.pb-5
        .titulo-tres.mb-4(data-aos="flip-up").mb-4
          h4 Efectos del omega-3

        p(data-aos="fade-up").mb-4
          | La investigación indica que los ácidos grasos omega-3 pueden prevenir los factores de riesgo asociados con diversas enfermedades crónicas, tales como:

        .row.justify-content-center.align-items-center.mb-5
            .col-lg-5(data-aos="fade-left")
              img(src='@/assets/curso/tema5/49.png', alt='', style="max-width: 505px").mx-auto
            .col-lg-5(data-aos="fade-right")
              .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
                img(src='@/assets/curso/tema5/49-1.svg', alt='', style="max-width: 50px").me-2.mb-0
                span.mb-0 #[strong Enfermedad coronaria, derrame cerebral, y presión arterial alta.]

              .d-flex.bg-color-8.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
                img(src='@/assets/curso/tema5/49-2.svg', alt='', style="max-width: 50px").me-2.mb-0
                span.mb-0 #[strong Resistencia a la insulina (diabetes mellitus).]

              .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
                img(src='@/assets/curso/tema5/49-3.svg', alt='', style="max-width: 50px").me-2.mb-0
                span.mb-0 #[strong Ciertos tipos de cáncer.]

              .d-flex.bg-color-8.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
                img(src='@/assets/curso/tema5/49-4.svg', alt='', style="max-width: 50px").me-2.mb-0
                span.mb-0 #[strong Enfermedades inflamatorias.]

              .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
                img(src='@/assets/curso/tema5/49-5.svg', alt='', style="max-width: 50px").me-2.mb-0
                span.mb-0 #[strong Salud mental y neuronal.]

        .titulo-tres.mb-4(data-aos="flip-up").mb-4
          h4 Omega-6

        .row.justify-content-center.align-items-center
          .col-lg-8(data-aos="flip-left")
            p
              | El ácido linoleico (AL) es uno de los ácidos grasos omega-6 y se puede obtener de aceites como los de soja, maíz, cártamo, girasol, maní, semillas de algodón y fibra de arroz. Otro omega-6 es el ácido araquidónico (AA), que se encuentra en el aceite de maní, carnes rojas, huevos y productos lácteos. Un consumo equilibrado de estos ácidos grasos beneficia el sistema circulatorio al prevenir la formación de coágulos, equilibrar la presión arterial y brindar protección ante ataques cardíacos.
          .col-lg-4(data-aos="fade-left")
            img(src="@/assets/curso/tema5/50.png", style="width: 100%; max-width: 400px;").mx-auto


    .titulo-tres.mb-4(data-aos="flip-up").mb-4
      h4 Omega-9

    
    .row.justify-content-center.align-items-stretch.g-0.mb-5
      .col-lg-8(data-aos="fade-left")
        .bg-color-8.bg-fondo-icon-planta.p-4.h-100
          .row.justify-content-center.align-items-center
            .col-lg-auto(data-aos="fade-right")
              img(src="@/assets/curso/tema5/51.svg", style="max-width: 85px", alt="").mx-auto
            .col-lg
              p.mb-0.mt-lg-4 El ácido oleico, un componente clave de aceites como el de canola, girasol y oliva, es un ácido graso omega-9. Ayuda a disminuir el riesgo de enfermedades cardiovasculares y accidentes cerebrovasculares, además de aumentar los niveles de colesterol bueno (HDL) y facilitar la eliminación de placas de grasa en las arterias.
      .col-lg-4(data-aos="fade-right")
        img(src="@/assets/curso/tema5/52.png", style="max-width: 400px", alt="").mt-xl-0.mt-4

</template>

<script>
export default {
  name: 'Tema5',
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
