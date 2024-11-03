<script setup lang="ts">
import { ref, computed, watch, onMounted } from "vue";

const drawer = ref<boolean>(false);
</script>
<template>
  <v-app>
    <v-navigation-drawer v-model="drawer" :permanent="false">
      nav
    </v-navigation-drawer>
    <v-app-bar>
      <v-app-bar-nav-icon @click="drawer=!drawer"></v-app-bar-nav-icon>
      <v-app-bar-title>Application</v-app-bar-title>
    </v-app-bar>
    <v-main>
      main
    </v-main>
  </v-app>
</template>
