<template>
  <div id="app">
    <Navbar />
    <Banner />
    <Products />
    <AboutNews />
    <Partners />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Banner from './components/Banner.vue'
import Products from './components/Products.vue'
import AboutNews from './components/AboutNews.vue'
import Partners from './components/Partners.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Navbar,
    Banner,
    Products,
    AboutNews,
    Partners,
    Contact,
    Footer
  }
}
</script>

<style>
</style>
