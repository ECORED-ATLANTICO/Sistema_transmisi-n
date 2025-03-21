<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mb-5 El sistema de transmisión de un vehículo es fundamental para la correcta distribución de la fuerza motriz hacia las ruedas, permitiendo su desplazamiento y estabilidad en diferentes terrenos. Dentro de este sistema, la caja de transferencia y los ejes cumplen un papel clave en la propulsión, ajustándose según el tipo de tracción y la configuración del vehículo.

    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/intro/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los semiejes, los rodamientos y los mecanismos de acoplamiento permiten la conexión eficiente entre el motor y las ruedas, asegurando un movimiento fluido y seguro. Existen diferentes tipos de rodamientos y sistemas de tracción que varían según el diseño del vehículo, ya sea con tracción delantera, trasera o en las cuatro ruedas.
    
   
    .row.align-items-center
      .col-lg-auto
        img(src="@/assets/curso/intro/2.svg", style="max-width: 90px").mx-auto
      .col-lg
        p.mb-0 Además, el ajuste adecuado de los componentes, como las puntas de eje y los sistemas de bloqueo, es esencial para garantizar la estabilidad del vehículo y prolongar la vida útil de sus partes. La correcta instalación y mantenimiento de estos elementos permite mejorar el desempeño del automóvil y su capacidad de respuesta ante diferentes condiciones de conducción.

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
