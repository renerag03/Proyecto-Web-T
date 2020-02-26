<template>
  <div>
  <Eventos/>
  <Personalizadas/>
  <Normales/>
  </div>
</template>

<script>
import Eventos from '@/components/Eventos.vue'
import Personalizadas from '@/components/Personalizadas.vue'
import Normales from '@/components/Normales.vue'

export default {
    components: {
    Eventos,
    Personalizadas,
    Normales
  }

}
</script>

<style>

</style>