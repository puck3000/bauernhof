<template>
    <div id="wrapper">
        <visitenkarte></visitenkarte>
    </div>
</template>

<script>
import Visitenkarte from "~/components/Visitenkarte.vue";

export default {
  components: {
    Visitenkarte
  }
};
</script>

<style scoped>
#wrapper {
  background: #f4f5f8;
  padding: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

@media screen and (max-width: 768px) {
  #wrapper {
    height: 510px;
    width: 330px;
  }
}

@media screen and (min-width: 769px) {
  #wrapper {
    height: 330px;
    width: 510px;
  }
}
</style>