<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />
    <SiteOption />
    <SiteFooterTop />
    <SiteFooterDown />
  </div>
</template>

<script>
import SiteHeader from "@/components/HeaderComponent.vue";
import SiteMain from "@/components/MainComponent.vue";
import SiteOption from "@/components/OptionComponent.vue";
import SiteFooterTop from "@/components/FooterTComponent.vue";
import SiteFooterDown from "@/components/FooterDownComponent.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
    SiteOption,
    SiteFooterTop,
    SiteFooterDown,
  },
};
</script>

<style lang="scss">
@import "~@/assets/scss/style.scss";
</style>
