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
function customTheme () {
  theme.global.name.value = 'myCustomLightTheme';
  localStorage.setItem('theme', theme.global.name.value);
}
function lightTheme () {
  theme.global.name.value = 'light';
  localStorage.setItem('theme', theme.global.name.value);
}

//if you want to apply to all page, you have to use a single v-app
</script>

<template>
  <v-card title="title" text="text blablabla"  />
  <v-divider class="my-5" />

  <v-btn @click="toggleTheme">Toggle theme</v-btn>
  <v-btn @click="lightTheme">Light Theme</v-btn>
  <v-btn @click="customTheme">Custom Theme</v-btn>
  <v-divider class="my-5" />

  <v-btn text="primary" color="primary" />
  <v-btn text="secondary" color="secondary" />
  <v-btn text="error" color="error" />
  <v-btn text="info" color="info" />
  <v-btn text="success" color="success" />
  <v-btn text="warning" color="warning" />
</template>
