<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade")
      .titulo-principal__numero
        span.text-dark 4
      h1 Monitoreo y evaluación
    p El monitoreo y la evaluación son una combinación de recopilación, análisis de datos y evaluación de hasta qué punto un plan y programa o ciclo han cumplido o no sus objetivos. El monitoreo y la evaluación se han utilizado para evaluar el desempeño del proyecto, programa e iniciativas sociales. 
    p.mb-5 Pueden fortalecer significativamente la planeación, el diseño, el seguimiento y la evaluación de un plan, programa o proyecto, sin embargo, existen muchos desafíos prácticos para implementar y optimizar la recopilación de datos de extremo a extremo para la generación de informes. Ayudan a las organizaciones a determinar si las actividades se están llevando a cabo cuándo y en qué medida.
    AcordionA.otroacordion(tipo="b" clase-tarjeta="tarjeta tarjeta--gris")
      .row.justify-content-center(titulo="Ejemplo")
        .col-md-11.mb-4.mb-md-0
          p Una empresa ofrece capacitación y cursos para sus colaboradores del área de servicio al cliente, por tanto, se podría hacer seguimiento mensual de la cantidad de PQRS que se reciben, la cantidad de cursos aprobados, el número de colaboradores capacitados.
      .row.justify-content-center(titulo="Monitoreo")
        .col-md-11.mb-4.mb-md-0
          p El monitoreo es periódico y continuo, realizado después del inicio del plan y durante la duración de ese plan o momento. Un monitoreo generalmente se enfoca en los procesos que ocurren durante la implementación de un plan. Estos pueden incluir el seguimiento de las siguientes actividades:
          ul.lista-ul--color
            li 
              i.fas.fa-folder-open
              | Cuándo se implementaron los planes.
            li 
              i.fas.fa-folder-open
              | Qué departamentos o equipos entregaron actividades.
            li 
              i.fas.fa-folder-open
              | Con qué frecuencia ocurrieron ciertas actividades.
            li 
              i.fas.fa-folder-open
              | Número de productos entregados u horas de servicio.
            li 
              i.fas.fa-folder-open
              | Costos de implementación del plan.   
    .row.my-5
      .col-xxl-2.col-xl-2.col-lg-3.col-md-3.col-sm-4.col-5.ps-md-1
        h4.ps-5.mb-1.fondo17.pb-1 Evaluación
    p La evaluación de los planes y programas se enfoca en el desempeño y se usa principalmente para determinar si los beneficiarios realmente se han beneficiado debido a esas actividades. Por lo general, analiza los resultados y evalúa si se produjo un cambio entre el inicio y la finalización de un periodo. Idealmente, ese cambio debería poder atribuirse a las actividades realizadas.
    p.mb-5 Al inicio de un plan y un programa, es importante adquirir datos de referencia, que se utilizarán para comparar el progreso en cada momento de evaluación y al final del período del plan y/o programa. Al pensar en cómo medir los resultados, considere lo siguiente:
    h1.text-center.mb-5 Evaluación
    .row.justify-content-around
      .col-xxl-2.col-xl-2.col-lg-2.col-4.col-sm-5.col-5
        img.nomuestre(src='@/assets/curso/tema4/cerebro.svg')
      .col-xxl-2.col-xl-2.col-lg-2.col-4.col-sm-5.col-5
        img.nomuestre(src='@/assets/curso/tema4/pc.svg')
      .col-xxl-2.col-xl-2.col-lg-2.col-4.col-sm-5.col-5
        img.nomuestre(src='@/assets/curso/tema4/engranaje.svg')
      .col-xxl-2.col-xl-2.col-lg-2.col-4.col-sm-5.col-5
        img.nomuestre(src='@/assets/curso/tema4/organigrama.svg')
      .col-xxl-2.col-xl-2.col-lg-2.col-4.col-sm-5.col-5
        img.nomuestre(src='@/assets/curso/tema4/blanco.svg')
    .row.justify-content-around
      .col-xxl-2.col-xl-2.col-lg-2.col-md-4.col-sm-5.col-5.fondo15.p-3.m-2
        p.text-center Comprenda cómo las actividades y acciones generan cambios.
      .col-xxl-2.col-xl-2.col-lg-2.col-md-4.col-sm-5.col-5.fondo15.p-3.m-2
        p.text-center Diseñe.
      .col-xxl-2.col-xl-2.col-lg-2.col-md-4.col-sm-5.col-5.fondo15.p-3.m-2
        p.text-center Use resultados que sean relevantes para sus colaboradores.
      .col-xxl-2.col-xl-2.col-lg-2.col-md-4.col-sm-5.col-5.fondo15.p-3.m-2
        p.text-center Incentive a los colaboradores para que le proporcionen datos importantes.
      .col-xxl-2.col-xl-2.col-lg-2.col-md-4.col-sm-5.col-5.fondo15.p-3.m-2
        p.text-center Asegúrese de tener herramientas adecuadas de gestión y análisis de datos y personal capacitado que tenga conocimiento de cómo usarlas.
    p.mt-5.text-bold Ventajas de implementar el seguimiento y la evaluación: 
    p.mb-5 Cuando se realiza de manera efectiva, la implementación del seguimiento y la evaluación genera ventajas para las partes interesadas en todas las actividades realizadas por una organización. En general, orienta la toma de decisiones estratégicas tanto durante como después de la ejecución de los planes.
    .row
      .col-lg-6
        .tarjeta-avatar-b.mb-5.nuevoalto
          .tarjeta-avatar-b__img
            img.imgsize3(src='@/assets/curso/tema4/avatar1.svg')
          .tarjeta.tarjeta--azul.fondo18
            .p-4
              h4 Los procesos de seguimiento (recopilación de datos): 
              p pueden significar que la organización realmente se preocupa por los resultados y la mejora continua.
              p Los datos se pueden utilizar para mejorar la eficiencia de la implementación, así como el diseño de la implementación.

      .col-lg-6
        .tarjeta-avatar-b.mb-5.nuevoalto
          .tarjeta-avatar-b__img
            img.imgsize3(src='@/assets/curso/tema4/avatar2.svg')
          .tarjeta.tarjeta--azul.fondo18
            .p-4
              h4 Colaboradores:
              p puede generar más aceptación y confianza en el compromiso de la organización con la misión si hay un esfuerzo claro, no solo para evaluar el progreso, sino también para usar esa evaluación para mejorar la generación de impacto. La realización de evaluaciones también puede generar más confianza entre los colaboradores y la organización.

      .col-lg-6
        .tarjeta-avatar-b.mb-5.nuevoalto
          .tarjeta-avatar-b__img
            img.imgsize3(src='@/assets/curso/tema4/avatar3.svg')
          .tarjeta.tarjeta--azul.fondo18
            .p-4
              h4 Gestión ejecutiva:
              p idealmente, la adaptación se vuelve más ágil.
              p Con datos relevantes y completos, los ejecutivos pueden construir argumentos mucho más persuasivos.

      .col-lg-6
        .tarjeta-avatar-b.mb-5.nuevoalto
          .tarjeta-avatar-b__img
            img.imgsize3(src='@/assets/curso/tema4/avatar4.svg')
          .tarjeta.tarjeta--azul.fondo18
            .p-4
              h4 Finanzas:
              p el dinero para el impacto fluye hacia donde están los datos, y una buena implementación de monitoreo y evaluación puede abrir ese flujo, porque genera credibilidad en el impacto y, por supuesto, una comprensión más transparente de cuánto impacto se puede generar por valor de inversión.
    p Cómo implementar monitoreo y evaluación en su organización:
    p.mb-5 La mayoría de las organizaciones comienzan con una estrategia de impacto. Dependiendo de sus antecedentes, diseñarán un enfoque orientado a los resultados.
 
</template>

<script>
import BannerInterno from '../components/BannerInterno.vue'
export default {
  name: 'Tema4',
  components: {
    BannerInterno,
  },
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
