<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 A continuación, se muestra un mapa conceptual con los elementos más importantes desarrollados en este componente.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="La síntesis presenta los componentes bioactivos de los alimentos, sustancias que aportan nutrientes y tienen efectos positivos en la salud, ayudando a prevenir enfermedades y mejorar el bienestar. Incluye diferentes tipos de componentes, como carotenoides, fitoesteroles y polifenoles, que contribuyen a la prevención de enfermedades crónicas, actúan como antioxidantes y ayudan a regular el colesterol. También se destacan los ácidos grasos omega (3, 6 y 9), que son beneficiosos para el corazón y la salud cerebral, y la importancia de la actividad física, con recomendaciones para su práctica regular y sus beneficios para el cuerpo y la mente.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
