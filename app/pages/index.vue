<template>
  <div class="bg-[#000]">
    <AppMobile />
    <NewApra />
    <FeaturedMovies />
    <KidApra />
    <div class="pt-[90px] pb-[42px] flex justify-center">
      <NuxtImg width="155" src="/img/logo.png" />
    </div>
  </div>
</template>

<script lang="ts" setup>
import FeaturedMovies from "./[components]/FeaturedMovies.vue";
import AppMobile from "./[components]/AppMobile.vue";
import NewApra from "./[components]/NewApra.vue"
import KidApra from "./[components]/KidApra.vue"

</script>

<style>
</style>