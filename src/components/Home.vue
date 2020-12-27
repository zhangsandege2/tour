<template lang="pug">
div
  nav.navbar.header(id="home")
    .navbar-brand
      a.navbar-item.logo
        em Travel diary
      .navbar-burger(@click="handleMenu", :class="{'is-active': isActive}")
        span
        span
        span
    .navbar-menu(:class="{'is-active': isActive}")
      .navbar-end
        a.navbar-item(href="#home") Home
        a.navbar-item(href="#about") About
        a.navbar-item(href="#services") Services
        a.navbar-item(href="#events") Events
        a.navbar-item(href="#gallery") Gallery
        a.navbar-item(href="#testimonials") Testimonials
        a.navbar-item(href="#contact") Contact
  Carousel(v-model="value1" autoplay )
    CarouselItem
      img.img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/banner2.jpg")
    CarouselItem
      img.img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/banner3.jpg")
    CarouselItem
      img.img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/banner1.jpg")
</template>
<script>
export default {
  name: "tour-home",
  data() {
    return {
      value1: 0,
      isActive: false
    };
  },
  methods: {
    handleMenu() {
      this.isActive = !this.isActive;
    }
  }
};
</script>
<style lang="less" scoped>
.header {
  position: absolute;
  padding: 1rem;
  top: 0;
  width: 100%;
  background-color: rgba(0, 0, 0, 0);
  .logo {
    letter-spacing: 0.1rem;
    font-weight: 700;
    font-size: 1.2rem;
  }
}
.img {
  width: 100%;
  height: auto;
}
</style>
