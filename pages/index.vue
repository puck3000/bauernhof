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
