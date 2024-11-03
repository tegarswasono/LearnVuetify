<script setup lang="ts">
import { ref } from "vue";
import { useTheme } from "vuetify";

const themes = ["light", "dark", "themeCustom1", "themeCustom2"];
const theme = useTheme();

const savedTheme = localStorage.getItem('theme');
if (savedTheme) {
  theme.global.name.value = savedTheme;
}

function toggleTheme () {
  theme.global.name.value = theme.global.current.value.dark ? 'light' : 'dark';
  localStorage.setItem('theme', theme.global.name.value);
}

//if you want to apply to all page, you have to use a single v-app
</script>

<template>
  <v-card title="title" text="text blablabla"  />
  <v-divider />
  <v-btn @click="toggleTheme">Toggle theme</v-btn>
</template>
