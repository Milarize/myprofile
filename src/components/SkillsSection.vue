<template>
  <v-container id="skills" class="py-16">
    <h2 class="text-h4 text-center mb-8">Skills</h2>
    <v-row>
      <v-col cols="12" md="4">
        <v-card>
          <v-card-title>Frontend</v-card-title>
          <v-card-text>
            <v-list>
              <v-list-item v-for="skill in frontendSkills" :key="skill">
                <v-list-item-title>{{ skill }}</v-list-item-title>
              </v-list-item>
            </v-list>
          </v-card-text>
        </v-card>
      </v-col>
      <!-- เพิ่ม Backend และ Tools ในลักษณะเดียวกัน -->
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'SkillsSection',
  data: () => ({
    frontendSkills: ['Vue.js', 'HTML', 'CSS', 'JavaScript']
  })
}
</script> 