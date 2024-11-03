<script setup lang="ts">
import { ref, onMounted } from "vue";
const drawer = ref<boolean>(true);
</script>
<template>
  <v-responsive class="border rounded" max-height="300">
    <v-app>

      <v-app-bar>
        <v-app-bar-nav-icon @click="drawer=!drawer"></v-app-bar-nav-icon>
        <v-app-bar-title>App Bar</v-app-bar-title>
      </v-app-bar>

      <v-navigation-drawer permanent v-model="drawer">
        <v-list>
          <v-list-item title="Navigation drawer" />
        </v-list>
      </v-navigation-drawer>

      <v-main>
        <v-container>
          <h1>Main Container</h1>
        </v-container>
      </v-main>

    </v-app>
  </v-responsive>
</template>
