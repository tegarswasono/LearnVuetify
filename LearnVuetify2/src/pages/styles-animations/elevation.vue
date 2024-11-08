<template>
  <v-row class="ma-4">
    <v-col cols="auto"><div style="width: 100px;height: 100px;" class="elevation-0 bg-secondary">elevation-0</div></v-col>
    <v-col cols="auto"><div style="width: 100px;height: 100px;" class="elevation-1 bg-secondary">elevation-1</div></v-col>
    <v-col cols="auto"><div style="width: 100px;height: 100px;" class="elevation-12 bg-secondary">elevation-12</div></v-col>
    <v-col cols="auto"><div style="width: 100px;height: 100px;" class="elevation-24 bg-secondary">elevation-24</div></v-col>
  </v-row>

  <v-divider />
  <div class="text-primary">
    <!-- Using the elevation prop -->
    <v-hover v-slot="{ isHovering, props }">
      <v-card
        v-bind="props"
        :elevation="isHovering ? 24 : 6"
        class="mx-auto pa-6"
      >
        Prop based elevation
      </v-card>
    </v-hover>

    <div class="my-6"></div>

    <!-- Using a dynamic class -->
    <v-hover v-slot="{ isHovering, props }">
      <div
        v-bind="props"
        :class="`elevation-${isHovering ? 24 : 6}`"
        class="mx-auto pa-6 transition-swing"
      >
        Class based elevation
      </div>
    </v-hover>
  </div>
</template>
