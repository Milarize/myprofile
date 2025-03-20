<template>
  <v-container id="contact" class="py-16">
    <h2 class="text-h4 text-center mb-8">Contact</h2>
    <v-row justify="center">
      <v-col cols="12" md="6">
        <v-card>
          <v-card-text>
            <v-list>
              <v-list-item>
                <v-list-item-title>
                  <v-icon start>mdi-email</v-icon>
                  your.email@example.com
                </v-list-item-title>
              </v-list-item>
              <v-list-item>
                <v-list-item-title>
                  <v-icon start>mdi-github</v-icon>
                  GitHub
                </v-list-item-title>
              </v-list-item>
              <v-list-item>
                <v-list-item-title>
                  <v-icon start>mdi-linkedin</v-icon>
                  LinkedIn
                </v-list-item-title>
              </v-list-item>
            </v-list>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script> 