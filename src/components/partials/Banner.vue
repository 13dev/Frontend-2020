<template>
  <section class="hero is-dark is-large is-bold">
    <!-- Hero head: will stick at the top -->
    <div class="hero-head">
      <navbar></navbar>
    </div>

    <div class="hero-body">
      <div class="container has-text-left">
        <div class="columns is-vcentered">
          <div class="column is-three-fifths">
            <h1 class="title">
              Apple Watch
            </h1>
            <h2 class="subtitle">
              The best Smart Watch in the world.
            </h2>
          </div>
          <div class="column has-text-centered">
            <img
              src="@/assets/banner_image.webp"
              alt="Banner image"
              class="banner-img"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Navbar from "@/components/partials/Navbar";

export default {
  components: {
    Navbar
  },
  name: "Banner"
};
</script>

<style scoped>
.banner-img {
  max-width: 400px;
}
</style>
