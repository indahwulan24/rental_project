<template>
  <NavbarPage />
  <HeroPage />
  <FooterPage />
</template>

<script>
import NavbarPage from "./NavbarPage.vue";
import HeroPage from "./HeroPage.vue";
import FooterPage from "./FooterPage.vue";
export default {
  name: "WelcomePage",
  components: {
    NavbarPage,
    HeroPage,
    FooterPage,
  },
};
</script>
