<template>
  <div>
    <Header />
    <div id="app"></div>
  </div>
</template>

<script>
import Header from '@/components/header/Header.vue'

export default {
  name: 'About',
  components: {
    Header,
  },
  data() {
    return {
      visible: false,
    }
  },
}
</script>
