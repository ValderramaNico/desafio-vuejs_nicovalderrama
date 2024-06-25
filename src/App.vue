<template>
  <CarnetElon msg="Carnet de Elon Musk" />
</template>

<script>
import CarnetElon from './components/CarnetElon.vue'

export default {
  name: 'App',
  components: {
    CarnetElon
  }
}
</script>

<style>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 60vh;
  font-size: 10px;
  font-family: sans-serif;
}
</style>
