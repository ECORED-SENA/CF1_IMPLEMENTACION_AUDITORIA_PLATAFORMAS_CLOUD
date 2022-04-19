<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      h1  Síntesis


    .row.mb-5
      .col-lg-12.mb-5
        .row.mb-5
          .col-lg-5.d-none.d-lg-block(data-aos="fade-left") 
            img.mb-5.img-a.img_b(src='@/assets/curso/images/tema3/img_1.png', alt='Texto que describa la imagen')
        .row.align-items-center.fondo-14.p-3.tex-ali.mb-5
          .col-lg-12.mb-4.mb-lg-0.mb-5.d-none.d-lg-block 
            .row
              .col-lg-6(data-aos="fade-right")
                p.mb-4 La computación en la nube permite que los consumidores y las empresas gestionen archivos y utilicen aplicaciones sin necesidad de instalarlas, lo cual puede hacerse en cualquier computadora con acceso a internet.
                .cajon.color-custom.p-3.mb-0
                  p.mb-0 Además, es útil como modelo de negocio, puesto que el <i>software</i> reduce los costos mediante servidores centralizados en internet, en lugar de servidores locales, al eliminar gastos de mantenimiento, licencias y <i>hardware</i> necesario para mantener los servidores, permite que las empresas puedan ejecutar aplicaciones fluida y eficientemente.
           
      
      .row.align-items-center.fondo-14.p-5.d-block.d-lg-none.mb-5
        .col-lg-12.mb-4.mb-lg-0
          p.mb-4 La computación en la nube permite que los consumidores y las empresas gestionen archivos y utilicen aplicaciones sin necesidad de instalarlas, lo cual puede hacerse en cualquier computadora con acceso a internet.
          .cajon.color-custom.p-3.mb-0
            p.mb-0 Además, es útil como modelo de negocio, puesto que el <i>software</i> reduce los costos mediante servidores centralizados en internet, en lugar de servidores locales, al eliminar gastos de mantenimiento, licencias y <i>hardware</i> necesario para mantener los servidores, permite que las empresas puedan ejecutar aplicaciones fluida y eficientemente.

      .row.align-items-center.p-5.d-block.d-lg-none.mb-5
        .col-lg-12.mb-4.mb-lg-0
          img.mb-5.img-a(src='@/assets/curso/images/tema3/img_1.png', alt='Texto que describa la imagen')


    .row.align-items-center.fondo-29.mb-5
      .col-12.col-md-8.col-lg-3.col-xl-3(data-aos="fade-right")
        img(src="@/assets/curso/images/tema3/img_2.svg" alt="AvatarTop", style="width:370px; display:block; margin:-5rem 7rem;").mb-3
      .col-12.col-md-4.col-lg-9.col-xl-9.mb-3(data-aos="fade-left")
        p.aling-7.text-white.mb-3 La computación en la nube hace que sea posible que los usuarios accedan a aplicaciones en #[br] servidores centralizados que se basan en la infraestructura de la nube, pudiendo así #[br] las aplicaciones funcionar en la nube y facilitando su implementación sin costo alguno, #[br] manteniendo varias capas de <i>hardware</i> y <i>software</i>. El siguiente mapa ofrece una vista rápida #[br] de los contenidos de este componente formativo:

    .row.justify-content-center.align-items-center.d-block.d-lg-none.fondo-28.mb-5
      .col-12.col-md-8.col-lg-6.col-xl-5
        img.my-3(src="@/assets/curso/images/tema3/img_2.svg" alt="AvatarTop", style="width:370px; display:block; margin:-6rem -1rem;")
      .col-12.col-md-4.col-lg-6.col-xl-7
        p.text-white La computación en la nube hace que sea posible que los usuarios accedan a aplicaciones en servidores centralizados que se basan en la infraestructura de la nube, pudiendo así las aplicaciones funcionar en la nube y facilitando su implementación sin costo alguno, manteniendo varias capas de <i>hardware</i> y <i>software</i>.El siguiente mapa ofrece una vista rápida de los contenidos de este componente formativo:
    br
    br    
    p.my-3 El siguiente mapa ofrece una vista rápida de los contenidos de este componente formativo:

    .row.justify-content-center
      .col-lg-12.mb-4(data-aos="fade")
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
