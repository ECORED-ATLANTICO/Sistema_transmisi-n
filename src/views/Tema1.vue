<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Transmisión de la fuerza motriz hasta las ruedas
    
    .bg_img
      p.mb-4 Un vehículo puede tener tracción en las ruedas delanteras,  en la mayoría de los automóviles de pasajeros. En estos casos, las ruedas traseras no reciben fuerza motriz y solo giran sobre su propio eje.

      .row.mb-5.justify-content-center
        .col-lg-10.p-4.bg-color-1.tarjeta
          .row
            .col-lg-6.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/temas/tema1/1.png", data-aos="zoom-in")
            .col-lg-6
              .bg-color.p-4.mb-3
                p.mb-0(data-aos="fade-left") En los vehículos con tracción en las ruedas traseras, la propulsión generada por el motor impulsa al vehículo desde estas, mientras que las ruedas delanteras giran únicamente sobre su eje y cumplen la función de dirección, sin recibir fuerza motriz.
              .row.align-items-start
                .col-lg-auto
                  img(src="@/assets/componentes/1.svg", style="max-width: 90px").mx-auto
                .col-lg
                  p.mb-0 Por otro lado, algunos vehículos modernos han incorporado tracción en las cuatro ruedas, especialmente en modelos todoterreno y otros vehículos especiales.

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Semiejes de propulsión

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/temas/tema1/3.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Cuando la fuerza motriz del vehículo se transmite a las ruedas delanteras, los semiejes son los encargados de llevar la energía desde el diferencial hasta las mazas de las ruedas, permitiendo su movimiento. En la figura se presenta cómo los semiejes se conectan al sistema diferencial y, en este caso particular, incluyen juntas homocinéticas. Debido a que estas ruedas deben girar en curvas, los ejes están asentados en rodamientos y se mantienen solidarios a las mazas para garantizar la transmisión de la tracción. En este ejemplo, el vehículo cuenta con tracción delantera, lo que significa que sus ruedas delanteras son, al mismo tiempo, motrices y directrices
    
        .row.justify-content-center.align-items-center.mb-5.bg-color-1.tarjeta
          .col-lg-8.py-4
            .titulo-sexto.color-acento-contenido
              h5 Figura 1.
              span Prospectiva como gestión del cambio y clave de innovación
        
            figure
              img(src="@/assets/curso/temas/tema1/4.png", data-aos="zoom-in", alt="Sistema diferencial con semiejes y apoyos estructurales.")
            figcaption.mt-2.text-center.mb-4 Not. ls1tech. (2004)
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Rodamientos para los ejes de propulsión delanteros
    
    p Cuando un vehículo tiene tracción delantera, los rodamientos de las mazas de las ruedas deben cumplir con ciertos requisitos para permitir el paso del eje de propulsión y garantizar una conexión sólida con la maza.

    p.mb-4 Las características principales de los rodamientos para tracción delantera son:
    
    .row.mb-5
      .col-lg-3(data-aos="fade-right")
        figure
          img(src="@/assets/curso/temas/tema1/5.png", data-aos="zoom-in")
      .col-lg-9(data-aos="fade-left")
        AcordionA.mb-5(tipo="a" clase-tarjeta="bg-color-2 tarjeta")
          div(titulo="Paso del eje de propulsión")
            p.mb-0 El rodamiento permite que el semieje atraviese su interior y se conecte con la maza de la rueda, asegurando que ambos giren solidariamente.
          div(titulo="Tipo de rodamiento")
            p.mb-0 Generalmente, se utilizan rodamientos de doble fila o doble pista de bolas, considerados como una sola unidad estructuralmente compacta.
          div(titulo="Fijación del semieje")
            p.mb-0 En el extremo del semieje, una rosca permite ajustarlo a la maza de la rueda, logrando que ambos giren en conjunto.
          div(titulo="Separador de pistas")
            p.mb-0 Los rodamientos incluyen un separador que mantiene la tolerancia adecuada, evitando que el ajuste del semieje afecte la libertad de giro del rodamiento.
    
    p.mb-4 Este diseño garantiza que el sistema de tracción funcione correctamente, permitiendo una rotación eficiente y reduciendo el desgaste en los componentes.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.py-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 2.
          span Esquema de un semieje y su rodamiento de bolas
    
        figure
          img(src="@/assets/curso/temas/tema1/6.png", data-aos="zoom-in", alt="Diagrama técnico que ilustra la conexión entre el semieje y el rodamiento.")
    
    p El sistema de rodamientos de doble bola, dependiendo del diseño y la carga que deben soportar, puede ser reemplazado por otros tipos de rodamientos que ofrezcan:
      
    .row.mb-5
      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-5
              figure
                img(src='@/assets/componentes/1.svg', alt='Texto que describa la imagen')

          p.text-center Mayor precisión en la transmisión del movimiento

      .col-sm-6.col-lg-4.mb-4.mb-lg-0
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-5
              figure
                img(src='@/assets/componentes/1.svg', alt='Texto que describa la imagen')

          p.text-center Mejor ajuste en el ensamblaje del sistema de tracción

      .col-sm-6.col-lg-4.mb-4.mb-sm-0
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.color-acento-contenido.text-white--hover.p-4
          .row.justify-content-center.mb-3
            .col-5
              figure
                img(src='@/assets/componentes/1.svg', alt='Texto que describa la imagen')

          p.text-center Mayor capacidad de carga, Adaptándose a diferentes Exigencias mecánica.

    div.text-center.bg-color.tarjeta.p-2.mb-5
      p.mb-0 Esta elección dependerá de las necesidades específicas del vehículo y del desempeño requerido en sus ruedas motrices.

    .row.justify-content-center.align-items-center.mb-5.bg-color-4.tarjeta.p-4
      .col-lg-6.py-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 3.
          span Rodamiento doble de bolas
        div.bg-color-5.tarjeta.p-4
          figure
          img(src="@/assets/curso/temas/tema1/7.png", data-aos="zoom-in", alt="Fotografía de un rodamiento de bolas con sus componentes identificados.")
        
      .col-lg-6.py-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 4.
          span Rodamiento de rodillos cónicos
        div.bg-color-5.tarjeta.p-4
          figure
            img(src="@/assets/curso/temas/tema1/8.png", data-aos="zoom-in", alt="Fotografía de un rodamiento cónico con detalles de su pista interna, externa y retenedor.")
            
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Semiejes delanteros
    
    p.mb-4 El sistema de suspensión emplea barras de torsión en lugar de los sistemas tradicionales de muelles, ballestas o el sistema MacPherson, que son los más utilizados en vehículos modernos.

    .bg_img
      .row.mb-5.justify-content-center
        .col-lg-5.mb-3.mb-lg-0
          p.mb-3 En algunos casos, se incorpora un sistema de soporte con rodamiento en el eje de mayor longitud, especialmente cuando la caja de cambios y el diferencial están más cerca de una de las ruedas. En este contexto, el semieje izquierdo es más corto, mientras que el semieje derecho, al ser más largo, requiere un soporte adicional entre el diferencial y la rueda más alejada para garantizar estabilidad y funcionamiento adecuado.
          figure
            img(src="@/assets/curso/temas/tema1/9.png", data-aos="zoom-in")
        .col-lg-5
          .titulo-sexto.color-acento-contenido
            h5 Figura 5.
            span Esquema de transmisión con semiejes y barra de torsión
          .row.justify-content-center.align-items-center.mb-5.bg-color-1.tarjeta
            .col-lg-12.py-4
              figure
                img(src="@/assets/curso/temas/tema1/10.png", data-aos="zoom-in", alt="Representación de un diferencial con semiejes corto y largo, además de una barra de torsión para estabilidad.")

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Puntas de ejes posteriores para tracción delantera

    p.m-4 En los vehículos con tracción delantera, las ruedas traseras, al no recibir propulsión, deben girar libremente sobre su punta de eje y los rodamientos que soportan la maza de las ruedas  

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-6.mb-3.mb-lg-0
        div.bg-color-6.tarjeta.p-5
          p.mb-0 Dado que las ruedas traseras no requieren curva, su soporte se logra insertando la punta de eje en los brazos de la suspensión. En este caso, la punta de eje suele contar con dos rodamientos cónicos, los cuales, con el ajuste adecuado de la tuerca y su seguro, mantienen la alineación precisa de los rodamientos. Esto permite que la maza gire sin juego y sobre su propio eje.
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 6.
          span  Sistema de frenos de tambor y sus componentes
        .row.justify-content-center.align-items-center.mb-5.bg-color-1.tarjeta
          .col-lg-12.py-4
            figure
              img(src="@/assets/curso/temas/tema1/11.png", data-aos="zoom-in", alt="Figura del freno de tambor con identificación de sus partes, incluyendo el cilindro y la zapata.")
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Puntas de eje delanteras sin tracción

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-6.mb-3.mb-lg-0
        div.bg-color-7.p-5.mb-3
          p.mb-0 Cuando un vehículo está diseñado con tracción trasera, las ruedas delanteras giran únicamente sobre su propio eje, cumpliendo la función de dirección. En este caso, las puntas de eje incorporan un sistema de doble rodamiento cónico, que, al ser ajustado dentro de la maza, permite su giro con la tolerancia exacta. Esta configuración evita holguras excesivas y garantiza un deslizamiento adecuado de los rodamientos durante su funcionamiento.
        .row.align-items-start
          .col-lg-auto.order-1.order-lg-2
            img(src="@/assets/curso/temas/tema1/13.svg", style="max-width: 90px").mx-auto
          .col-lg.order-2.order-lg-1
            p.mb-0 Estos rodamientos están alojados en la manzana de la rueda, la misma que debe alojar al disco o al tambor de freno, sus espárragos o pernos podrán sujetar a la rueda contra ella de forma fija.
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 7.
          span   Ensamble de freno de disco y sus elementos
        .row.justify-content-center.align-items-center.mb-5.bg-color-1.tarjeta
          .col-lg-12.py-4
            figure
              img(src="@/assets/curso/temas/tema1/12.png", data-aos="zoom-in", alt="Diagrama técnico con la mordaza de freno, la manzana de rueda y otros componentes separados.")

    .bg-full-width.bg-fondo-1
      .p-5
        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
            h3.titulo-con-imagen__texto Puntas de eje delanteras dentro de la suspensión
        p.mb-5 Las puntas de eje de las ruedas delanteras soportan la maza, los tambores o discos de freno y alojan las ruedas directrices del vehículo. En algunos casos, estas puntas de eje, representadas en color azul, están unidas a los amortiguadores delanteros, lo que permite que, al girar, dirijan las ruedas hacia la izquierda o la derecha según la necesidad de conducción.

        .row.justify-content-center.align-items-center
          .col-lg-5.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/temas/tema1/14.png", data-aos="zoom-in")
          .col-lg-5
            .titulo-sexto.color-acento-contenido
              h5 Figura 8.
              span Suspensión MacPherson delantera individual
            .row.justify-content-center.align-items-center.bg-color-1.tarjeta
              .col-lg-12.p-3
                figure
                  img(src="@/assets/curso/temas/tema1/15.png", data-aos="zoom-in", alt="Esquema de la suspensión MacPherson con sus principales elementos como muelles y amortiguadores.")

    .row.mb-5.justify-content-center
      .col-lg-10      
        p.mb-5(data-aos="fade-right") El brazo o mesa de suspensión proporciona soporte en la parte inferior del sistema y, a través de su rótula, permite el giro del conjunto. Mientras la suspensión trabaja en su movimiento vertical, también facilita la curvatura del vehículo.

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Diseños de las puntas de eje delanteras

    .row.mb-5.justify-content-center.align-items-center
      .col-lg-6.mb-3.mb-lg-0
        div.bg-color-8.p-5.mb-3
          img.mb-3(src="@/assets/curso/temas/tema1/16.svg", style="max-width: 100px")
          p.mb-0 Es fundamental considerar el procedimiento de montaje y ajuste de los rodamientos y la maza en la punta de eje delantera de un vehículo. Cuando la tracción recae en las ruedas traseras, las ruedas delanteras requieren un sistema que les permita girar libremente sobre su eje. Del mismo modo, en vehículos con tracción delantera, las ruedas traseras incorporan un sistema de punta de eje con rodamientos libres, ya que no reciben propulsión.
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 9.
          span   Ensamble de punta de eje con rodamiento cónico
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-12.py-4
            figure
              img(src="@/assets/curso/temas/tema1/17.png", data-aos="zoom-in", alt="Rodamiento doble de bolas con sus partes principales: bolas, separador y pistas de contacto para minimizar el desgaste.")
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Ajuste de las puntas de eje
    
    .bg-full-width.bg-fondo-2
      .p-5
        p.mb-5 El ajuste de los rodamientos cónicos debe seguir las recomendaciones del fabricante. Sin embargo, existe un procedimiento común para garantizar un montaje adecuado:
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-8.mb-3.mb-lg-0.order-2
        
                SlyderF(columnas="col-12 col-lg-6")
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema1/19.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Ajuste de la tuerca de castillo
                    p.text-center Usar un torquímetro para apretar la tuerca hasta 30 lb/pie o el valor recomendado por el fabricante del vehículo.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema1/20.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Asentamiento de piezas
                    p.text-center Girar la maza con el disco o tambor de freno para asegurar que las piezas ensambladas se asienten correctamente. Si hay cambios en la posición tras el giro, repetir el ajuste con el torque recomendado.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema1/21.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Aflojado de la tuerca
                    p.text-center Soltar la tuerca de castillo aproximadamente 30 grados y verificar que el pasador pueda insertarse en las ranuras correspondientes.
                  .bg-color-white.p-4.h-100.shadow-app
                    img(src='@/assets/curso/temas/tema1/20.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                    h4.text-center.mb-4 Asentamiento de piezas
                    p.text-center Doblar cuidadosamente las puntas del pasador, aplicar un poco de grasa extra e instalar la tapa protectora asegurando que quede bien ajustada.
              .col-lg-4.order-1
                figure
                  img(src='@/assets/curso/temas/tema1/18.png', alt='')

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Puntas de ejes posteriores
    
    p.mb-4 En vehículos con tracción trasera, los semiejes deben estar unidos a las mazas de las ruedas. Independientemente del sistema de frenos, ya sea de tambor y zapatas o de disco y mordaza, el semieje debe ajustarse con los torques recomendados por el fabricante.

    .bloque-texto-g.bloque-texto-g--inverso.bg-color-9.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/22.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En los vehículos modernos con tracción trasera o en las cuatro ruedas, se deben considerar los sensores de velocidad para los sistemas de frenos ABS y control de tracción. Un ajuste inadecuado de los semiejes o las mazas puede generar holgura en las ruedas fónicas o dentadas, afectando la señal del sensor de velocidad y comprometiendo la seguridad del vehículo y sus ocupantes

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Rodamientos utilizados
    
    .bg-full-width.bg-fondo-2
      .p-5
        .bg-full-width.bg-fondo-5
          .px-4.px-md-5.pb-md-3
            .row.justify-content-center.mb-5.align-items-center
              .col-lg-6.mb-3.mb-lg-0
                p Cada fabricante selecciona el tipo de rodamiento más adecuado para las puntas de eje de sus vehículos, considerando el diseño y la función de las ruedas, ya sea para tracción o giro libre.
                p Algunos fabricantes pueden optar por rodamientos de agujas o de palillos, aunque este diseño no suele ser el más apropiado debido a las cargas y esfuerzos a los que está sometida esta parte del vehículo. También se podría utilizar un rodamiento de rodillos cilíndricos, aunque este tipo suele reservarse para otras aplicaciones.
                .row.justify-content-center.align-items-center
                  .col-lg-10
                    figure
                      img(src='@/assets/curso/temas/tema1/23.png', alt='')
              .col-lg-5
                figure.mb-3
                  img(src='@/assets/curso/temas/tema1/24.png', alt='')
                .titulo-sexto.color-acento-contenido
                  h5 Figura 10.
                  span Sistema de freno trasero con tambor y sensor ABS
                .row.justify-content-center.align-items-center.mb-5
                  .col-lg-12.py-4
                    figure
                      img(src="@/assets/curso/temas/tema1/25.png", data-aos="zoom-in", alt="Rodamiento de rodillos cónicos, mostrando sus componentes como pistas interna y externa, retenedor y rodillos.")
    
    .row.align-items-center.bg-color-2.p-4.mb-5
      .col-lg-auto
        img(src="@/assets/componentes/1.svg", style="max-width: 90px").mx-auto
      .col-lg
        p.mb-0 Los rodamientos más comúnmente utilizados y adecuados para soportar el peso, las cargas laterales y garantizar un buen rodaje de las ruedas son los rodamientos de bolas y los rodamientos cónicos.
    
    .row.mb-5.justify-content-center
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 11.
          span Tipos de rodamientos según su estructura interna
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-12.py-4
            figure
              img(src="@/assets/curso/temas/tema1/26.png", data-aos="zoom-in", alt="Suspensión con diferencial, semiejes largos y cortos, además de barra de torsión para mejorar estabilidad.")
    
    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/2.svg")
        h3.titulo-con-imagen__texto Rodamientos más usuales

    p.mb-5 Existen varios tipos de rodamientos diseñados para trabajar con un eje, y cada fabricante selecciona el más adecuado según las características de las ruedas con tracción y las que giran libremente. El análisis de los esfuerzos que debe soportar cada componente es clave para elegir el rodamiento más apropiado, garantizando su correcto funcionamiento dentro del mecanismo en el que será instalado.

    .row.justify-content-center.align-items-center
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/temas/tema1/27.png", data-aos="zoom-in")
      .col-lg-7
        .titulo-sexto.color-acento-contenido
          h5 Figura 12.
          span Configuración de diferentes tipos de rodamientos
        .row.justify-content-center.align-items-center.bg-color-1.tarjeta
          .col-lg-8.p-3
            figure
              img(src="@/assets/curso/temas/tema1/28.png", data-aos="zoom-in", alt="Sistema de freno de tambor con zapatas, cilindro y mecanismo de ajuste para la frenada eficiente del vehículo.")
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
  }),
}
</script>

<style lang="sass"></style>
