<template>
  <v-container>
    <v-row class="d-flex justify-center">
      <NuxtLink to="/" class="mr-5 grey--text text-decoration-none text-sm-caption">Home</NuxtLink>
      <NuxtLink to="/about" class="mr-5 grey--text text-decoration-none text-sm-caption">About</NuxtLink>
      <NuxtLink to="/works" class="mr-5 grey--text text-decoration-none text-sm-caption">Works</NuxtLink>
      <NuxtLink to="/contact" class="mr-5 grey--text text-decoration-none text-sm-caption">Contact</NuxtLink>
    </v-row>
    <v-row>
      <v-col class="d-flex justify-center">
        <v-btn icon href="https://github.com/akiyoshiyamamoto">
          <v-icon>mdi-github</v-icon>
        </v-btn>
        <v-btn icon href="https://twitter.com/">
          <v-icon>mdi-twitter</v-icon>
        </v-btn>
      </v-col>
    </v-row>
    <v-col class="text-center grey--text text-sm-caption">
      {{ new Date().getFullYear() }} - <strong>yaak</strong>
    </v-col>
  </v-container>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
</style>
