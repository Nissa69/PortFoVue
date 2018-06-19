<template>
  <div id="app">
    <Header />
    <TopSection />
    <Resume />
    <Veille />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import TopSection from './components/TopSection.vue'
import Resume from './components/Resume.vue'
import Veille from './components/Veille.vue'


export default {
  name: 'app',
  components: {
    Header,
    TopSection,
    Resume,
    Veille
  }
}
</script>

<style>
import BootstrapVue from 'bootstrap-vue'

#app {
      background-image: url(./assets/fond.jpg);
      background-repeat: no-repeat ;
      background-size:cover ;
      background-position: center;
      background-attachment:fixed ;
      font-family: Arial, Helvetica, sans-serif;
}

  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;


</style>
