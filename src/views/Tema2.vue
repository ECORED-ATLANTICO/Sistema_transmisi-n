<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Sistemas de acoplamiento de tracción controlada en propulsor
    
    .row.mb-5
      .col-lg-7
        .row.align-items-center.mb-5
          .col-lg-auto
            img(src="@/assets/componentes/1.svg", style="max-width: 90px").mx-auto
          .col-lg
            p Los ejes de propulsión mencionados hasta ahora han estado conectados de forma permanente para transmitir potencia a las ruedas de un vehículo. Sin embargo, existen sistemas de acoplamiento que pueden ser controlados mecánica o electrohidráulicamente, permitiendo que la tracción en el eje delantero o trasero se active según las necesidades del vehículo.
        div.bg-color.p-5
          p.mb-0.p-5 Un sistema de embragues controlados por una electroválvula (solenoide) regula la presión hidráulica generada por una bomba de presión. Esta presión acciona uno o varios pistones que comprimen los embragues, logrando que el eje de propulsión de entrada se conecte con el eje de salida. De este modo, la tracción hacia el diferencial se ajusta mediante un control computarizado, activando las ruedas motrices cuando es necesario.


      .col-lg-4
        figure.mb-3
          img(src="@/assets/curso/temas/tema2/1.png", data-aos="zoom-in")
        
        .titulo-sexto.color-acento-contenido
          h5 Figura 13.
          span Sistema de embrague multidisco con electroválvula
        .row.justify-content-center.align-items-center
          .col-lg-12.p-3
            figure
              img(src="@/assets/curso/temas/tema2/2.png", data-aos="zoom-in", alt="Freno de disco desmontado, con mordaza, sujeción del disco a la rueda y piezas de fijación como tuercas y pasadores.")

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Tracción en eje delantero
    
    .row.mb-5
      .col-lg-7
        .row.align-items-center.mb-5
          .col-lg-auto
            img(src="@/assets/componentes/1.svg", style="max-width: 90px").mx-auto
          .col-lg
            p En vehículos con tracción en las cuatro ruedas, las ruedas delanteras no requieren tracción en condiciones normales de conducción, como en pavimento seco o en calles urbanas. La tracción en las ruedas directrices genera un mayor esfuerzo en el tren delantero, lo que incrementa el consumo de combustible. Por esta razón, este sistema debe permanecer desconectado cuando no es necesario.
        div.bg-color-7.tarjeta.p-5
          p.mb-0 Para ello, los primeros vehículos con tracción en las cuatro ruedas, como los todoterreno, contaban con un sistema de bloqueo en las manzanas de las ruedas delanteras. Este mecanismo permitía al conductor desconectar la tracción cuando no era necesaria y volver a activarla manualmente al girar una perilla en caso de requerirse.
      .col-lg-4 
        .titulo-sexto.color-acento-contenido
          h5 Figura 14.
          span Mecanismo de bloqueo de rueda libre
        .row.justify-content-center.align-items-center
          .col-lg-10.p-3
            figure
              img(src="@/assets/curso/temas/tema2/3.png", data-aos="zoom-in", alt="Suspensión delantera MacPherson con amortiguadores, resortes y barra estabilizadora para mejorar la conducción.")
    
    .row.mb-5.justify-content-center.align-items-center.bg-color-10.tarjeta.p-4
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/temas/tema2/4.png", data-aos="zoom-in")
        
      .col-lg-6
        img.mb-3(src="@/assets/componentes/1.svg", style="max-width: 100px")
        p.mb-0 Estos bloqueos consistían en sistemas que fijaban el eje a la manzana de la rueda. Cuando estaban activados, la manzana quedaba solidaria al eje de propulsión, transmitiendo la tracción. Al desactivarlos, la rueda giraba libremente sobre sus rodamientos sin recibir tracción.
    
    .row.mb-5
      .col-lg-6
        .row.align-items-center.mb-5
          .col-lg-auto
            img(src="@/assets/componentes/1.svg", style="max-width: 90px").mx-auto
          .col-lg
            p En este sistema, la acción de propulsión hace que los candados se bloqueen automáticamente al eje en contra de la maza de la rueda, permitiendo que la tracción se active de manera automática..
        figure
          img(src="@/assets/curso/temas/tema2/5.png", data-aos="zoom-in")
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 15.
          span Sistema de embrague multidisco con electroválvula
        .row.justify-content-center.align-items-center
          .col-lg-12.p-3
            figure
              img(src="@/assets/curso/temas/tema2/6.png", data-aos="zoom-in", alt="Ensamble del cubo de rueda con punta de eje, rodamientos y sujeción mediante tuercas y tapagrasas.")
            div.bg-color-7.tarjeta.p-4
              p.mb-0 Para desactivar este candado automático, es necesario seleccionar la caja de transferencia en la posición de tracción en el eje posterior (dos ruedas motrices) y, al mismo tiempo, dejar de aplicar fuerza con el acelerador. Esto permite que los ejes se liberen de los candados, restableciendo el giro libre de las ruedas delanteras.
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Sistema controlado de tracción en semieje delantero
    
    .bg-full-width.bg-fondo-2
      .p-5
        p.mb-5 Este sistema innovador gestiona la tracción en los semiejes delanteros de un vehículo con tracción en las cuatro ruedas, activándola solo cuando es necesario mediante un computador. El sistema opera desconectando uno de los dos semiejes delanteros, lo que impide que las ruedas tengan tracción. Cuando se requiere activarla, el sistema reconecta el semieje, permitiendo la transferencia de fuerza a las ruedas delanteras. Los componentes son:
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0.order-2
        
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema2/8.png' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Computador
                    p.text-center Recibe información de los sensores de velocidad, condiciones del terreno y acciones del conductor.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema2/9.png' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Sensores
                    p.text-center Detectan la velocidad y el estado del camino.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema2/10.png' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Electroválvula
                    p.text-center Recibe pulsos eléctricos del computador y permite el paso de una depresión hacia el actuador neumático.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema2/11.png' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Actuador neumático
                    p.text-center Activa una horquilla que engrana ambas mitades del semieje.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema2/12.png' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Horquilla de engranaje
                    p.text-center Une las dos mitades del semieje, permitiendo la transmisión de la tracción a las ruedas delanteras.
              .col-lg-4.order-1
                figure
                  img(src='@/assets/curso/temas/tema2/7.png', alt='')
    
    p.mb-5 Cuando las condiciones lo requieren, el computador procesa la información recibida y envía pulsos eléctricos a la electroválvula. Esta acción permite el paso de una depresión hacia el actuador neumático, que a su vez empuja la horquilla para engranar ambas mitades del semieje, asegurando la transmisión de la fuerza propulsora a las ruedas delanteras.

    .row.mb-5.justify-content-center
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 16.
          span Sistema de acoplamiento 4WD - 2WD con actuador de vacío
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-12.py-4
            figure
              img(src="@/assets/curso/temas/tema2/13.png", data-aos="zoom-in", alt="Sistema de freno de mano con zapatas y sensor ABS, regulando la presión de frenado para mayor seguridad.")
    
</template>

<script>
export default {
  name: 'Tema2',
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
