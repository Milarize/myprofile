<template>
  <v-container id="about" class="hero-section" fluid>
    <v-row align="center" justify="center" style="height: 100vh">
      <v-col cols="12" md="8" class="text-center">
        <v-avatar size="150" class="mb-4">
          <v-img src="@/assets/profile.jpg" alt="Profile"></v-img>
        </v-avatar>
        <h1 class="text-h2 font-weight-bold mb-4">Your Name</h1>
        <p class="text-h5">Full Stack Developer</p>
        <p class="text-body-1 mt-4">
          A passionate developer with experience in Vue.js, Node.js, and more.
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script> 