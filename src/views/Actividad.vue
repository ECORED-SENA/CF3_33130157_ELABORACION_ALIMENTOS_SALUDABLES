<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    #Actividad                
      <Actividad :cuestionario="cuestionario" />

</template>

<script>
import Actividad from '@/components/actividad/Actividad'
export default {
  name: 'ActividadDidactica',
  components: { Actividad },
  data: () => ({
    cuestionario: {
      tema: 'Componentes bioactivos',
      titulo: 'Cuestionario: Componentes bioactivos y su impacto en la salud',
      introduccion:
        '<b> Objetivo:</b> identificar los principales componentes bioactivos presentes en los alimentos, como los carotenoides, fitoesteroles y polifenoles, y reconozcan su relevancia en la prevención de enfermedades crónicas.',
      barajarPreguntas: false,
      preguntas: [
        {
          id: 1,
          texto: '¿Qué son los componentes bioactivos?',
          imagen: require('@/assets/actividad/1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Sustancias presentes solo en alimentos animales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Sustancias presentes en alimentos que aportan beneficios más allá de la nutrición.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Sustancias utilizadas en suplementos únicamente.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Compuestos que solo mejoran el sabor de los alimentos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto: '¿Cuál de los siguientes es un carotenoide?',
          imagen: require('@/assets/actividad/2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Colesterol.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Omega 9.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Ácido linoleico.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Beta-caroteno.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: '¿Qué beneficios aportan los fitoesteroles?',
          imagen: require('@/assets/actividad/3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Ayudan a reducir el colesterol.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Aumentan el colesterol en sangre.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Previenen la obesidad.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Incrementan el azúcar en sangre.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto: '¿Cuál es una fuente principal de ácidos grasos omega-3?',
          imagen: require('@/assets/actividad/4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Aceite de coco.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Aceite de pescado.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Carne de res.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Mantequilla.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            'Según estudios, el consumo de polifenoles está relacionado con:',
          imagen: require('@/assets/actividad/1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El aumento del riesgo de cáncer.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El desarrollo de enfermedades cardiovasculares.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La reducción de antioxidantes en el cuerpo.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'La prevención de enfermedades del envejecimiento.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué tipo de actividad física es clave para fortalecer los músculos?',
          imagen: require('@/assets/actividad/2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Meditación.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Saltar cuerda.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Levantamiento de pesas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Correr largas distancias.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: 'El té verde es conocido por',
          imagen: require('@/assets/actividad/3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Ser una fuente de vitaminas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Ser rico en catequinas antioxidantes.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Ser rico en proteínas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Aumentar el colesterol LDL.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            'Los carotenoides son responsables de los colores amarillo, naranja y rojo en muchas plantas.',
          imagen: require('@/assets/actividad/4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            'Los polifenoles no tienen ningún impacto en la prevención del cáncer.',
          imagen: require('@/assets/actividad/1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            'La actividad física puede ayudar a reducir los niveles de estrés y mejorar el estado de ánimo.',
          imagen: require('@/assets/actividad/2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
  computed: {},
  methods: {},
}
</script>
