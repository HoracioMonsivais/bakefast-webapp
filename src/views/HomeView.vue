<template>
  <nav class="nav">
    <Navigation/>
  </nav>
  <div class="home">
    <Header/>
  </div>
</template>

<script>
// @ is an alias to /src
import Navigation from '@/components/Navigation.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'HomeView',
  components: {
    Navigation,
    Header
  }
}
</script>

<style scoped>
template {
  height: 100vh;
}
</style>