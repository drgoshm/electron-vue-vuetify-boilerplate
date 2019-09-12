<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
        <span class="font-weight-light">MATERIAL DESIGN</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        text
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>fas fa-external-link-alt</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <LandingPage/>
    </v-content>
  </v-app>
</template>

<script>
import LandingPage from './components/LandingPage'

import {VApp, VContent, VAppBar, VBtn, VIcon, VSpacer, VToolbarTitle} from 'vuetify/lib'

export default {
  name: 'App',
  components: {
    LandingPage, VApp, VContent, VAppBar, VBtn, VIcon, VSpacer, VToolbarTitle
  },
  data: () => ({
    //
  })
}
</script>
