<template>
  <Header/>
  <About/>
  <Cards/>
  <Footer/>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Cards from './components/Cards.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    About,
    Cards,
    Footer,
  }
}
</script>

<style>

</style>
