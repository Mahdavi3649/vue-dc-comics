<template>
  <footer class="down">
    <div class="container">
      <div class="row">
        <div class="col-2">
          <button>Sign up now</button>
        </div>

        <div class="col-10">
          <h3>follow us</h3>
          <img src="@/assets/img/footer-facebook.png" alt="" />
          <img src="@/assets/img/footer-twitter.png" alt="" />
          <img src="@/assets/img/footer-youtube.png" alt="" />
          <img src="@/assets/img/footer-pinterest.png" alt="" />
          <img src="@/assets/img/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterDownComponent",
};
</script>

<style lang="scss" scoped>
.down {
  background-color: $dc-light-dark;
  padding: 30px;
}

h3 {
  text-transform: uppercase;
  font-weight: 700;
  color: $dc-primary;
}
button {
  text-transform: uppercase;
  color: $dc-white;
  background-color: transparent;
  padding: 10px 20px;
  font-weight: 500;
  border: 2px solid $dc-primary;
}
.col-10 {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  column-gap: 15px;
}
</style>
