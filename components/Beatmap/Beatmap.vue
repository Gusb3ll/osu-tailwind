<template>
<div>
  <div class="flex flex-row h-full rounded-xl bg-[#394642] transition-all transform hover:scale-105">
    <div class="z-0 hidden md:block">
      <img class="rounded-lg h-26 object-cover" src="https://assets.ppy.sh/beatmaps/1514385/covers/list.jpg">
    </div>
    <div class="z-10 lg:-ml-3 w-full">
      <div class="flex flex-col justify-between h-full px-2 py-1 mr-2 rounded-lg bg-[#2f3a36] pr-30">
        <div class="text-white">
          <h1 id="title">Weaponized</h1>
          <h2 id="artist" class="text-[0.65rem]">Celldweller</h2>
          <h2 id="mapper" class="text-[0.65rem] mt-2 font-bold">by Cynplytholowazy</h2>
        </div>
        
        <div class="flex items-center justify-start">
          <div class="px-2 py-1 mt-6 rounded-xl bg-[#B2FF66]">
            <h1 class="font-bold text-[#394642] uppercase text-[0.55rem]">Ranked</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Beatmap',
}
</script>

<style>
.info-bg {
  background: url('~/assets/Info-box.png') no-repeat;
  background-size: cover;
}

.logo-bg {
  background: rgba(0, 0, 0, 0.5);
}
</style>