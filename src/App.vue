<script lang="ts">
import Navigation from "./components/Navigation.vue";
export default {
  name: "app",
  components: {
    "nav-menu": Navigation,
  },
};
</script>

<template>
  <div id="app">
    <nav-menu></nav-menu>
    <router-view></router-view>
  </div>
</template>

<style scoped></style>
