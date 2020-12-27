<template lang="pug">
section.hero.events(id="events")
  .hero-body
    .container
      .columns.is-centered
        .column.title-center
          h1.title Our Events
          p is simply dummy text of the printing and typesetting industry.
      .columns.is-centered
        .column.is-3-desktop.background-black
          h2.title.is-4 March 24th
          p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s,
            | when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        .column.is-3-desktop.background-black
          h2.title.is-4 March 26th
          p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s,
            | when an unknown printer took a galley of type and scrambled it to make a type specimen book.
        .column.is-3-desktop.background-black
          h2.title.is-4 March 28th
          p is simply dummy text of the printing and typesetting industry. has been the industry's standard dummy text ever since the 1500s,
            | when an unknown printer took a galley of type and scrambled it to make a type specimen book.

</template>
<script>
export default {
  name: "tour-events"
};
</script>
<style lang="less" scoped>
.events {
  background: url("https://images.pexels.com/photos/6208418/pexels-photo-6208418.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500")
    no-repeat;
  background-size: 100% auto;
  background-position: center;
  background-attachment: fixed;
  padding: 2rem 1rem;
  color: #ffffff;
  .title-center {
    text-align: center;
    h1 {
      color: #ffffff;
    }
    p {
      font-size: 1.1rem;
      padding: 1rem;
    }
  }
  .background-black {
    background-color: rgba(0, 0, 0, 0.5);
    margin: 1rem;
    padding: 1rem;
    h2 {
      color: #ffffff;
      text-align: center;
    }
    p {
      font-size: 1.1rem;
    }
  }
}
</style>
