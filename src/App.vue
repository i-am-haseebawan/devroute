<template>
  <TheHome></TheHome>
</template>

<script>
import TheHome from './components/TheHome.vue'
import './assets/tailwind.css'

export default {
  name: 'App',
  components: {
    TheHome,
}
}
</script>

<style>
#app {
  font-family: 'Kanit-SemiBold';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
  margin: 0;
}

</style>
