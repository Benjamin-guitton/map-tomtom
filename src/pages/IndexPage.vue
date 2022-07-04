<template>
  <q-page class="flex-center">
    <TomTomMap city='Aubagne' apikey='hBGB8rd9Z05DLKUCaLmXbLOvQIblJEJ2'/>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import TomTomMap from 'components/TomTomMap.vue'

export default defineComponent({
  name: 'IndexPage',
  components: { TomTomMap }
})
</script>
