<template>
  <div>
    <Beatmap />
    <p class="mt-2 text-center">I don't have Torus font pls donate</p>
    <NuxtLink to="/"><p class="mt-2 text-center">Home</p></NuxtLink>
  </div>
</template>

<script>
import Beatmap from "~/components/Beatmap.vue";

export default {
  components: {
    Beatmap,
  },
};
</script>
