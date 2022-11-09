<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p Bienvenidos al componente formativo Riesgo de desastres bajo el cual se describirán los contenidos a trabajar en el desarrollo del resultado de aprendizaje llamado
    p proponer alternativas para la formulación de la estrategia de respuesta a emergencias –ERE– según metodología en el marco de la competencia atender incidentes según protocolos y normativa. En un primer apartado se encontrará lo que refiere a las técnicas de manejo, evaluación y métodos de control del riesgo, en un segundo apartado se hará referencia al subsistema nacional de voluntarios de primera respuesta y se finalizará con la respuesta comunitaria a emergencias y desastres. Se invita a iniciar este recorrido observando el siguiente video de introducción.  
    
    figure
      img(src="@/assets/curso/portada/intro-img-decorativa-01.svg").intro-decorativa-01

    .row
      figure.mt-5
        .video
         iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
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
