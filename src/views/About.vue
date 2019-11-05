<template>
  <div class="about">
    <h1 class="team">The Team</h1>
    <div class="content-card" >
      <dev v-bind:picture = "require('@/assets/christian.png')" v-bind:name="'Christian Gigante'"  v-bind:description="'Project Manager'"></dev>
      <dev v-bind:picture = "require('@/assets/hannah.png')" v-bind:name="'Hannah Mae Peliño'" v-bind:description="'Front-end Developer'"></dev>
      <dev v-bind:picture = "require('@/assets/chilla.png')" v-bind:name="'Chilla Jean Cabungcag'" v-bind:description="'Back-end Developer'"></dev>
      <dev v-bind:picture = "require('@/assets/marion.png')" v-bind:name="'Marion Jay Balugo'" v-bind:description="'Back-end Developer'"></dev>
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
  .team{
    padding: 20px;
    color:burlywood;
    text-align: center;
  }
  .content-card{
    width: 50%;
    height: 30%;
    float: right;
    margin-right: 23%;

  }
</style>




