<template>
  <div class="app">
    <Head />
    <router-view/>
  </div>
</template>

<script>
import Head from "@/header.vue";

export default {
  name: "app",
  components: {
    Head
  }
};
</script>
<style scoped>
</style>