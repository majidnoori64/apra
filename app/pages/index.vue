<template>
  <div class="bg-black-1">
    <AppMobile />
    <NewApra />
    <FeaturedMovies />
    <KidApra />
    <div class="pt-[90px] pb-[42px] flex justify-center">
      <NuxtImg width="155" src="/img/logo.png" />
    </div>
  </div>
</template>

<script setup>
import FeaturedMovies from "./[components]/landing/FeaturedMovies.vue";
import AppMobile from "./[components]/landing/AppMobile.vue";
import NewApra from "./[components]/landing/NewApra.vue"
import KidApra from "./[components]/landing/KidApra.vue"

</script>

<style>
</style>