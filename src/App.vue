<script>
import AppHero from "./components/AppHero.vue";
import AppMain from "./components/AppMain.vue";
export default {
  components: {
    AppHero,
    AppMain,
  },
  data() {
    return {};
  },
};
</script>

<template>
  <AppHero />
  <AppMain />
</template>

<style lang="scss">
@use "./style/general.scss" as *;

// body {

// }
/* img {
  width: 100%;
} */
</style>
