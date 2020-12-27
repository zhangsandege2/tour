<template lang="pug">
  div
    TourHome
    vue-lazy-component.custom-transition
      TourAbout
      TourAbout(slot="skeleton")
    vue-lazy-component.custom-transition
      TourService
      TourService(slot="skeleton")
    vue-lazy-component.custom-transition
      TourEvents
      TourEvents(slot="skeleton")
    vue-lazy-component.custom-transition
      TourGallery
      TourGallery(slot="skeleton")
    vue-lazy-component.custom-transition
      TourTestimonials
      TourTestimonials(slot="skeleton")
    vue-lazy-component.custom-transition
      TourContact
      TourContact(slot="skeleton")
    vue-lazy-component.custom-transition
      TourFooter
      TourFooter(slot="skeleton")
</template>
<script>
import TourHome from "../components/Home";
import TourAbout from "../components/About";
import TourService from "../components/Services";
import TourEvents from "../components/Events";
import TourGallery from "../components/Gallery";
import TourTestimonials from "../components/Testimonials";
import TourContact from "../components/Contact";
import TourFooter from "../components/Footer";
import { component as VueLazyComponent } from "@xunlei/vue-lazy-component";

export default {
  components: {
    TourHome,
    TourAbout,
    TourService,
    TourEvents,
    TourGallery,
    TourTestimonials,
    TourContact,
    TourFooter,
    "vue-lazy-component": VueLazyComponent
  }
};
</script>
<style>
.custom-transition .lazy-component-enter {
  opacity: 0;
  transform: translateY(100px);
}

.custom-transition .lazy-component-enter-to {
  opacity: 1;
  transform: translateY(0px);
}

.custom-transition .lazy-component-enter-active {
  transition: all 3s;
}
</style>
