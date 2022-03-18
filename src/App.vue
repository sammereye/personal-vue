<template>
  <div class="container mx-auto mt-24 lg:px-0 px-2">
    <Hero />
    <Main />
  </div>
  <Footer />
</template>

<script>
import Hero from './components/Hero/HeroIndex.vue';
import Main from './components/Main/MainIndex.vue';
import Footer from './components/Footer/FooterIndex.vue';
export default {
  name: 'App',
  components: {
    Hero,
    Main,
    Footer
  },
  methods: {
    
  }
}
</script>