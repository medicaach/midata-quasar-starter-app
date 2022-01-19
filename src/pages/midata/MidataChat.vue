<template>
  <q-page>
   
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
