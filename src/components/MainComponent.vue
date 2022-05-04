<template>
  <main>
    <div class="jumbotron"></div>
    <seriesList />
  </main>
</template>

<script>
import seriesList from "@/components/SeriesListComponent.vue";
export default {
  name: "MainComponent",
  components: {
    seriesList,
  },
};
</script>

<style lang="scss" scoped>
main {
  background-color: $dc-dark;
  .jumbotron {
    background-image: url("@/assets/img/jumbotron.jpg");
    background-size: cover;
    height: 300px;
  }
}
</style>
