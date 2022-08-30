<template>
  <Header />
  <landingPage />
  <Footer />
  <router-view/>
</template>

<script>
import landingPage from './components/landingPage.vue'
import Header from './components/header.vue'
import Footer from './components/footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    landingPage,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Poppins', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
