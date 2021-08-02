<template>
  <div>
    <div class="flex flex-row h-12 rounded-xl bg-[#243342] transition-all transform hover:scale-105">
      <div class="my-auto ml-2">
        <svg width="4" height="16" viewBox="0 0 4 16" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="4" height="16" rx="2" fill="#EB47D0"/>
        </svg>
      </div>
      <div class="flex flex-row my-auto px-2">
        <h2 class="text-white text-sm">Gusbell</h2>
        <div class="flex flex-row ml-2 my-auto">
          <svg id="friend-stats" width="20" height="16" viewBox="0 0 20 16" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="20" height="16" rx="8" fill="black" fill-opacity="0.5"/>
            <path d="M7.75 7.625C8.82227 7.625 9.71875 6.74609 9.71875 5.65625C9.71875 4.58398 8.82227 3.6875 7.75 3.6875C6.66016 3.6875 5.78125 4.58398 5.78125 5.65625C5.78125 6.74609 6.66016 7.625 7.75 7.625ZM9.08594 8.1875H8.94531C8.57617 8.36328 8.17188 8.46875 7.75 8.46875C7.31055 8.46875 6.90625 8.36328 6.53711 8.1875H6.39648C5.27148 8.1875 4.375 9.10156 4.375 10.2266V10.7188C4.375 11.1934 4.74414 11.5625 5.21875 11.5625H10.2812C10.7383 11.5625 11.125 11.1934 11.125 10.7188V10.2266C11.125 9.10156 10.2109 8.1875 9.08594 8.1875ZM12.8125 7.625C13.7441 7.625 14.5 6.86914 14.5 5.9375C14.5 5.00586 13.7441 4.25 12.8125 4.25C11.8809 4.25 11.125 5.00586 11.125 5.9375C11.125 6.86914 11.8809 7.625 12.8125 7.625ZM13.6562 8.1875H13.5859C13.3398 8.27539 13.0762 8.32812 12.8125 8.32812C12.5312 8.32812 12.2676 8.27539 12.0215 8.1875H11.9688C11.5996 8.1875 11.2656 8.29297 10.9844 8.46875C11.4062 8.92578 11.6875 9.54102 11.6875 10.2266V10.8945C11.6875 10.9297 11.6699 10.9648 11.6699 11H14.7812C15.2383 11 15.625 10.6309 15.625 10.1562C15.625 9.08398 14.7285 8.1875 13.6562 8.1875Z" fill="#9FEB54"/>
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PlayerBrickMinimal',
}
</script>

<style>
* {
  font-family: 'Torus' ,'Varela Round' ,sans-serif;
}
</style>