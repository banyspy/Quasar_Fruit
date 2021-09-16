<template>
    <q-page class="q-pa-lg">
        <p>Please try contact the vegetals or web provider if you have any problem!</p>
        <img
      alt="Quasar logo"
      src="~assets/vegetal.png"
      class="vegetal"
    >
    </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageIndex'
})
</script>

<style lang="scss">
  .vegetal{
    size:50%;
    z-index:1;
  }
</style>
