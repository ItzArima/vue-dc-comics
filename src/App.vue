// eslint-disable-next-line
<template>
  <div id="app">
    <siteHeader />
    <siteContent />
    <siteFooter />
  </div>
</template>

<script>
import siteHeader from "./components/siteHeader.vue";
import siteContent from "./components/siteContent.vue";
import siteFooter from "./components/siteFooter.vue";

export default {
  name: "App",
  components: {
    siteHeader,
    siteContent,
    siteFooter
  },
};
</script>

<style lang="scss">
#app {
  p {
    color: red;
  }
}
</style>


