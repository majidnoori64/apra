<template>
  <div class="pb-[119px] w-max pr-[63px]">
    <p class="text-[24px] text-white mb-3">فیلم های برگذیده</p>
    <div class="flex">
      <div v-for="item in 8" :key="item" class="ml-[16px]">
        <NuxtImg width="200" src="/img/image 2.png" alt="" />
        <p class="text-white text[20px] mt-2">انگاشته</p>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
</script>

<style>
</style>