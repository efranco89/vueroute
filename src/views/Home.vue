<template>
  <div class="home container">
    <HelloWorld msg="Bienvenido a tu app VueJS con rutas"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
