<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Componentes bioactivos
      

    .row.justify-content-center.align-items-center.mb-5.pb-4
      .col-lg-8
        p(data-aos="fade-right") Uno de los principales desafíos de los gobiernos actuales es la prevención de enfermedades crónicas no transmisibles. En este contexto, la dieta desempeña un rol fundamental, no solo por satisfacer las necesidades nutricionales de cada individuo, sino también como un mecanismo de prevención y control de diversas enfermedades crónicas. 
        .bg-color-2.bg-fondo-icon-planta
          .row.justify-content-center.align-items-center
            .col-xl-auto(data-aos="fade-right")
              img(src="@/assets/curso/tema1/3.svg", style="max-width: 218px", alt="").m-auto.mt-xl-0.mt-4
            .col-xl(data-aos="fade-left")
              .p-4
                p.mb-0 En los países desarrollados, se han investigado sustancias bioactivas, las cuales han sido difundidas por la comunidad científica junto con sus aplicaciones en la dieta. Esto ha contribuido a que el uso de estas sustancias sea cada vez más confiable y aceptado por los consumidores.
      .col-lg-4(data-aos="fade-left")
        img(src="@/assets/curso/tema1/4.png", style="max-width: 400px", alt="").m-auto.mt-lg-0.d-none.d-lg-block
          
    .bg-full-width.bg-fondo-1
      .px-4.px-md-5.pb-5

        .row.justify-content-center.align-items-center.mb-4
          .col-lg-6
            .bg-color-1.p-4.brounded.mb-4
              .row.justify-content-center.align-items-center
                .col-xl-auto(data-aos="fade-right")
                  img(src="@/assets/curso/tema1/6.svg", style="max-width: 100px", alt="").m-auto.mt-xl-0.mt-4
                .col-xl(data-aos="fade-left")
                  p.mb-0 #[strong Los componentes bioactivos] se definen como sustancias que ejercen efectos que van más allá de la simple nutrición. Estos compuestos, que incluyen vitaminas y minerales, se encuentran en pequeñas cantidades en alimentos como vegetales y productos ricos en lípidos.
            
            p(data-aos="fade-left").mb-4 De acuerdo con un informe de salud, las enfermedades crónicas no transmisibles son responsables de dos tercios de las muertes a nivel mundial. 

            p(data-aos="fade-left").mb-5 Las estrategias para mejorar la salud a través de la dieta son:
          .col-lg-6
            img(src="@/assets/curso/tema1/5.svg", style="max-width: 610px", alt="").m-auto.mt-lg-0.d-none.d-lg-block


        .row.justify-content-center
          .col-lg-6
            .row.justify-content-center.align-items-stretch.mb-5
              .col-lg-6.mb-4
                .tarjeta--boton.bg-color-white.p-4.text-center.h-100(data-aos="flip-up").shadow-soft
                  img(src='@/assets/curso/tema1/7.svg', alt='', style="max-width: 90px").mx-auto.mb-4
                  p.text-center Aprovechar las zonas elevadas del terreno para maximizar su uso y crear una barrera natural que brinde protección adicional.
              .col-lg-6.mb-4
                .tarjeta--boton.bg-color-white.p-4.text-center.h-100(data-aos="flip-up").shadow-soft
                  img(src='@/assets/curso/tema1/8.svg', alt='', style="max-width: 90px").mx-auto.mb-4
                  p.text-center Ubicar las barreras arbóreas en oposición a la dirección predominante del viento, con el fin de reducir su impacto en el área de cultivo.


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
