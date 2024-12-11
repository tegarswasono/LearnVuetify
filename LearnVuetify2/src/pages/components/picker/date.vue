<script setup lang="ts">
  import { ref } from "vue";
  const dateTest = ref<string | undefined>();
</script>
<template>
  date: {{ dateTest }} <br />
  date.toJSON : {{ dateTest != undefined ? new Date(dateTest).toJSON() : "" }}
  <v-container>
    <v-row justify="space-around">
      <v-date-picker v-model="dateTest" ></v-date-picker>
    </v-row>
  </v-container>
</template>
