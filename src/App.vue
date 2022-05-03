<template>
  <div id="app">
     <SiteHeader />
     <SiteMain />
     <SiteOption />


  </div>
</template>


<script>
import SiteHeader from '@/components/HeaderComponent.vue'
import SiteMain from '@/components/MainComponent.vue'
import SiteOption from '@/components/OptionComponent.vue'

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
    SiteOption,
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
</style>
