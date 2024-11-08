<template>
  <v-row class="ma-4">
    <v-col cols="auto"><div class="bg-info rounded" style="width: 100px; height:100px;">rounded</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-sm" style="width: 100px; height:100px;">rounded-sm</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-0" style="width: 100px; height:100px;">rounded-0</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-xl" style="width: 100px; height:100px;">rounded-xl</div></v-col>
  </v-row>
  <v-row class="ma-4">
    <v-col cols="auto"><div class="bg-info rounded-pill text-center" style="width: 400px; height:100px;">rounded-pill</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-circle text-center" style="width: 400px; height:100px;">rounded-circle</div></v-col>
  </v-row>
  <v-row class="ma-4">
    <v-col cols="auto"><div class="bg-info rounded-t-lg" style="width: 100px; height:100px;">rounded-t-lg</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-e-lg" style="width: 100px; height:100px;">rounded-e-lg</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-b-lg" style="width: 100px; height:100px;">rounded-b-lg</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-s-lg" style="width: 100px; height:100px;">rounded-s-lg</div></v-col>
  </v-row>
  <v-row class="ma-4">
    <v-col cols="auto"><div class="bg-info rounded-ts-lg" style="width: 100px; height:100px;">rounded-ts-lg</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-te-lg" style="width: 100px; height:100px;">rounded-te-lg</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-be-lg" style="width: 100px; height:100px;">rounded-be-lg</div></v-col>
    <v-col cols="auto"><div class="bg-info rounded-bs-lg" style="width: 100px; height:100px;">rounded-bs-lg</div></v-col>
  </v-row>

  <v-divider />
  <v-row class="ma-4">
    <v-col cols="auto">
      <v-btn
      color="primary"
      rounded="0"
      text="Update Account"
      flat
      />
    </v-col>
    <v-col cols="auto">
      <v-btn
        color="primary"
        rounded="pill"
        text="Update Account"
        flat
      />
    </v-col>
  </v-row>

</template>
