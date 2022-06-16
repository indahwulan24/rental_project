<template>
  <LoginPage />
</template>

<script>
import WelcomePage from "./components/WelcomePage/WelcomePage.vue";
// eslint-disable-next-line no-unused-vars
import LoginPage from "@/components/LoginPage/LoginPage";
export default {
  name: "App",
  components: {
    // eslint-disable-next-line vue/no-unused-components
    WelcomePage,
    LoginPage
  },
};
</script>

<style></style>
