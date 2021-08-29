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
            <NuxtLink class="text-[#94D1BD] text-xl text-bold" to="/">Home</NuxtLink>
            <NuxtLink class="text-[#94D1BD] text-xl text-bold" to="/">Friends</NuxtLink>
            <NuxtLink class="text-[#94D1BD] text-xl text-bold" to="/">Forum Subs</NuxtLink>
            <NuxtLink class="text-[#94D1BD] text-xl text-bold" to="/">Modding Watchlist</NuxtLink>
            <NuxtLink class="text-[#94D1BD] text-xl text-bold" to="/">Settings</NuxtLink>
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
              <section id="slideshow">
                <div class="w-full">
                  <div class="relative">
                    <button class="absolute top-40 left-0 mx-2">
                      <svg width="15" height="23" viewBox="0 0 15 23" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <g filter="url(#filter0_d)">
                        <path d="M2.36719 9.83594L9.94531 2.25781C10.1276 2.07552 10.349 1.98438 10.6094 1.98438C10.8698 1.98438 11.0911 2.07552 11.2734 2.25781L12.1328 3.11719C12.3151 3.29948 12.4062 3.52083 12.4062 3.78125C12.4323 4.04167 12.3542 4.26302 12.1719 4.44531L6.11719 10.5L12.1719 16.5547C12.3542 16.737 12.4323 16.9583 12.4062 17.2188C12.4062 17.4792 12.3151 17.7005 12.1328 17.8828L11.2734 18.7422C11.0911 18.9245 10.8698 19.0156 10.6094 19.0156C10.349 19.0156 10.1276 18.9245 9.94531 18.7422L2.36719 11.1641C2.15885 10.9818 2.05469 10.7604 2.05469 10.5C2.05469 10.2396 2.15885 10.0182 2.36719 9.83594Z" fill="white"/>
                        </g>
                        <defs>
                        <filter id="filter0_d" x="0.0546875" y="0.984375" width="14.3564" height="21.0312" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
                        <feFlood flood-opacity="0" result="BackgroundImageFix"/>
                        <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
                        <feOffset dy="1"/>
                        <feGaussianBlur stdDeviation="1"/>
                        <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/>
                        <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow"/>
                        <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow" result="shape"/>
                        </filter>
                        </defs>
                      </svg>
                    </button>
                    <button class="absolute top-40 right-0 mx-2">
                      <svg width="15" height="23" viewBox="0 0 15 23" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <g filter="url(#filter0_d)">
                        <path d="M12.1328 11.1641L4.55469 18.7422C4.3724 18.9245 4.15104 19.0156 3.89062 19.0156C3.63021 19.0156 3.40885 18.9245 3.22656 18.7422L2.36719 17.8828C2.1849 17.7005 2.08073 17.4792 2.05469 17.2188C2.05469 16.9583 2.14583 16.737 2.32812 16.5547L8.38281 10.5L2.32812 4.44531C2.14583 4.26302 2.05469 4.04167 2.05469 3.78125C2.08073 3.52083 2.1849 3.29948 2.36719 3.11719L3.22656 2.25781C3.40885 2.07552 3.63021 1.98438 3.89062 1.98438C4.15104 1.98438 4.3724 2.07552 4.55469 2.25781L12.1328 9.83594C12.3411 10.0182 12.4453 10.2396 12.4453 10.5C12.4453 10.7604 12.3411 10.9818 12.1328 11.1641Z" fill="white"/>
                        </g>
                        <defs>
                        <filter id="filter0_d" x="0.0546875" y="0.984375" width="14.3906" height="21.0312" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
                        <feFlood flood-opacity="0" result="BackgroundImageFix"/>
                        <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
                        <feOffset dy="1"/>
                        <feGaussianBlur stdDeviation="1"/>
                        <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/>
                        <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow"/>
                        <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow" result="shape"/>
                        </filter>
                        </defs>
                      </svg>
                    </button>
                    <img class="rounded-xl w-full" src="~/assets/miku.png">
                  </div>
                  <div class="flex justify-center mt-2 gap-2">
                      <button class="bg-[#66FFCC] w-12 h-2 rounded-full"></button>
                      <button class="bg-[#66FFCC80] w-12 h-2 rounded-full"></button>
                      <button class="bg-[#66FFCC80] w-12 h-2 rounded-full"></button>
                  </div>
                </div>
              </section>
              <section id="news">
                <div class="flex flex-col space-y-2">
                  <h1 class="text-xl text-white text-bold mb-2">News</h1>
                  <News />
                  <News />
                  <News />
                  <div id="card">

                  </div>
                </div>
              </section>
            </div>
          </div>
      </main>
    </div>
  </div>
</template>

<style>
body {
  font-family: 'Varela Round', sans-serif;
}
</style>