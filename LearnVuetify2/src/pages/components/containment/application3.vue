<script setup lang="ts">
import { ref, onMounted } from "vue";

const theme = ref<string>("light");
  function onClick () {
    theme.value = theme.value === 'light' ? 'dark' : 'light'
  }
</script>
<template>
  <v-responsive class="border rounded" max-height="300">
    <v-app :theme="theme">
      <v-app-bar class="px-3">
        <v-spacer />
        <v-btn :prepend-icon="theme === 'light' ? 'mdi-weather-sunny':'mdi-weather-night'" text="Toggle Theme" slim @click="onClick" />
      </v-app-bar>
      <v-main>
        <v-container>
          <h1>Main Content</h1>
        </v-container>
      </v-main>
    </v-app>
  </v-responsive>
</template>
