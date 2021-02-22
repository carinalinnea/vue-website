<template>
  <div>
    <navbar />
    <showcase />
    <stats />
    <cli />
    <cloud />
    <languages />
    <appFooter />
  </div>
</template>

<script>
import Navbar from './components/navigation/Navbar.vue'
import Footer from './components/navigation/Footer'
import Showcase from './components/Showcase.vue'
import Stats from './components/stats.vue'
import Cli from './components/cli.vue'
import Cloud from './components/cloud.vue'
import Languages from './components/languages.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    appFooter: Footer,
    Showcase,
    Stats,
    Cli,
    Cloud,
    Languages
    
  }
}
</script>

<style>
  
</style>
