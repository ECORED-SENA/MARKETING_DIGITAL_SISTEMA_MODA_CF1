<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        .h3 2 
      .h3 Tipos de mercadeo

    p.mb-5 Hay diversos tipos de mercadeo, que se direccionan y se mezclan según la intención de la estrategia de las organizaciones. A continuación, se pueden observar los más conocidos. #[strong ¿Cuáles son? ¿Qué características tienen? ¿Cuál de todos elegir para la vida laboral?] Las siguientes tarjetas pueden ayudar a la identificación de las respuestas.

    .row
      .col-lg-4.mb-5
        .tarjeta.color_tar.p-4
          .h4.text-center.mt-5 Directo
          p.mb-4.text-center Basado en la comunicación 
            br
            | directa y bidireccional. Además, 
            br
            | 
            strong una audiencia determinada  
            br 
            | 
            strong y bien segmentada. 
          img.img-a(src='@/assets/curso/tema_2/img_1.png' alt='AvatarTop')

      .col-lg-4.mb-5
        .tarjeta.color-secundario.p-4
          .h4.text-center.mt-5 Online
          p.mb-5.text-center Basado en las acciones y 
            br
            |
            strong contenidos a través del 
            br
            | 
            strong internet.
          img.img-a(src='@/assets/curso/tema_2/img_2.png' alt='AvatarTop')

      .col-lg-4.mb-5
        .tarjeta.color_tar.p-4
          .h4.text-center.mt-5 De nicho
          p.mb-4.text-center Basado en la satisfacción y 
            br
            | resolución de problemas 
            br
            | de #[strong un grupo poblacional] 
            br
            |
            strong específico.
          img.img-a(src='@/assets/curso/tema_2/img_3.png' alt='AvatarTop')

    .row.justify-content-center
      .col-lg-4.mb-5
        .tarjeta.color-secundario.p-4.t-ava
          .h4.text-center.mt-5 De influencia
          p.mb-4.text-center Basado en #[strong las redes]
            br
            | 
            strong sociales y las celebridades 
            br
            | 
            strong para incidir en la toma de 
            br
            | #[strong decisiones] de las compras 
            br
            | de las personas. 
          img.img-a(src='@/assets/curso/tema_2/img_4.png' alt='AvatarTop')

      .col-lg-4.mb-5
        .tarjeta.color_tar.p-4
          .h4.text-center.mt-5 Masivo
          p.mb-5.text-center Busca y logra alcanzar 
            br
            | grupos grandes 
            br
            |
            strong poblacionales sin tener 
            br
            |
            strong en cuenta el nicho. 
          img.img-a(src='@/assets/curso/tema_2/img_5.png' alt='AvatarTop')

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
