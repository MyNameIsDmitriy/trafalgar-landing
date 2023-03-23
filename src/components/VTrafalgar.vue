<template>
  <div class="trafalgar">
    <VHeader />
    <VirtualHealthcare />
    <OurServices />
    <HealthcareProviders />
    <MobileApp />
    <VReviews />
    <OurArticle />
    <VFooter />
  </div>
</template>

<script>
import VHeader from "@/components/VHeader.vue";
import VirtualHealthcare from "@/components/VirtualHealthcare.vue";
import OurServices from "@/components/OurServices.vue";
import HealthcareProviders from "@/components/HealthcareProviders.vue";
import MobileApp from "@/components/MobileApp.vue";
import VReviews from "@/components/VReviews.vue";
import OurArticle from "@/components/OurArticle.vue";
import VFooter from "@/components/VFooter.vue";

export default {
  name: "VTrafalgar",
  props: {},

  components: {
    VHeader,
    VirtualHealthcare,
    OurServices,
    HealthcareProviders,
    MobileApp,
    VReviews,
    OurArticle,
    VFooter,
  },
};
</script>

<style scoped lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Mulish:wght@300;400;700&display=swap");

.trafalgar {
  width: 100%;
  margin: 0 auto;
}
</style>
