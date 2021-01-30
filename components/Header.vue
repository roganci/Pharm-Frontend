<template>
  <nav class="bg-primary text-white flex items-center p-4">
    <h1>UWIPHARM</h1>

    <ul class="text-bold flex px-10">
      <li class="px-10">HOME</li>
      <li class="px-10">STORE</li>
      <li class="px-10">ABOUT</li>
    </ul>

    <form action="" class="pl-10 ml-5 w-3/4">
      <input
        type="text"
        class="rounded p-3 w-3/4"
        placeholder="Search for medicines in stock..."
      />
      <button class="border-2 p-3 rounded">GO</button>
    </form>

    <div class="flex justify-end w-1/4 px-10">
      <img src="~assets/profile.png" alt="" class="pr-10" />
      <img src="~assets/basket.png" alt="" class="pr-10" />
      <img src="~assets/favorites.png" alt="" class="pr-10" />
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style></style>
