<template>
  <div class="bg-deep-orange-8 text-white">
    <q-toolbar class="z-top">
      <q-space />
      <q-btn flat icon="eva-github-outline" label="Github" />
      <q-btn flat icon="eva-linkedin-outline" label="LinkedIn" />
    </q-toolbar>
    <q-toolbar class="z-top">
      <q-toolbar-title>
        <p class="text-h4 q-ml-md">{{ myName }}</p>
      </q-toolbar-title>
    </q-toolbar>
  </div>
</template>

<script>
export default {
  name: "Toolbar",
  data () {
    return{
      myName: 'Adenilson Prado Raul'
    }
  }
};
</script>
