<template>
  <div>
    <div class="flex">
        
        <div class="categories min-h-screen w-1/5 border-r-2 flex justify-center">
            <h3 class="mt-10 text-2xl">Categories</h3>
        </div>

        <div class="products m-10 flex flex-wrap space-between max-w-4/5">
            
            <div class="card w-1/4 flex flex-col mb-10">
                <img src="~assets/med.png" alt="" class="pr-10" />
                <div class="p-info mt-10">
                    <h4 class="font-thin">Item</h4>
                    <br>
                    <p class="price text-xl">$50.00</p>
                </div>
            </div>

            <div class="card w-1/4 flex flex-col">
                <img src="~assets/med.png" alt="" class="pr-10" />
                <div class="p-info mt-10">
                    <h4 class="font-thin">Item</h4>
                    <br>
                    <p class="price text-xl">$50.00</p>
                </div>
            </div>


            <div class="card w-1/4 flex flex-col">
                <img src="~assets/med.png" alt="" class="pr-10" />
                <div class="p-info mt-10">
                    <h4 class="font-thin">Item</h4>
                    <br>
                    <p class="price text-xl">$50.00</p>
                </div>
            </div>

            <div class="card w-1/4 flex flex-col">
                <img src="~assets/med.png" alt="" class="pr-10" />
                <div class="p-info mt-10">
                    <h4 class="font-thin">Item</h4>
                    <br>
                    <p class="price text-xl">$50.00</p>
                </div>
            </div>

            <div class="card w-1/4 flex flex-col">
                <img src="~assets/med.png" alt="" class="pr-10" />
                <div class="p-info mt-10">
                    <h4 class="font-thin">Item</h4>
                    <br>
                    <p class="price text-xl">$50.00</p>
                </div>
            </div>

        </div>
    
    </div>  
  </div>
</template>

<script>
export default {
  name: 'Listing',
}
</script>
