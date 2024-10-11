<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 La actividad física como factor clave para la salud

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p.mb-4(data-aos="fade-up") La actividad física implica cualquier movimiento del cuerpo que requiera un gasto energético, como caminar, trabajar o realizar tareas domésticas. Cuando estos movimientos se realizan de manera planificada y regular, se les denomina ejercicio físico, el cual es esencial en todas las etapas de la vida, preferiblemente desde edades tempranas.

        .bg-color-3.p-4(data-aos="fade-up").brounded
          p.mb-0 El sedentarismo, resultado de la vida moderna y el ocio centrado en la televisión, el cine y el uso de computadoras, es un importante factor de riesgo para el desarrollo de enfermedades crónicas, especialmente las cardiovasculares.

      .col-lg-4
        img(src="@/assets/curso/tema6/53.png", style="width: 100%; max-width: 413px;").mx-auto

    .bg-full-width.bg-fondo-2
      .px-4.px-md-5.pb-5
        .titulo-tres.mb-4(data-aos="flip-up").mb-4
          h4 Beneficios del ejercicio físico
        
        p(data-aos="fade-up").mb-4
          | Los invitamos a escuchar el siguiente pódcast donde se exploran los #[strong beneficios del ejercicio físico]. A través de este episodio, descubrirán cómo la actividad regular contribuye a #[strong mejorar la salud, prevenir enfermedades] y potenciar el #[strong bienestar integral].

        .row.justify-content-center.align-items-center.mb-5
          .col-lg-7
            .bg-color-9.p-4.brounded
              .row.justify-content-center.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema6/54.svg", alt="", data-aos="fade-up", style="max-width: 270px").m-auto.mb-4.mb-lg-0
                .col-lg
                  h5.text-white Pódcast

                  TarjetaAudio.color-primario.mb-3(
                    texto="Beneficios del ejercicio físico",
                    :audio="require('@/assets/componentes/audios/audio-ej.mp3')"
                    tiempo
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )
          .col-lg-5
            img.img-fluid(src="@/assets/curso/tema6/55.png", alt="", data-aos="fade-up")

    .titulo-tres.mb-4(data-aos="flip-up").mb-4
      h4 Salud mental y ejercicio físico

    p(data-aos="fade-up").mb-4 Estudios han demostrado que la actividad física mejora el estado de ánimo y contribuye a una mayor disposición mental al generar endorfinas. También favorece una buena relación con las personas del entorno.

    p(data-aos="fade-up").mb-4
      | Las recomendaciones para practicar ejercicio físico son: 
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5(data-aos="fade-right")
        .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-1.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 Realizar ejercicios sobre superficies adecuadas como prados suaves.

        .d-flex.bg-color-8.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-2.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 Hacer estiramientos y calentamientos antes de cualquier actividad física.

        .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-3.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 Mantenerse hidratado antes y después del ejercicio.

        .d-flex.bg-color-8.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-4.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 Utilizar calzado suave y ropa cómoda, preferiblemente de algodón y colores claros.

        .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-5.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 Evitar el uso de bolsas de plástico en el abdomen para sudar, ya que impiden la evaporación del sudor.

        .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-6.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 No bañarse inmediatamente después de hacer ejercicio.

        .d-flex.bg-color-8.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-7.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 Esperar al menos dos horas después de una comida fuerte antes de hacer ejercicio.

        .d-flex.bg-color-6.ps-2.pe-3.py-2.mb-2.align-items-center.rounded-pill
          img(src='@/assets/curso/tema6/58-8.svg', alt='', style="max-width: 50px").me-2.mb-0
          span.mb-0 Si se presentan síntomas como presión en el pecho, palpitaciones o mareos, es recomendable detener el ejercicio y consultar a un médico.

      .col-lg-5(data-aos="fade-left")
        img(src='@/assets/curso/tema6/58.png', alt='', style="max-width: 505px").mx-auto


    p(data-aos="fade-up").mb-4
      | Los tipos de actividad física beneficiosa son:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/tema6/59.png', style="max-width: 100%", alt='').m-auto

      .col-lg-9
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg-color-2")
          div(titulo="Actividades aeróbicas")
            p Aumentan la respiración y aceleran el ritmo cardíaco. Pueden ser de intensidad moderada o vigorosa.
          div(titulo="Actividades de fortalecimiento muscular")
            p Hacen los músculos más fuertes, como flexiones y levantamiento de pesas. Se deben trabajar todas las partes del cuerpo.
          div(titulo="Actividades para fortalecer los huesos")
            p Saltar es una de las mejores actividades para fortalecer los huesos, especialmente en niños y adolescentes.
          div(titulo="Actividades de equilibrio y estiramiento")
            p Mejoran la estabilidad y flexibilidad, reduciendo el riesgo de lesiones. Ejemplos incluyen yoga, artes marciales y estiramientos suaves.

</template>

<script>
export default {
  name: 'Tema6',
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
