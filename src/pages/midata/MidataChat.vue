<template>
  <q-page class="chat">

    <trustie-component></trustie-component>
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

.chat
  margin: -50px -100px


.screen--sm .chat
  margin: -81px -30px
  z-index: 100000
  position: fixed
  width: 100%
  height: 100%
</style>
