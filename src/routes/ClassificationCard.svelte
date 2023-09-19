<script>
  import DiCoffeescript from "svelte-icons/di/DiCoffeescript.svelte";
  import FaArrowUp from "svelte-icons/fa/FaArrowUp.svelte";
  export let coffeeClassification = "Mole";
</script>

<div class="bg-stone-50 w-64 flex flex-col pt-5 gap-4 rounded-md">
  <div
    class="relative icon w-20 bg-white self-center border-solid border-stone-200 border-2 rounded-full"
  >
    <div class="absolute w-5 z-10 right-2 top-4" style="color: #3FA152">
      <FaArrowUp />
    </div>
    <div class="relative" style="color: #444444">
      <DiCoffeescript />
    </div>
  </div>
  <div class="text-center text-2xl font-semibold place-content-center">
    {coffeeClassification}
  </div>
  <div
    class="bg-gray-300 font-bold h-12 flex-row flex justify-between text-center"
  >
    <button class="px-5 hover:bg-gray-500"> - </button>
    <div class="place-self-center">0</div>
    <button class="hover:bg-gray-500 px-5"> + </button>
  </div>
</div>
