<template>
  <div class="flex items-center justify-center min-h-full flex-col">
    <h1 class="text-4xl">Cart</h1>
    <br />
    <p>Total items: <b>3</b></p>

    <div class="product flex my-5 w-10/12 p-5 shadow-lg h-screen/4">
      <img src="../../assets/med.png" alt="" class="pr-10" />

      <div class="text">
        <p class="text-red-600 text-right">X</p>
        <br />
        <p class="font-thin text-lg">Medicine 1</p>
        <br />
        <p class="font-bold">$50.00</p>
      </div>
    </div>

    <div class="product flex my-5 w-10/12 p-5 shadow-lg h-screen/4">
      <img src="../../assets/med.png" alt="" class="pr-10" />

      <div class="text">
        <p class="text-red-600 text-right">X</p>
        <br />
        <p class="font-thin text-lg">Medicine 1</p>
        <br />
        <p class="font-bold">$50.00</p>
      </div>
    </div>

    <div class="product flex my-5 w-10/12 p-5 shadow-lg h-screen/4">
      <img src="../../assets/med.png" alt="" class="pr-10" />

      <div class="text">
        <p class="text-red-600 text-right">X</p>
        <br />
        <p class="font-thin text-lg">Medicine 1</p>
        <br />
        <p class="font-bold">$50.00</p>
      </div>
    </div>

    <div class="product flex my-5 w-10/12 p-5 shadow-lg h-screen/4">
      <img src="../../assets/med.png" alt="" class="pr-10" />

      <div class="text">
        <p class="text-red-600 text-right">X</p>
        <br />
        <p class="font-thin text-lg">Medicine 1</p>
        <br />
        <p class="font-bold">$50.00</p>
      </div>
    </div>

    <div class="product flex my-5 w-10/12 p-5 shadow-lg h-screen/4">
      <img src="../../assets/med.png" alt="" class="pr-10" />

      <div class="text">
        <p class="text-red-600 text-right">X</p>
        <br />
        <p class="font-thin text-lg">Medicine 1</p>
        <br />
        <p class="font-bold">$50.00</p>
      </div>
    </div>

    <p>Total price: <b>$150</b></p>
    <br>

    <button
        id="submit"
        type="submit"
        class="button bg-primary p-4 w-3/4 text-white mb-10 text-lg"
      >
        Go to Checkout
      </button>

  </div>
</template>

<script>
export default {
  name: 'Cart',
}
</script>
