<script setup>
import { defineOptions } from 'vue'
defineOptions({
  name: 'HeaderSection'
})
</script>

<template>
  <v-app-bar app elevation="4">
    <v-container class="d-flex align-center">
      <v-app-bar-title>Your Name</v-app-bar-title>
      <v-spacer></v-spacer>
      <v-btn variant="text" href="#about">About</v-btn>
      <v-btn variant="text" href="#skills">Skills</v-btn>
      <v-btn variant="text" href="#projects">Projects</v-btn>
      <v-btn variant="text" href="#contact">Contact</v-btn>
    </v-container>
  </v-app-bar>
</template> 