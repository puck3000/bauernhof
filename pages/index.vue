<template>
  <section class="container">
    <wrapper></wrapper>
  </section>
</template>

<script>
import Wrapper from "~/components/Wrapper.vue";

export default {
  components: {
    Wrapper
  },

  mounted: function() {
    setTimeout(function() {
      // This hides the address bar:
      window.scrollTo(0, 1);
    }, 0);
  }
};
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
