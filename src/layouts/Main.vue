<template>
  <q-layout>
    <q-header  class="transparent">
      <a-toolbar />
      <a-background />
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>

import aToolbar from "components/Toolbar.vue";
import aBackground from "components/Background.vue";

export default {
  name: "Main",
  data() {
    return {};
  },

  components: {
    aToolbar,
    aBackground
  }
};
</script>
