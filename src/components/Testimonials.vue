<template lang="pug">
section.hero.testimonials(id="testimonials")
  .hero-body
    .container
    .columns.is-centered
      .column.text-centent
        h1.title What Our Clients Say
        p is simply dummy text of the printing and typesetting industry.
    .columns.is-centered
      .column.is-3-desktop.text-message
        img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/test-img1.png")
        p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
      .column.is-3-desktop.text-message
        img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/test-img1.png")
        p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
      .column.is-3-desktop.text-message
        img(src="http://demo.kangjingept.com:8020/cssthemes6/zsy20201113-17/images/test-img1.png")
        p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
</template>
<script>
export default {
  name: "tour-testimonials"
};
</script>
<style lang="less" scoped>
.testimonials {
  background: url("https://images.pexels.com/photos/1961958/pexels-photo-1961958.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500")
    no-repeat;
  background-size: 100% auto;
  background-position: center;
  background-attachment: fixed;
  color: #ffffff;
  .text-centent {
    text-align: center;
    h1 {
      color: #ffffff;
      padding: 2rem;
    }
    p {
      font-size: 1.1rem;
      padding: 1rem;
    }
  }
  .text-message {
    text-align: center;
    padding: 4rem 1rem;
    background-color: rgba(0, 0, 0, 0.5);
    margin: 1rem;
    img {
      width: 7rem;
      height: 7rem;
      border-radius: 50%;
      overflow: hidden;
    }
    p {
      font-size: 1.1rem;
      margin-top: 1rem;
    }
  }
}
</style>
