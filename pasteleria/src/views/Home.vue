<template>
  <div class="home">
    <Portada/>
    <Texto/>
    <Servicio                                                                 />
    <Galeria/>
  </div>
</template>

<script>
import Portada from '@/components/Portada.vue'
import Texto from '../components/Texto.vue'
import Servicio from '@/components/Servicio.vue'
import Galeria from '../components/Galeria.vue'

export default {
  name: 'home',
  components: {
    Portada,
    Texto,
    Servicio,
    Galeria
  }
}
</script>
