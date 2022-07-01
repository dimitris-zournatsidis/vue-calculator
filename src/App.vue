<template>
  <div id="app">
    <calculator></calculator>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'App',
  components: {
    Calculator
    }
}
</script>

<style>
@import '~bootstrap/dist/css/bootstrap.css';

body {
  background: #31475e;
}
</style>
