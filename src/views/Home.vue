<template>
  <div class="home">
    <header-shayna />
    <hero-carousel />
    <women-banner />
    <insta-shayna />
    <partner-shayna />
    <footer-shayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "../components/HeaderShayna.vue";
import HeroCarousel from "../components/HeroCarousel.vue";
import InstaShayna from "../components/InstaShayna.vue";
import PartnerShayna from "../components/PartnerShayna.vue";
import WomenBanner from "../components/WomenBanner.vue";
import FooterShayna from "../components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroCarousel,
    WomenBanner,
    InstaShayna,
    PartnerShayna,
    FooterShayna,
  },
};
</script>
