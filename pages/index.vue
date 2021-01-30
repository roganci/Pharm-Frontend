<template>
  <div>
    <Header />
    <main>
      <Hero />
    </main>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Hero from '@/components/index/Hero.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Index',
  components: {
    Header,
    Hero,
    Footer
  },
}
</script>
