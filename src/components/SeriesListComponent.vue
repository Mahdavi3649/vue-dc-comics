<template>
  <div class="col-2s">
    <div class="serie">
      <img :src="item.thumb" />
      <h5 class="text-left">{{ item.series }}</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: "SeriesListComponent",

  props: {
    item: Object,
  },
};
</script>

<style lang="scss" scoped>
img {
  max-width: 100%;
  object-fit: cover;
  aspect-ratio: 1/1;
  object-position: top;
}
.col-2s {
  width: calc((100% / 6) - 0.5rem);
  padding: 10px 7px;
}
.text-left {
  text-align: left;
  color: $dc-light-gray;
  margin: 0.5rem 0;
}
</style>
