<template lang="pug">
  section.section(id="about")
    .container
      .columns.is-centered
        .column.centered
          h1.title About Us
          p.text-content is simply dummy text of the printing and typesetting industry.
      .columns.is-centered
        .column.flex-center.is-5-desktop.is-4-tablet.is-12-mobile
          img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/about-img.jpg")
        .column.flex-center.is-6-desktop.is-8-tablet.is-12-mobile
          h2.title We're The Best
          p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
          p is simply dummy text of the printing and typesetting industry. 
            | has been the industry's standard dummy text ever since the 1500s.
</template>
<script>
export default {
  name: "tour-about"
};
</script>
<style lang="less" scoped>
.centered {
  text-align: center;
  padding: 2rem;
  .text-content {
    font-size: 1.1rem;
    padding: 1rem;
  }
}
.flex-center {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  p {
    margin-bottom: 1rem;
    font-size: 1rem;
  }
}
</style>
