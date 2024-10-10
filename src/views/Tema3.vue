<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Esteroles vegetales


    .row.justify-content-center.align-items-stretch.g-0.mb-5
      .col-lg-8(data-aos="fade-left")
        .bg-color-3.bg-fondo-icon-planta.p-4.h-100
          p.mb-0 Los esteroles vegetales, conocidos como fitoesteroles o fitosteroles, son alcoholes derivados del escualeno, como el colesterol. A lo largo de la evolución, el ser humano ha consumido grandes cantidades de alimentos de origen vegetal, ricos en proteínas, fibras y fitoesteroles. Aunque el colesterol es el principal esterol en animales y humanos, en las plantas se encuentra una amplia variedad de esteroles. Existen dos tipos de fitoesteroles:
      .col-lg-4(data-aos="fade-right")
        .bg-color-5.p-4
          img(src="@/assets/curso/tema3/20.svg", style="max-width: 275px", alt="").m-auto.mt-xl-0.mt-4


    .row.justify-content-center.align-items-center.mb-2
      .col-lg-8
        .row.justify-content-center.align-items-stretch
          .col-lg-6.mb-4
            .tarjeta--boton.bg-color-2.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema3/21.svg', alt='', style="max-width: 82px").mx-auto.mb-4
              p.text-center Esteroles con doble enlace en el anillo de esterol.
          .col-lg-6.mb-4
            .tarjeta--boton.bg-color-5.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema3/22.svg', alt='', style="max-width: 82px").mx-auto.mb-4
              p.text-center Esteroles sin doble enlace en el anillo de esterol.

    p(data-aos="fade-left") Los fitoesteroles, como el sitosterol y el campesterol, son compuestos presentes en las plantas y en la dieta humana. A diferencia del colesterol, que se deriva tanto de la dieta como de la síntesis endógena, los fitoesteroles provienen exclusivamente de la dieta, ya que los humanos no pueden sintetizarlos.

    p(data-aos="fade-left").mb-4 Las propiedades de los fitoesteroles son:

    .bg-full-width.bg-fondo-4.mb-3
      .px-4.px-md-5.pb-5
        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-4.mb-4
            .tarjeta--boton.bg-color-5.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema3/23.svg', alt='', style="max-width: 90px").mx-auto.mb-4
              .bg-color-6.d-inline-block.p-2.mb-3
                h5.text-center.mb-0 #[strong Reducción del colesterol]
              p.text-center Desde los años 50, los fitoesteroles han demostrado reducir los niveles de colesterol. En cantidades adecuadas, inhiben hasta un 14% de la absorción de colesterol. Más de 60 estudios clínicos han validado su eficacia.

          .col-lg-4.mb-4
            .tarjeta--boton.bg-color-3.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema3/24.svg', alt='', style="max-width: 90px").mx-auto.mb-4
              .bg-color-7.d-inline-block.px-2.py-1.mb-3
                h5.text-center.mb-0 #[strong Descubrimientos y aplicaciones]
              p.text-center En los años 70, el interés en los fitoesteroles disminuyó debido a efectos inconsistentes y el descubrimiento de la sitosterolemia. En 1995, los alimentos enriquecidos con ésteres de fitoesteroles revitalizaron su uso.

          .col-lg-4.mb-4
            .tarjeta--boton.bg-color-3.p-4.text-center.h-100(data-aos="flip-up")
              img(src='@/assets/curso/tema3/25.svg', alt='', style="max-width: 90px").mx-auto.mb-4
              .bg-color-7.d-inline-block.px-2.py-1.mb-3
                h5.text-center.mb-0 #[strong Impacto en la salud cardiovascular]
              p.text-center Una reducción del 10% en el colesterol plasmático puede reducir el riesgo de enfermedad cardiovascular entre un 20% y un 55%, dependiendo de factores como la edad y condiciones individuales.

        .row.justify-content-center.align-items-center
          .col-lg-8
            .bg-color-1.p-4.brounded
              .row.justify-content-center.align-items-center
                .col-lg-auto(data-aos="fade-right")
                  img(src='@/assets/curso/tema3/26.svg', alt='', style="max-width: 100px")
                .col-lg(data-aos="fade-right")
                  p.mb-0 El aceite de oliva, el aceite de semillas y los frutos secos son fuentes naturales de fitoesteroles, compuestos que ayudan a reducir los niveles de colesterol en el cuerpo. Además, hoy en día se pueden encontrar fitoesteroles añadidos en alimentos como margarinas, yogures y otros productos lácteos, diseñados específicamente para mejorar la salud cardiovascular.

    .titulo-tres.mb-4(data-aos="flip-up").mb-4
      h4 Consumo habitual de esteroles

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p(data-aos="fade-left") El consumo habitual de esteroles vegetales en la dieta diaria varía entre 170 y 385 mg, mientras que en los vegetarianos la ingesta puede llegar a 500-800 mg al día. Sin embargo, estos niveles no tienen un impacto significativo en la reducción del colesterol.
	 
        p(data-aos="fade-left") Los datos clave sobre los esteroles vegetales son:
      .col-lg-4(data-aos="fade-right")
        img(src="@/assets/curso/tema3/27.png", style="max-width: 400px", alt="").m-auto.mt-xl-0.mt-4

    .bg-full-width.bg-fondo-3.mb-3
      .px-4.px-md-5.pb-5
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="flip-up")
          h5 Figura 1. 
          span Colesterol en el intestino  

        .row.justify-content-center.align-items-center.mb-5
          .col-lg-7
            AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg-color-2")
              div(titulo="Ingesta recomendada")
                p Un consumo diario de 1,5 g de esteroles vegetales puede reducir los niveles de colesterol en un 10-15% en tres meses, disminuyendo el riesgo de enfermedades cardiovasculares en un 25%.
              div(titulo="Absorción")
                p Los esteroles vegetales tienen una absorción menor al 5%, mientras que el colesterol se absorbe entre un 40% y 70%.
              div(titulo="Excreción")
                p La baja absorción, combinada con una alta tasa de excreción biliar, mantiene la concentración de esteroles vegetales en plasma a niveles bajos en condiciones normales.
          .col-lg-5
            img(src="@/assets/curso/tema3/28.png", style="max-width: 505px", alt="").m-auto

    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-auto(data-aos="fade-left")
        img(src="@/assets/curso/bullets/icon-2.svg", style="max-width: 85px", alt="").m-auto
      .col-lg(data-aos="fade-left")
        p.mb-0 Estos datos reflejan la importancia de un consumo adecuado de esteroles vegetales para la salud cardiovascular.

    .titulo-tres.mb-4(data-aos="flip-up").mb-5
      h4 Esteroles, digestión y absorción

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p(data-aos="fade-left") En promedio, #[strong alrededor del 50 % del colesterol] de la dieta se absorbe durante la digestión. Sin embargo, cuando se consumen #[strong ésteres de esteroles vegetales], estos se hidrolizan a #[strong esteroles libres], y solo una pequeña cantidad de ellos se incorpora al torrente sanguíneo. Esto tiene un impacto directo en la #[strong reducción de la absorción de colesterol], lo que, junto con una disminución de su síntesis endógena, contribuye a una reducción de los niveles de colesterol total y LDL en sangre, disminuyendo así el riesgo de padecer enfermedades coronarias.
   
        p(data-aos="fade-left") Los puntos clave sobre la interacción entre fitoesteroles y colesterol son:

      .col-lg-4(data-aos="fade-right")
        img(src="@/assets/curso/tema3/29.svg", style="max-width: 386px", alt="").m-auto.mt-xl-0.mt-4

    TabsA.color-acento-botones.mb-5
      .tarjeta.p-4(titulo="Afinidad por las micelas lipídicas").tarjeta--azul
        h5 Afinidad por las micelas lipídicas 
        p Los fitoesteroles tienen mayor afinidad por las micelas lipídicas que el colesterol debido a su naturaleza hidrofóbica.

      .tarjeta.p-4(titulo="Reducción de absorción de colesterol").tarjeta--azul
        h5 Reducción de absorción de colesterol 
        p Una mayor proporción de fitoesteroles en las micelas reduce la absorción de colesterol, promoviendo su eliminación fecal.

      .tarjeta.p-4(titulo="Impacto en la salud cardiovascular").tarjeta--azul
        h5 Impacto en la salud cardiovascular 
        p La disminución en la absorción y síntesis de colesterol contribuye directamente a la reducción del colesterol total en sangre, previniendo enfermedades coronarias.

    .titulo-tres.mb-4(data-aos="flip-up").mb-5
      h4 Productos con fitoesteroles

    .bg-full-width.bg-fondo-5.mb-3
      .px-4.px-md-5.pb-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-8
            p(data-aos="fade-left").mb-4 Los fitoesteroles se encuentran en alimentos como aceites vegetales, frutos secos, semillas, cereales, legumbres, frutas y verduras. Además, se pueden encontrar en productos enriquecidos con fitoesteroles, como margarinas, yogures y otros productos lácteos. Estos alimentos están diseñados para mejorar la salud cardiovascular y reducir los niveles de colesterol en el cuerpo.

            .bg-color-1.p-3.brounded
              .row.justify-content-center.align-items-center
                .col-lg-auto(data-aos="fade-right")
                  img(src='@/assets/curso/tema3/31.svg', alt='', style="max-width: 79px")
                .col-lg(data-aos="fade-right")
                  p.mb-0 Estos productos deben consumirse como parte de una dieta equilibrada y variada, que incluya frutas y hortalizas de manera regular.

          .col-lg-4(data-aos="fade-right")
            img(src="@/assets/curso/tema3/30.png", style="max-width: 400px", alt="").m-auto.mt-xl-0.mt-4
</template>

<script>
export default {
  name: 'Tema3',
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
