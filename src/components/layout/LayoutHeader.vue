<template>
  <v-app-bar app >
    <v-toolbar-title class="headline text-uppercase">
      <span><v-icon>mdi-wb_sunny</v-icon></span>
      <span class="font-weight-bold" color="light">CloudAlbum</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>

    <v-btn
      text
      href="https://github.com/vuetifyjs/vuetify/releases/latest"
      target="_blank"
    >
      <v-icon>mdi-face</v-icon>
      <span class="mr-2">Hello, Mario!</span>
    </v-btn>


    <v-btn
      text
      href="https://github.com/vuetifyjs/vuetify/releases/latest"
      target="_blank"
    >
      <v-icon>mdi-search</v-icon>
      <span class="mr-2">Search</span>
    </v-btn>


    <v-btn
      text
      href="https://github.com/vuetifyjs/vuetify/releases/latest"
      target="_blank"
    >
      <v-icon>mdi-location_on</v-icon>
      <span class="mr-2">Map</span>
    </v-btn>

    <v-btn
      text
      href="https://github.com/vuetifyjs/vuetify/releases/latest"
      target="_blank"
    >
      <v-icon>mdi-cloud_upload</v-icon>
      <span class="mr-2">Upload</span>
    </v-btn>

    <v-btn
      text
      href="https://github.com/vuetifyjs/vuetify/releases/latest"
      target="_blank"
    >
      <v-icon>mdi-open-in-new</v-icon>
      <span class="mr-2">Sign out</span>
    </v-btn>

  </v-app-bar>
</template>

<script>
	export default {
		name: "LayoutHeader"
	}
</script>

<style scoped>

</style>
