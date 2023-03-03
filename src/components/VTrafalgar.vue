<template>
  <div class="wrapper">
    <VHeader />
    <VirualHealthcare />
    <OurServices />
    <HealthcareProviders />
    <MobileApp />
  </div>
  <VFooter />
</template>

<script>
import VHeader from "@/components/VHeader.vue"
import VirualHealthcare from "@/components/VirtualHealthcare.vue"
import OurServices from "@/components/OurServices.vue"
import HealthcareProviders from "@/components/HealthcareProviders.vue"
import MobileApp from "@/components/MobileApp.vue"
import VFooter from "@/components/VFooter.vue"

export default {
  name: "VTrafalgar",
  props: {},

  components: {
    VHeader,
    VirualHealthcare,
    OurServices,
    HealthcareProviders,
    MobileApp,
    VFooter,
  },
};
</script>

<style scoped lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Mulish:wght@300;400;700&display=swap");

// min-width 1480px ??? TODO
.wrapper {
  width: 1200px;
}

// @media (min-width: 1600px) {
//  .wrapper {
//   width: 1200px;
//  }
// }

// @media (min-width:1280px) {
//   .wrapper {
//     width: 798px;
//   }
// }
</style>
