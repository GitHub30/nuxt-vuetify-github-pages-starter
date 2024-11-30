<script setup>
import { ref } from 'vue'

const drawer = ref(null)
</script>
<style>
html {
  /* https://stackoverflow.com/q/56973002 */
  overflow: visible;
}
</style>
<template>
  <NuxtLayout>
    <v-app>
      <v-app-bar>
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
        <v-app-bar-title>Application</v-app-bar-title>
      </v-app-bar>

      <v-navigation-drawer v-model="drawer">
        <v-list>
          <v-list-item title="Page 1" to="page1"></v-list-item>
          <v-list-item title="Page 2" to="page2"></v-list-item>
          <v-list-item title="Page 3" to="page3"></v-list-item>
        </v-list>
      </v-navigation-drawer>

      <v-main>
        <NuxtPage />
      </v-main>
    </v-app>
  </NuxtLayout>
</template>
