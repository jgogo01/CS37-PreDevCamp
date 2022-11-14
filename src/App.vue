<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <navbar/>
  <router-view/>
  <footer/>
</template>

<script>
import navbar from "./components/structure/navbar.vue";
import footer from "./components/structure/footer.vue";
export default {
  components: {
    navbar,
    footer
  },
};
</script>

<style>
</style>
