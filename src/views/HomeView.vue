<script setup>
import DailyPuzzle from "../components/DailyPuzzle.vue";
</script>

<template>
  <main class="bg-[#c9d8d3]">
    <div class="container flex flex-col mx-auto px-6 py-10 items-center">
      <div class="flex flex-col items-center gap-6 md:flex-row ">
        <div class="flex flex-col items-center">
          <h1 class="text-3xl text-center font-bold text-gray-900">Play Chess Online With Your Friends!</h1>
          <button 
          class="mt-7 px-6 py-3 text-white font-bold text-lg bg-blue-900 hover:bg-blue-800 transition-colors rounded-lg drop-shadow-lg">
            Play Online
          </button>
        </div>
        <div class="flex flex-col w-full gap-1 sm:p-12 md:p-6">
          <h1 class="text-2xl text-left font-bold text-gray-900">
            Today's Puzzle
          </h1>

          <DailyPuzzle/>
        </div>
      </div>

      <div class="border-2 border-blue-600 mt-6 px-4 pb-2 rounded">
        <h2 class="mt-[-15px]  mb-3 bg-[#c9d8d3] w-fit px-2 font-bold">Quote of the Day</h2>
        <q class="font-serif">
          If you wish to succeed, you must brave the risk of failure.
        </q>
        <p class="text-center font-bold">Garry Kasparov</p>
      </div>

    </div>
  </main>
  <footer class="bg-gray-900 text-white flex justify-center items-center p-2">
     <p class="font-semibold drop-shadow-sm">Made By <a href="https://github.com/khaled5321" class="text-blue-400 hover:text-blue-600 transition-colors">Khaled Emad</a></p>
  </footer>
</template>

<style scoped>
.main-wrap{
  width:100%;
}

</style>