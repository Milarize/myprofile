<template>
  <v-container id="projects" class="py-16">
    <h2 class="text-h4 text-center mb-8">Projects</h2>
    <v-row>
      <v-col v-for="project in projects" :key="project.title" cols="12" md="6">
        <v-card>
          <v-img :src="project.image" height="200" cover></v-img>
          <v-card-title>{{ project.title }}</v-card-title>
          <v-card-text>
            <p>{{ project.description }}</p>
            <v-chip-group>
              <v-chip v-for="tech in project.technologies" :key="tech">
                {{ tech }}
              </v-chip>
            </v-chip-group>
          </v-card-text>
          <v-card-actions>
            <v-btn variant="outlined" :href="project.github" target="_blank">
              GitHub
            </v-btn>
            <v-btn variant="outlined" :href="project.demo" target="_blank">
              Live Demo
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'ProjectsSection',
  data: () => ({
    projects: [
      {
        title: 'Project 1',
        description: 'Description of project',
        technologies: ['Vue', 'Node.js'],
        image: '@/assets/project1.jpg',
        github: 'https://github.com/',
        demo: 'https://demo.com'
      }
    ]
  })
}
</script> 