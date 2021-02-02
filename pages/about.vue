<template>
  <div>
    <Header />
    <div id="app">
    
      <slideout dock="right" v-model="visible" title="The title">
        <p>The content</p>
      </slideout>

      <button @click="visible = true">Show</button>
  </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'

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
  methods: {
    onClosing(e) {
      // prevent close and wait
      e.wait = true
      // close after 3 seconds
      setTimeout(() => {
        // assign true to close, do nothing or assign false to cancel close.
        e.close = true
      }, 3000)
    },
  },
}
</script>
