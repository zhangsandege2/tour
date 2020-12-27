<template lang="pug">
section.hero.contact(id="contact")
  .hero-body
    .container
      .columns.is-centered
        .column.text-content
          h1.title Contact Us
          p is simply dummy text of the printing and typesetting industry.
      .columns.is-centered.is-multiline
        .column.is-3-desktop.is-4-tablet.is-12-mobiel
          input.input(type="text", placeholder="Your Name")
        .column.is-3-desktop.is-4-tablet.is-12-mobiel
          input.input(type="email", placeholder="Your Email")
        .column.is-3-desktop.is-4-tablet.is-12-mobiel
          input.input(type="text", placeholder="Your Phone Number")
        .column.is-9-desktop.is-12-tablet.is-12-mobiel
          textarea.textarea(placeholder="Your Message")
        .column.is-9-desktop.is-12-tablet.is-12-mobiel
          button.button(style="width: 100%;margin-bottom: 2rem;") sumbit
</template>
<script>
export default {
  name: "tour-contact"
};
</script>
<style lang="less" scoped>
.contact {
  background: url("https://images.pexels.com/photos/1928080/pexels-photo-1928080.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500")
    no-repeat;
  background-size: 100% auto;
  background-position: center;
  background-attachment: fixed;
  color: #ffffff;
  padding: 3rem;
  .text-content {
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
}
</style>
