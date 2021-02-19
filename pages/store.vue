<template>
  <div>
    <Header />
    <main>
      <div class="m-10">
        <h2 class="text-gray-500">Store</h2>
        <br />
        <hr />

        <div>
          <Listing />
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import Header from '@/components/header/Header.vue'
import Listing from '@/components/store/Listing.vue'

export default {
  name: 'Store',
  components: {
    Header,
    Listing,
  },
}
</script>
