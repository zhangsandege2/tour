<template lang="pug">
section.hero.footer(id="footer")
  .hero-body
    .container
      .columns.is-centered
        .column.text-content
          h1.title THANKS FOR VISITING US
          Divider
      .columns.is-centered
        .column.text-message.is-4-desktop
          h2.title.is-4 Contact Information
          .font-icon
            font-awesome-icon(icon="air-freshener", size="2x")
          .font-icon
            font-awesome-icon(icon="american-sign-language-interpreting", size="2x")
          .font-icon
            font-awesome-icon(icon="archway", size="2x")
        .column.text-message.is-4-desktop
          h2.title.is-4 Newsletter
          p Register to our newsletter and be updated with the latests information regarding our services, offers and much more.
          button.max-width.button Email
          button.max-width.button Your Email
          button.max-width.button Sign in
        .column.text-message.is-4-desktop
          h2.title.is-4 Support Us
          p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
      Divider
      h1.title.is-6 Copyright © 2016.Company name All rights reserved.
</template>
<script>
export default {
  name: "tour-footer"
};
</script>
<style lang="less" scoped>
.footer {
  padding: 2rem;
  background-color: #2f3640;
  color: #ffffff;
  .text-content {
    text-align: center;
    h1 {
      color: #ffffff;
    }
  }
  .text-message {
    text-align: center;
    padding: 1rem;
    h2 {
      color: #ffffff;
    }
    .font-icon {
      margin-bottom: 0.5rem;
    }
    p {
      font-size: 1.1rem;
      padding: 0.5rem;
    }
    .max-width {
      width: 100%;
      margin-bottom: 0.5rem;
    }
  }
  h1 {
    color: #ffffff;
    text-align: center;
  }
}
</style>
