<script>
import HeaderSection from './components/HeaderSection.vue'
import HeroSection from './components/HeroSection.vue'
import SkillsSection from './components/SkillsSection.vue'
import ProjectsSection from './components/ProjectsSection.vue'
import ContactSection from './components/ContactSection.vue'

export default {
  name: 'App',
  components: {
    HeaderSection,
    HeroSection,
    SkillsSection,
    ProjectsSection,
    ContactSection
  }
}
</script>

<template>
  <v-app>
    <HeaderSection />
    <v-main>
      <HeroSection />
      <SkillsSection />
      <ProjectsSection />
      <ContactSection />
    </v-main>
  </v-app>
</template>