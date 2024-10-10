<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción


    .row.mb-4.mb-lg-5
      .col-lg(data-aos="fade-left")
        p.mb-0 El componente formativo está enfocado en los componentes bioactivos presentes en los alimentos de origen vegetal, destacando su importancia para la salud humana. Estos compuestos, como los carotenoides, fitoesteroles y polifenoles, juegan un papel esencial en la prevención de enfermedades crónicas no transmisibles.
      .col-lg-auto(data-aos="fade-right")
        img.img-fluid(src="@/assets/curso/intro/1.svg", alt='', style='max-width: 100%').mx-auto.d-none.d-lg-block

    .bg-fondo-gradiente.p-4.ps-lg-5(data-aos="zoom-in").mb-5
      .row
        .col-lg-8.order-2.order-lg-1(style="place-self:center;")
          .bg-white.p-4.p-xl-5
            p.mb-0 En la actualidad, la investigación científica ha revelado los beneficios que estos componentes aportan más allá de la nutrición básica. Los gobiernos y organizaciones de salud promueven su consumo, dado su potencial para reducir el riesgo de enfermedades cardiovasculares, cáncer y otros problemas relacionados con el envejecimiento.
        .col-lg-4.order-1.order-lg-2
          figure.position-relative
            img(src="@/assets/curso/intro/2.svg")#img-intro-2

    p(data-aos="fade-left").mb-5 Además, el componente formativo resalta la importancia de adoptar hábitos alimenticios saludables y de incorporar actividades físicas regulares, lo que contribuye a mejorar la calidad de vida y el bienestar general, fortaleciendo el sistema inmunológico y promoviendo un estilo de vida equilibrado.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
