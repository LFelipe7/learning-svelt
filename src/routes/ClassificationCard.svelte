<script>
  import DiCoffeescript from "svelte-icons/di/DiCoffeescript.svelte";
</script>

<div class="bg-stone-50 w-64 flex flex-col pt-5 gap-4 rounded-md">
  <!-- <img src = {DiCoffeescript} alt='Coffee Icon' /> -->
  <!-- <div class="bg-[length:50px_50px] bg-red-300"> -->
  <div
    class="icon w-20 bg-white self-center rounded-full border-solid border-stone-200 border-2"
  >
    <DiCoffeescript />
  </div>
  <div class="text-center text-2xl font-semibold place-content-center">
    Mole
  </div>
  <div
    class="bg-gray-300 font-bold h-12 flex-row flex justify-between text-center"
  >
    <button class="px-5 hover:bg-gray-500"> - </button>
    <div class="place-self-center">0</div>
    <button class="hover:bg-gray-500 px-5"> + </button>
  </div>
</div>
