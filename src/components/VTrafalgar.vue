<template>
  <div class="">
    <VHeader />
    <VirualHealthcare />
    <OurServices />
    <HealthcareProviders />
    <MobileApp />
    <VFooter />
  </div>
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

<style scoped></style>
