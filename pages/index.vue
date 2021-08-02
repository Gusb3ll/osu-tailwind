<template>
  <div class="grid grid-cols-2 w-320">
    <div class="ml-14 -mr-8 my-8 flex flex-col space-y-4">
      <img class="rounded-xl" src="~/assets/miku.png">
      <!-- Placeholder -->
      <div class="mx-auto">
          <svg width="110" height="6" viewBox="0 0 110 6" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M0 3C0 1.34315 1.34315 0 3 0H27C28.6569 0 30 1.34315 30 3C30 4.65685 28.6569 6 27 6H3C1.34315 6 0 4.65685 0 3Z" fill="#66FFCC"/>
          <rect opacity="0.5" x="40" y="2" width="30" height="2" rx="1" fill="#66FFCC"/>
          <rect opacity="0.5" x="80" y="2" width="30" height="2" rx="1" fill="#66FFCC"/>
        </svg>
      </div>
      <!--             -->
      <div id="news" class="flex flex-col space-y-2">
        <h1 class="text-xl text-white text-bold mb-2">News</h1>
        <News />
        <News />
        <News />
      </div>
    </div>
  </div>
</template>
