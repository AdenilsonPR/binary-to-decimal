<template>
  <div class="bg-orange text-white">
    <q-toolbar>
      <q-space />
      <q-btn flat icon="eva-github-outline" label="Github" />
      <q-btn flat icon="eva-linkedin-outline" label="LinkedIn" />
    </q-toolbar>
    <q-toolbar inset>
      <q-toolbar-title>
        <p class="text-h4">{{ myName }}</p>
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

<style>
</style>
