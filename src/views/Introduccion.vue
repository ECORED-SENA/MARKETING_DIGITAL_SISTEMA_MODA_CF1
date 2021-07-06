<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        .h3
          i.fas.fa-info
      .h3 Introducción
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/9bZfwswKaEY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Introducción: Fundamentos del mercadeo
    
    p.mb-5 Apreciado aprendiz, bienvenido a este momento de aprendizaje diseñado a partir de un contenido temático, recursos educativos digitales y actividades de aprendizaje que pretenden ayudar en el reconocimiento del plan estratégico de mercadeo de la organización, de acuerdo con los objetivos de la marca. En este sentido, se ha creado un video que presenta el contexto del presente componente de formación y que se encuentra a continuación.

    .cajon--amarillo.p-4
      p Luego de entender las condiciones iniciales, es momento de introducir los fundamentos del mercadeo a través de una conceptualización básica de algunos elementos, haciendo un recorrido por la evolución del concepto de mercadeo hasta llegar a la tendencia del marketing digital, desarrollada hoy con gran fuerza.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
