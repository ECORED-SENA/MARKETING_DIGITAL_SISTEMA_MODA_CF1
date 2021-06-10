<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        .h3 1
      .h3 Introducción al mercadeo

    p.mb-5 Este concepto ha tenido múltiples definiciones, por lo cual esta ruta formativa se inicia abordando el concepto de mercadeo desde la postura de diferentes autores, #[strong con el propósito de describir la evolución del concepto, su importancia para las organizaciones y cómo se ha llegado al concepto de marketing que hoy prevalece]. A continuación se puede encontrar definciónes de mercadeo en las siguientes tarjetas. 
    
    .row
      .col-md-6.col-lg.mb-5
        .tarjeta-Avatar
          img.img_ava(src='@/assets/curso/tema_1/img_1.svg' alt='AvatarTop')
          .tarjeta.color-secundario.p-4.t-ava
            p La mercadotecnia (marketing o mercadeo) es #[strong la actividad, conjunto de instituciones y procesos para crear, comunicar, entregar e intercambiar ofertas que tienen valor para los consumidores, clientes y socios]. Cabe mencionar que antes se concebía el mercadeo solo en el marco de las ventas (American Marketing Asociation, 2017).

      .col-md-6.col-lg.mb-5
        .tarjeta-Avatar
          img.img_ava(src='@/assets/curso/tema_1/img_2.svg' alt='AvatarTop')
          .tarjeta.color-secundario.p-4.t-ava
            p Según  Philip Kotler y Gary Armstrong (2013), #[strong "el marketing es un proceso social y directivo mediante el que los individuos y las organizaciones obtienen lo que necesitan y desean a través de la creación y el intercambio de valor con los demás”]. (p.5).

    .row
      .col-md-6.col-lg.mb-5
        .tarjeta-Avatar
          img.img_ava(src='@/assets/curso/tema_1/img_3.svg' alt='AvatarTop')
          .tarjeta.color-secundario.p-4.t-ava
            p Stanton, Etzel y Walker, (2007), #[strong "un sistema total de actividades de negocios ideado para planear productos satisfactores de necesidades, asignarles precios, promoverlos y distribuirlos a los mercados meta, a fin de lograr los objetivos de la organización"] (p.6)

      .col-md-6.col-lg.mb-5
        .tarjeta-Avatar
          img.img_ava(src='@/assets/curso/tema_1/img_4.svg' alt='AvatarTop')
          .tarjeta.color-secundario.p-4.t-ava
            p De acuerdo con Solomon y Stuart (como se citó en Rosenstiehl, 2016 ), #[strong “el concepto de marketing implica que, al identificar las necesidades de los consumidores y al suministrar productos que satisfagan estas necesidades, la organización asegura su rentabilidad a largo plazo”] (2001,p.7)

    p.mb-5 Las últimas definiciones tienen elementos comunes en relación con la importancia organizacional, comercial, y se amplía a la esfera social, explicitando el papel cada vez más preponderante que el marketing representa en la sociedad.

    .bloque-texto-a1.color-secundario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
          .h3.mb-0 Evolución del concepto de mercadeo
        .col-lg-8
          .bloque-texto-a1__texto.p-4
            p Este somero recorrido por el concepto de mercadeo, que se puede apreciar en el Video, ayudará a entender su evolución desde un contexto histórico, entendiendo que existen una serie de acontecimientos, como la Revolución Industrial, algunas guerras mundiales y las situaciones económicas vividas durante largos años, que han tenido protagonismo en el surgimiento del concepto y su evolución.

    igure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    
  
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
