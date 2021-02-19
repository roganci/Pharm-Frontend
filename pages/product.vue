<template>
  <div>
    <Header />
    <div class="m-10 min-h-full min-w-screen min-h-screen">
      <h2 class="text-gray-500">
        Store | Category | <span class="text-black">Name of Product</span>
      </h2>
      <br />

      <div class="flex m-10">
        <img src="@/assets/med.png" alt="" class="product-img w-1/4" />

        <div
          class="product-info ml-40 w-3/4 text-gray-800 flex flex-col justify-between"
        >
          <h1 class="text-2xl">Medicine</h1>

          <p>
            <span class="text-xl">$50.00</span>
            <br />
            <br />
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vel
            nunc fermentum, convallis sem vitae, ornare lectus. Interdum et
            malesuada fames ac ante ipsum primis in faucibus. Nam convallis
            libero purus, vitae sollicitudin lorem consectetur vitae. Sed vel
            nibh id ipsum tempor aliquet. Nullam vel eros augue.
            <br />
            <br />
            Code: 0000
          </p>

          <div class="product-actions flex">
            <div class="w-1/2 flex items-center">
              Quantity:
              <div class="bg-secondary ml-5">
                <button class="p-5 border-2-transparent">-</button>
                <span class="p-5">1</span>
                <button class="p-5 border-2-transparent">+</button>
              </div>
            </div>
            <button class="button bg-primary p-4 text-white w-1/2">
              Add to Cart
            </button>
          </div>
        </div>
      </div>
    </div>

    <Footer />
  </div>
</template>

<script>
export default {
  name: 'Product',
}
</script>
