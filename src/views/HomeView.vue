<template>
  <Navbar/>
  <Intro/>
  <Portfolio/>
  <About/>
  <Hobies/>
  <Contact/>
  <Footer />
</template>

<script>
import About from '../components/About.vue'
import Footer from '../components/Footer.vue'
import Hobies from '../components/Hobies.vue'
import Intro from '../components/Intro.vue'
import Navbar from '../components/Navbar.vue'
import Portfolio from '../components/Portfolio.vue'
import Contact from '../components/Contact.vue'
export default {
  components: { Navbar, Intro, Portfolio, About, Hobies, Footer,Contact },

}
</script>

<style >

</style>