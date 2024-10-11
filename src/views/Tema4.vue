<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Compuestos fenólicos o polifenoles

    .bg-color-3.bg-fondo-icon-planta
      .row.justify-content-center.align-items-stretch.g-0.mb-5
        .col-lg-8(data-aos="fade-left")
          .p-4
            p.mb-0.mt-lg-4 Los #[strong polifenoles] constituyen una amplia familia de más de 8000 compuestos, siendo los más comunes los #[strong fenoles simples] y los #[strong flavonoides] (aproximadamente 4000 identificados). Estos compuestos se encuentran presentes en muchos alimentos y bebidas.
        .col-lg-4(data-aos="fade-right")
          img(src="@/assets/curso/tema4/32.png", style="max-width: 400px", alt="").m-auto.mt-xl-0.mt-4


    

    .bg-full-width.bg-fondo-4.mb-3.mb-lg-5
      .px-4.px-md-5.pb-5
        p(data-aos="fade-up").mb-4 Los beneficios de los polifenoles son:
        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-4.mb-4
            .tarjeta--boton.bg-color-5.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema4/33.svg', alt='', style="max-width: 90px").mx-auto.mb-4
              .bg-color-6.d-inline-block.p-2.mb-3
                h5.text-center.mb-0 #[strong Reducción del riesgo de enfermedades]
              p.text-center Los estudios sugieren que el consumo de polifenoles está asociado a una menor incidencia de enfermedades cardíacas y ciertos tipos de cáncer, especialmente relacionadas con el envejecimiento.

          .col-lg-4.mb-4
            .tarjeta--boton.bg-color-3.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema4/34.svg', alt='', style="max-width: 90px").mx-auto.mb-4
              .bg-color-7.d-inline-block.px-2.py-1.mb-3
                h5.text-center.mb-0 #[strong Propiedades antioxidantes]
              p.text-center Los polifenoles protegen a las células del daño de los radicales libres, evitando la oxidación del colesterol LDL y reduciendo el riesgo de enfermedades cardíacas.

          .col-lg-4.mb-4
            .tarjeta--boton.bg-color-3.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema4/35.svg', alt='', style="max-width: 90px").mx-auto.mb-4
              .bg-color-7.d-inline-block.px-2.py-1.mb-3
                h5.text-center.mb-0 #[strong Prevención del cáncer]
              p.text-center Polifenoles como la epigalocatequina-3-galato (EGCG) bloquean enzimas que permiten el crecimiento tumoral y desactivan sustancias que promueven el desarrollo del cáncer.

    .bg-full-width.bg-fondo-4b.mb-3.mb-lg-5
      .px-4.px-md-5.pb-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-5
            .titulo-sexto.color-acento-contenido.mb-4(data-aos="flip-up")
                h5 Tabla 1. 
                span Contenidos de polifenoles en algunos alimentos
            .tabla-a.color-secundario
              table
                thead
                  tr
                    th(style="width: 70%") Alimento (ración)
                    th(style="width: 30%").text-center mg/ración
                tbody.bg-color-white
                  tr
                    td Manzana con piel (150g)
                    td 166
                  tr
                    td Uva negra (150g)
                    td 133
                  tr
                    td Té negro (200ml)
                    td 132
                  tr
                    td Té verde (200ml)
                    td 319
                  tr
                    td Vino tinto (100ml)
                    td 106-178
                  tr
                    td Moras (50g)
                    td 116
                  tr
                    td Chocolate negro (40g)
                    td 189
                  tr
                    td Naranja (150g)
                    td 74

    .titulo-tres.mb-4(data-aos="flip-up").mb-5
      h4 Té verde

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-8
        p(data-aos="fade-left").mb-4 El té verde, proveniente de la planta Camellia sinensis, ha sido cultivado originalmente en Japón y utilizado en China por cerca de 4000 años, no solo por sus propiedades estimulantes, sino también por su capacidad para prevenir y tratar diversas dolencias.

        p(data-aos="fade-left").mb-4 El té es la segunda bebida más consumida en el mundo después del agua, con una producción anual de tres billones de kilogramos. A diferencia del té negro, el té verde no es fermentado; las hojas frescas se someten a torrefacción, luego se prensan, enrollan, trituran y secan. Los chinos fueron los primeros en descubrir el té, que se utilizaba como bebida medicinal para promover la salud física y mental durante milenios.
      .col-lg-4
        img(src='@/assets/curso/tema4/36.png', alt='', style="max-width: 400px").mx-auto.mb-4

    .titulo-tres.mb-4(data-aos="flip-up").mb-5
      h4 Tipos de té

    p(data-aos="fade-left") Existen cuatro tipos principales de té, cada uno con múltiples variedades que suman más de 3000 tipos en todo el mundo:

    .bg-full-width.bg-fondo-3.mb-3.mb-lg-5
      .px-4.px-md-5.pb-5
        .row.justify-content-center
          .col-lg-3.mb-5(data-aos="zoom-in-up")
            .custom-image-card-3.bg-color-8
              img.custom-image-card-3__image(src="@/assets/curso/tema4/37.png" alt="")
              .custom-image-card__text.p-4
                p.mb-3 #[strong Té blanco]
                p.mb-0 Se elabora con yemas nuevas recolectadas antes de abrirse, que se marchitan y secan.
          .col-lg-3.mb-5(data-aos="zoom-in")
            .custom-image-card-3.bg-color-8
              img.custom-image-card-3__image(src="@/assets/curso/tema4/38.png" alt="")
              .custom-image-card__text.p-4
                p.mb-3 #[strong Té verde ]
                p.mb-0 Se seca y se somete a un tratamiento térmico (vapor y secado) para detener la fermentación y la actividad enzimática.
          .col-lg-3.mb-5(data-aos="zoom-in-left")
            .custom-image-card-3.bg-color-8
              img.custom-image-card-3__image(src="@/assets/curso/tema4/39.png" alt="")
              .custom-image-card__text.p-4
                p.mb-3 #[strong Té rojo]               
                p.mb-0 Se encuentra entre el té verde y el té negro. Las hojas se secan al aire libre y luego se dejan secar más tiempo en interiores.
          .col-lg-3.mb-5(data-aos="zoom-in-left")
            .custom-image-card-3.bg-color-8
              img.custom-image-card-3__image(src="@/assets/curso/tema4/40.png" alt="")
              .custom-image-card__text.p-4
                p.mb-3 #[strong Té negro]               
                p.mb-0 Se deja marchitar, se enrolla, fermenta y luego se seca. Tiene un mayor contenido aromático debido a la fermentación de los polifenoles.


        p(data-aos="fade-left").mb-5 Los niveles de compuestos en té verde y negro son: 


        .row.justify-content-center.align-items-center.mb-5
          .col-lg-6
            .titulo-sexto.color-acento-contenido.mb-4(data-aos="flip-up")
                h5 Tabla 2. 
                span Los niveles de compuestos en té verde y negro
            .tabla-a.color-secundario
              table
                thead
                  tr
                    th Compuesto
                    th Té verde (1 taza)
                    th Té negro (1 taza)
                tbody.bg-color-white
                  tr
                    td Catequinas	
                    td 60-125 mg	
                    td 30-60 mg
                  tr
                    td Teaflavinas	
                    td 0 mg	
                    td 3.0-60 mg
                  tr
                    td Cafeína	
                    td 20-50 mg	
                    td 30-60 mg
                  tr
                    td L-teína	
                    td 20-40 mg	
                    td 20-40 mg

    .titulo-tres.mb-4(data-aos="flip-up").mb-5
      h4 Epigalocatequina-3-galato (EGCG)

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p(data-aos="fade-left").mb-5 El (-)-Epigalocatequina-3-galato (EGCG) es el polifenol más abundante en el té verde y representa más del 50% de las catequinas totales. Numerosos estudios sugieren que el EGCG es responsable de muchos de los beneficios para la salud asociados al consumo de té verde.
      .col-lg-4
        img(src='@/assets/curso/tema4/41.png', alt='', style="max-width: 400px").mx-auto.mb-4
        
    .bg-full-width.bg-fondo-5.mb-3
      .px-4.px-md-5.pb-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-6
            img(src='@/assets/curso/tema4/42.svg', alt='').mx-auto.mb-4

    .titulo-tres.mb-4(data-aos="flip-up").mb-5
      h4 Beneficios del té verde
    
    p(data-aos="fade-left").mb-5 Diversas investigaciones han comprobado que el té verde puede ayudar a prevenir enfermedades como:

    .bg-full-width.bg-fondo-7.mb-3.mb-lg-5
      .px-4.px-md-5.pb-5

        .row.justify-content-center.align-items-center.mb-5
          .col-lg-5
            img(src='@/assets/curso/tema4/43.png', alt='', style="max-width: 505px").mx-auto
          .col-lg-3
            .d-flex.bg-color-6.px-2.py-1.mb-1.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-1.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Cáncer]

            .d-flex.bg-color-6.px-2.py-1.mb-1.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-2.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Enfermedades cardíacas]

            .d-flex.bg-color-6.px-2.py-1.mb-1.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-3.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Diabetes]

            .d-flex.bg-color-6.px-2.py-1.mb-1.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-4.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Obesidad]

            .d-flex.bg-color-6.px-2.py-1.mb-1.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-5.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Enfermedades hepáticas]

            .d-flex.bg-color-6.px-2.py-1.mb-1.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-6.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Envejecimiento prematuro]

            .d-flex.bg-color-6.px-2.py-1.mb-1.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-7.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Caries]

            .d-flex.bg-color-6.px-2.py-1.mb-0.align-items-center.rounded-pill
              img(src='@/assets/curso/tema4/43-8.svg', alt='', style="max-width: 50px").me-2.mb-0
              span.mb-0 #[strong Reducción del estrés]
          
        .titulo-tres.mb-4(data-aos="flip-up").mb-5
          h4 ¿Cómo previenen las catequinas el cáncer?

        .bg-color-3.bg-fondo-icon-planta
          .row.justify-content-center.align-items-stretch.g-0.mb-5
            .col-lg-8(data-aos="fade-left")
              .p-4
                ul.custom-list
                  li.mb-1 Actúan como potentes antioxidantes, protegiendo el cuerpo del daño de los radicales libres.
                  li.mb-1 Interfieren en la adhesión de sustancias cancerígenas al ADN de las células.
                  li.mb-0 Colaboran con antioxidantes y enzimas del intestino, hígado y pulmones para inhibir la formación de tumores.
            .col-lg-4(data-aos="fade-right")
              img(src="@/assets/curso/tema4/44.png", style="max-width: 400px", alt="").m-auto.mt-xl-0.mt-4


</template>

<script>
export default {
  name: 'Tema4',
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
