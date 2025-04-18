<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <v-toolbar>
    <v-btn icon="mdi-menu"></v-btn>
    <v-toolbar-title>
      <RouterLink to="/">Vuetify</RouterLink>
    </v-toolbar-title>

      <v-btn to="/login" variant="outlined" color="pink-darken-4" size="default" text="Login"></v-btn>
  </v-toolbar>
</template>