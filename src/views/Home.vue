<template>
  <div class="home">
    <div class="home">
      <dev v-bind:name="'BHM ( Boarding House Management System )'"></dev>
      <div class="log">
        <dev v-bind:picture = "require('@/assets/logo2.png')"></dev>
      </div>
    </div>
  </div>
</template>

<script>
import dev from "@/components/developers";
export default {
  components:{
    dev
  }
};
</script>
<style scoped>
  .log{
    margin-top: 5%;
    float: right;
    margin-right: 35%;
  }
</style>