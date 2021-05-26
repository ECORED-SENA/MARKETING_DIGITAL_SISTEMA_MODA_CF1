<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        .h3 4 
      .h3 Variables del mercado

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        .cajon--morado_1.p-5
          p El marketing mezclado es uno de los elementos clásicos del marketing, el cual engloba los cuatros componentes básicos: #[strong precio, producto, comunicación y distribución.] Estas variables son conocidas como las 4P por su acepción anglosajona (product, price, place y promotion). En el siguiente gráfico interactivo, se puede apreciar de qué se trata cada una de ellas.
        
      .col-lg-6
        img.img-a(src='@/assets/curso/tema_4/img_1.png')

    TabsB.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="Producto" :icono="require('@/assets/curso/tema_4/img_2.svg')")
        .row.justify-content-center.align-items-center
          .col-md-3.mb-4.mb-md-0
            .h4 ¿Cuál es tu producto 
              br
              | o servicio?
          .col-md-6
            p.mb-3 El producto podría definirse como #[strong todo lo que se pone a disposición del consumidor, y puede comprender bienes y servicios]. Según Lam, Hair & McDaniel (2011), el producto es la gran pieza clave dentro del marketing mix (producto, precio, promoción y distribución); además, consideran al #[strong producto como elemento primordial dentro del proceso de producción], debido a que es el punto de partida de toda comercialización.

            p Dichos productos se deben diferenciar de otros y postularse como únicos a través de las cualidades o atributos que se les ponga. Es posible hablar de variedad, diseño, características, marcas, servicios, garantías.
      .py-4.py-md-5(titulo="Precio" :icono="require('@/assets/curso/tema_4/img_3.svg')")
        .row.justify-content-center.align-items-center
          .col-md-3.mb-4.mb-md-0
            .h4 ¿Cuánto cobras? 
              br
              | ¿Cómo afecta esto tu marca? 
          .col-md-6
            p Es la variable relacionada con los ingresos, o la suma de valores que se requiere para  realizar un intercambio, es decir, #[strong la cantidad de dinero que se requiere para adquirir un producto y/o servicio]. 
            p.mb-3 Para Baena y Moreno (2010), es el costo que debe desembolsar o pagar el consumidor (cliente) para obtener la mercancía en un momento dado, ya sea en el mercado o en el lugar específico de venta (p.97). 

            p Como indicadores del precio, se podrían plantear el precio del valor para el cliente y los precios según la competencia.
      .py-4.py-md-5(titulo="Promoción" :icono="require('@/assets/curso/tema_4/img_4.svg')")
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            .h4 ¿Cómo se enteran tus clientes de tus productos? 
              br
              | ¿Qué estrategias utilizas?
            
        
          .col-md-6
            p.mb-3 Son las técnicas de publicidad  para dar a conocer el servicio o producto en un mercado determinado. Podemos dar cuenta de medios, canales y técnicas  que nos posibilitan dar a conocer nuestro producto.
 
            p Kotler y Armstrong (2013) definen la promoción como 
              strong el conjunto de actividades sistemáticas que promueven información y datos sobre las cualidades de un producto o servicio para inculcar y promover la adquisición por parte del comprador.

      .py-4.py-md-5(titulo="Plaza" :icono="require('@/assets/curso/tema_4/img_5.svg')")
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0
            .h4 ¿Dónde promocionas tu producto o servicio?
              br
              | ¿Dónde te encuentran los clientes?
          .col-md-6
            p Hace referencia  a los 
              strong lugares de venta y a los canales de distribución.
          
        
      
    .row.mb-5
      .col-lg-6
        .cajon--amarillo.p-4
          p El avance más significativo, sin duda, fue el paso del marketing al mundo digital; sin embargo, a pesar de que han sido significativas en las estrategias de marketing por muchos años, 
            strong las 4P han evolucionado con las necesidades del mercado y han sido sustituidas por las 4C.  
      .col-lg-6  
        p Con las 4C, #[strong se distinguen cuatro importantes aspectos a tener en cuenta para entender y desplegar una estrategia]. Ellos son: consumidor, costo, conveniencia y comunicación. Este modelo fue propuesto por Robert F. Lauterborn, en 1990, quien vio la necesidad de actualizar, al entorno digital, el modelo del mercadeo tradicional de 4P (producto, precio, plaza y promoción), sin perder su esencia (Shum Xie, 2019). Observe a continuación sus cualidades en el recurso educativo. 

    .row
      .col-lg-3.mb-5
        .tarjeta.color_tar.p-4.alt_tarj
          .h3 01
          .h4 Consumidor
          img.mb-3.img-b(src='@/assets/curso/tema_4/img_6.png')
          p Todas las estrategias para promocionar y vender un producto se basan en #[strong los gustos, deseos y necesidades de los consumidores], por ello, el marketing digital está tan enfocado en conocer y analizar su público través de diversas técnicas para lograr efectividad en sus procesos.

      .col-lg-3.mb-5
        .tarjeta.color-secundario.p-4.alt_tarj
          .h3 02
          .h4 Costo
          img.mb-3.img-b(src='@/assets/curso/tema_4/img_6.png')
          p Este se entiende como el precio a pagar por un bien o servicio, el cual puede depender de distintos factores, como la producción, la calidad o el poder adquisitivo del público objetivo. Esta información será usada por el consumidor para 
            strong decidir si adquiere o no dicho elemento.

      .col-lg-3.mb-5
        .tarjeta.color_tar.p-4.alt_tarj
          .h3 03
          .h4 Conveniencia
          img.mb-3.img-b(src='@/assets/curso/tema_4/img_6.png')
          p Supone el proceso de compra, teniendo en cuenta el servicio al cliente, #[strong la comodidad del consumidor y claridad de información del producto] o servicio que va a adquirir, lo que permite fidelizar a un público.

      .col-lg-3.mb-5
        .tarjeta.color-secundario.p-4.alt_tarj
          .h3 04
          .h4 Comunicación
          img.mb-3.img-b(src='@/assets/curso/tema_4/img_6.png')
          p Los procesos comunicativos dentro del marketing digital juegan un papel muy importante, estos pueden definir la personalidad, interacción y conexión de la marca con su público; además, #[strong permiten realizar una entrega de información coherente] que logre una capitalización del tiempo invertido en lograr estos lazos de unión.



</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
