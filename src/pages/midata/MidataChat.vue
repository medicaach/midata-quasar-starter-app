<template>
  <q-page>
    <div class="q-mb-xl">
      <div class="text-h3 text-weight-thin">Einführung in Trustie</div>
      <q-separator spaced class="midata-fade"></q-separator>
    </div>
    <matrix-component></matrix-component>
    <div class="q-my-xl text-grey">Quelle: https://trustie.medicaa.ch</div>
  </q-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'MidataChat',
});
</script>

<style lang="sass" scoped>
.img-800
  max-width: 800px
</style>
