<template>
  <div class="flex w-screen my-8">
    <div class="mx-auto">
      <nav>
        <div class="h-14 w-320 bg-[#1F2E29] flex flex-col">
          <div class="flex flex-row mx-16 my-auto">
            <h1 class="text-white text-2xl text-bold">Dashboard</h1>
            <h1 class="text-green-300 text-2xl pl-2">Home</h1>
          </div>
        </div>
        <div class="h-14 w-320 bg-[#293D36] flex flex-col">
          <div class="flex flex-row mx-16 my-auto space-x-8">
            <NuxtLink class="text-white text-xl text-bold" to="/">Home</NuxtLink>
            <NuxtLink class="text-white text-xl text-bold" to="/">Friends</NuxtLink>
            <NuxtLink class="text-white text-xl text-bold" to="/">Forum Subs</NuxtLink>
            <NuxtLink class="text-white text-xl text-bold" to="/">Modding Watchlist</NuxtLink>
            <NuxtLink class="text-white text-xl text-bold" to="/">Settings</NuxtLink>
          </div>
          <!-- Just for decoration -->
          <div class="-ml-3.5 -mb-0.5">
            <svg width="680" height="5" viewBox="0 0 515 5" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect x="43" width="5" height="43" rx="2.5" transform="rotate(90 43 0)" fill="#66FFCC"/>
                <rect y="2" width="680" height="1" fill="#66FFCC"/>
            </svg>
          </div>
        </div>
      </nav>
      <main class="h-full w-full bg-[#222A28]">
          <div class="grid grid-cols-2 w-320">
            <div class="ml-14 -mr-8 my-8 flex flex-col space-y-4">
              <div id="slideshow" class="w-full">
                <img class="rounded-xl w-full" src="~/assets/miku.png">
                <!-- Placeholder -->
                <div class="flex justify-center mt-2 gap-2">
                    <button class="bg-[#66FFCC] w-12 h-2 rounded-full"></button>
                    <button class="bg-[#66FFCC80] w-12 h-2 rounded-full"></button>
                    <button class="bg-[#66FFCC80] w-12 h-2 rounded-full"></button>
                </div>
                <!--             -->
              </div>
              <div id="news" class="flex flex-col space-y-2">
                <h1 class="text-xl text-white text-bold mb-2">News</h1>
                <News />
                <News />
                <News />
              </div>
            </div>
  </div>
      </main>
    </div>
  </div>
</template>
