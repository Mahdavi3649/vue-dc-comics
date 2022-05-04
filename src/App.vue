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

import SiteHeader from '@/components/HeaderComponent.vue'
import SiteMain from '@/components/MainComponent.vue'
import SiteOption from '@/components/OptionComponent.vue'
import SiteFooterTop from '@/components/FooterTComponent.vue'
import SiteFooterDown from '@/components/FooterDownComponent.vue'

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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container{
    width: 1000px;
    margin: auto;
}

.row{
  display: flex;
}

.col-2 {
  width: calc(100% / 12) * 2;
}

.col-4 {
  width: calc(100% / 12) * 4;
}

.col-8 {
  width: calc(100% / 12) * 8;
}

.col-6{
  width: calc(100% / 12) * 6;
}

.col-10{
  width: calc(100% / 12) * 10;
}
</style>
