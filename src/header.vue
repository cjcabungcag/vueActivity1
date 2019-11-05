<template>
  <div class="header">
    <router-link class="navBtn" to="/" tag="div">Home</router-link>
    <router-link class="navBtn" :to="'/about'" tag="div">About</router-link>
  </div>
</template>

<style scoped>
.header {
  background-color: var(--main-dark-bg-color);
  color: var(--txt-inverse-color);
  font-size: 20px;
  display: flex;
  height: 50px;
  margin-left: 40%;
  padding: 20px;
  margin-bottom: 20px;
}

.navBtn {
  margin: 15px;
}
.navBtn:hover {
  cursor: pointer;
}
</style>
<script>
export default {
  name: "header"
};
</script>