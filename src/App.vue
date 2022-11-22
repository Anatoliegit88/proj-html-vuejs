<script>
import AppHero from "./components/AppHero.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";
export default {
  components: {
    AppHero,
    AppMain,
    AppFooter,
  },
  data() {
    return {
      leftList: ["list"],
    };
  },
};
</script>

<template>
  <AppHero />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
@use "./style/general.scss" as *;
</style>
