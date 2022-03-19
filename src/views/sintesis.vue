<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1  Síntesis
    
    .row.justify-content-center.align-items-center.fondo-14.p-3.mb-5
      .col-12.col-md-8.col-lg-6.col-xl-6
        p.mb-4 La computación en la nube permite que los consumidores y las empresas gestionen archivos y utilicen aplicaciones sin necesidad de instalarlas, lo cual puede hacerse en cualquier computadora con acceso a internet.
        .cajon.color-custom.p-3
          p.mb-0 Además, es útil como modelo de negocio, puesto que el <i>software</i> reduce los costos mediante servidores centralizados en internet, en lugar de servidores locales, al eliminar gastos de mantenimiento, licencias y <i>hardware</i> necesario para mantener los servidores, permite que las empresas puedan ejecutar aplicaciones fluida y eficientemente.
      .col-12.col-md-4.col-lg-6.col-xl-6
        img(src="@/assets/curso/images/tema3/img_1.png" alt='AvatarTop', style="width:500px; display:block; margin:-12px 1rem;")

    .row.align-items-center.mb-4.fondo-18.mb-5
      .col-12.col-md-8.col-lg-4.col-xl-4
        img(src="@/assets/curso/images/tema3/img_2.svg" alt="AvatarTop", style="width:320px; display:block; margin: -5rem -2rem;")
      .col-12.col-md-4.col-lg-7.col-xl-7.mb-3
        img(src="@/assets/curso/images/tema1/text.svg" alt="AvatarTop", style="width:600px; display:block; margin:-5rem 7rem;")
        p.text-white.aling-5 La computación en la nube hace que sea posible que los usuarios accedan a aplicaciones en servidores centralizados que se basan en la infraestructura de la nube, pudiendo así las aplicaciones funcionar en la nube y facilitando su implementación sin costo alguno, manteniendo varias capas de <i>hardware</i> y <i>software</i>. El siguiente mapa ofrece una vista rápida de los contenidos de este componente formativo:

    .row.justify-content-center.align-items-center.d-block.d-lg-none.fondo-28.mb-5
      .col-12.col-md-8.col-lg-6.col-xl-5
        img.my-3(src="@/assets/curso/images/tema3/img_2.svg" alt="AvatarTop", style="width:370px; display:block; margin:-6rem -1rem;")
      .col-12.col-md-4.col-lg-6.col-xl-7
        p.text-white La computación en la nube hace que sea posible que los usuarios accedan a aplicaciones en servidores centralizados que se basan en la infraestructura de la nube, pudiendo así las aplicaciones funcionar en la nube y facilitando su implementación sin costo alguno, manteniendo varias capas de <i>hardware</i> y <i>software</i>.El siguiente mapa ofrece una vista rápida de los contenidos de este componente formativo:
    br
        
    p.my-3 El siguiente mapa ofrece una vista rápida de los contenidos de este componente formativo:

    .row.justify-content-center
      .col-lg-12.mb-4
        img(src="@/assets/curso/images/tema3/img_3.svg" alt="AvatarTop")


</template>

<script>
export default {
  name: 'Sintesis',
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
