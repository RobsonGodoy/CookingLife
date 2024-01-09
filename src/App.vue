<script lang="ts">
import Banner from "./components/Banner.vue";

export default {
  components: { Banner }
}
</script>

<template>
  <Banner />

  <h1 class="titulo">
    Texto do APP.vue
  </h1>
</template>

<style scoped>
.titulo {
  color: yellow
}
</style>