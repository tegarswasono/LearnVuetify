<script setup lang="ts">
import { ref, onMounted } from "vue";
const drawer = ref<boolean>(false);
const links = [
            ['mdi-inbox-arrow-down', 'Inbox'],
            ['mdi-send', 'Send'],
            ['mdi-delete', 'Trash'],
            ['mdi-alert-octagon', 'Spam'],
          ];
const cards = ['Today', 'Yesterday'];
</script>
<template>
  <v-app>
    <v-system-bar>
      <v-icon @click="drawer = !drawer">mdi-menu</v-icon>
      <v-spacer />
      <v-icon>mdi-square</v-icon>
      <v-icon>mdi-circle</v-icon>
      <v-icon>mdi-triangle</v-icon>
    </v-system-bar>
    <v-navigation-drawer v-model="drawer" permanent>
      <v-sheet class="pa-4" color="grey-lighten-4">
        <v-avatar class="mb-4" color="grey-darken-1" size="64" />
        <div>John@google.com</div>
      </v-sheet>
      <v-divider />
      <v-list>
        <v-list-item v-for="[icon, text] in links" :key="icon" :prepend-icon="icon" :title="text" link />
      </v-list>
    </v-navigation-drawer>
    <v-main>
      <v-container class="py-8 px-6" fluid>
        <v-row>
          <v-col v-for="card in cards" :key="card" cols="12">
            <v-card>
              <v-list lines="two">
                <v-list-subheader :title="card" />
                <template v-for="n in 6" :key="n">
                  <v-list-item>
                    <template v-slot:prepend>
                      <v-avatar color="grey-darken-1" />
                    </template>
                    <v-list-item-title :title="`Message ${n}`" />
                    <v-list-item-subtitle title="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nihil repellendus distinctio similique" />
                  </v-list-item>
                  <v-divider
                    v-if="n !== 6"
                    :key="`divider-${n}`"
                    inset
                  ></v-divider>
                </template>
              </v-list>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
