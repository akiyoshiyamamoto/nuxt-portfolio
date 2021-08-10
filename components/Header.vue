<template>
  <v-container class="d-flex justify-start mb-6">
    <NuxtLink to="/" class="mr-5 grey--text">Home</NuxtLink>
    <NuxtLink to="/about" class="mr-5 grey--text">About</NuxtLink>
    <NuxtLink to="/works" class="mr-5 grey--text">Works</NuxtLink>
    <NuxtLink to="/contact" class="mr-5 grey--text">Contact</NuxtLink>
  </v-container>

</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
a {
  text-decoration: none;
  font-size: large;
}
</style>
