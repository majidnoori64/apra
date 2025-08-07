<template>
  <div
    class="h-[682px] bg-no-repeat bg-cover bg-center"
    style="
      background-image: linear-gradient(
          179.71deg,
          rgba(0, 0, 0, 0.855) 1.85%,
          rgba(0, 0, 0, 0) 39.23%,
          rgba(0, 0, 0, 0.855) 102.5%
        ),
        url('img/header-bg.jpg');
    "
  >
    <div class="flex justify-between p-[16.5px]">
      <div class="flex">
        <NuxtImg width="140" src="/img/logo.png" />
        <SearchBox />
        <div class="w-[98px] h-[48px] flex items-center p-[8px] mr-[16px]">
          <img width="24" height="24" src="/img/icons8.png" alt="" />
          <p class="text-white text-[20px] font-bold pr-[8px]">کودک</p>
        </div>
      </div>
      <div>
        <button
          class="w-[314px] bg-[#1B6BE5] py-[12px] text-white rounded-[8px] font-[800] ml-[16px]"
        >
          پرداخت خودکار
        </button>
        <button
          class="w-[116px] bg-[#FF6633] py-[12px] text-white rounded-[16px] font-[800]"
        >
          پروفایل
        </button>
      </div>
    </div>
    <div class="flex justify-center mt-[254px]">
      <h1 class="w-[866px] text-[48px] text-white leading-[100px] text-center">
        "تو تصمیم می‌گیری چقدر پرداخت کنی!" دنیایی از فیلم‌های متنوع ایرانی و
        خارجی  آماده تماشا هستید؟
      </h1>
    </div>
  </div>
</template>

<script setup lang="ts">
</script>

<style>
</style>