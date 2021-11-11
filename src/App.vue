<template>
  <div id="app">
    <siteHeader />
    <siteContent />
    <siteWidgets />
    <siteFooter />
  </div>
</template>

<script>
import siteHeader from "./components/siteHeader.vue";
import siteContent from "./components/siteContent.vue";
import siteFooter from "./components/siteFooter.vue";
import siteWidgets from "./components/siteWidgets.vue";

export default {
  name: "App",
  components: {
    siteHeader,
    siteContent,
    siteFooter,
    siteWidgets
  },
};
</script>

<style lang="scss">
  @import "./assets/scss/common.scss"
</style>


