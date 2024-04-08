<template>
  <Header></Header>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {Header},
  data() {
    return {
    }
  },
  methods: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
}

body {
  margin: 0;
  background-color: #f7f7f7;
}

</style>
