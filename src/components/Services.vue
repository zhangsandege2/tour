<template lang="pug">
section.hero.services(id="services")
  .hero-body
    .container
      .columns
        .column.text-center
            h1.title(style="color: #ffffff;") Our Services
            p is simply dummy text of the printing and typesetting industry.
      .columns.is-centered.mar-bottom
        .column.flex-center.is-5-desktop.is-6-tablet.is-12-mobile
          h1.title(style="color: #ffffff;") First Class Design
          p.text-content-p It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing passages, and more recently with desktop publishing software like Aldus PageMaker including versions of .
          h2.title.is-4(style="color: #ffffff;") Retina Ready Theme
          h2.title.is-4(style="color: #ffffff;") Awesome Support
          h2.title.is-4(style="color: #ffffff;") Responsive Design
        .column.flex-center.is-4-desktop.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/service-img.jpg")
</template>
<script>
export default {
  name: "tour-services"
};
</script>
<style lang="less" scoped>
.services {
  background: url("https://images.pexels.com/photos/4628208/pexels-photo-4628208.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940")
    no-repeat;
  background-size: 100% auto;
  background-position: center;
  background-attachment: fixed;
  background-color: rgba(0, 0, 0, 0.2);
  color: #ffffff;
  padding: 2rem 1rem;
  .text-center {
    text-align: center;
    h1 {
      padding: 1rem;
    }
    p {
      padding-bottom: 1rem;
      font-size: 1.1rem;
    }
  }
  .text-content-p {
    font-size: 1.1rem;
    padding: 0 0 1rem 0;
  }
  .text-left {
    h1 {
      padding: 1rem 1rem 1rem 0;
    }
    p {
      padding-bottom: 1rem;
      font-size: 1.1rem;
    }
  }
}
</style>
