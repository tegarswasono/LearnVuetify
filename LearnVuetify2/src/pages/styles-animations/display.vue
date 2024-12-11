<script setup lang="ts">
  import { useDisplay } from 'vuetify';
  const { xs, sm, md, lg } = useDisplay();
</script>
<template>
  <div>
    <div class="d-inline pa-2 bg-deep-purple">d-inline</div>
    <div class="d-inline pa-2 bg-black">d-inline</div>
  </div>

  <v-divider class="my-5" />
  <div>
    <div class="d-block pa-2 bg-deep-purple">d-block</div>
    <div class="d-block pa-2 bg-black">d-block</div>
  </div>

  <v-divider class="my-5" />
  <v-btn class="ma-2" color="success" v-if="sm">Button 1</v-btn>
  <v-btn class="ma-2" color="warning">Button 2</v-btn>

  <v-divider class="my-5" />
  <v-row>
    <v-col cols="12" sm="6" class="bg-error"></v-col>
    <v-col cols="12" sm="6" class="bg-warning"></v-col>
  </v-row>
</template>
