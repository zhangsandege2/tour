<template lang="pug">
section.hero.gallery(id="gallery")
  .hero-body
    .container
      .columns.is-centered
        .column.text-content
          h1.title Our Gallery
          p is simply dummy text of the printing and typesetting industry.
      .columns.is-centered.is-multiline
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img1.jpg")
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img2.jpg")
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img3.jpg")
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img4.jpg")
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img5.jpg")
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img6.jpg")
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img7.jpg")
        .column.is-3-desktop.flex-center.is-6-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/gallery-img8.jpg")
</template>
<script>
export default {
  name: "tour-gallery"
};
</script>
<style lang="less" scoped>
.gallery {
  padding: 2rem 1rem;
  .text-content {
    padding: 1rem;
    text-align: center;
    p {
      font-size: 1.1rem;
    }
  }
}
</style>
