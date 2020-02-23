<template>
  <q-page>
    <div class="fixed-center z-top">
      <p class="text-white text-center text-h4">Binary to decimal converter</p>
      <div class="form-main shadow-1">
        <div class="row q-pa-lg">
          <div class="col-12">
            <p class="text-center">Enter a number with binary base to be converted</p>
          </div>
          <q-input outlined v-model="bin" class="col-12">
            <template v-slot:append>
              <q-icon name="close" @click="bin = ''" />
            </template>
          </q-input>
          <p class="col-12 q-pt-lg text-subtitle1">Result: {{ bin }}</p>
          <q-btn size="lg" class="col-12 q-mt-sm" label="Calcular" color="deep-orange-8" />
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  name: "Home",

  data() {
    return {
      bin: ""
    };
  }
};
</script>

<style>
.form-main {
  width: 75vmin;
  background-color: white;
  margin: auto;
  border-radius: 0.5em;
}
</style>
