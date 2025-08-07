<template>
  <div class="pb-[119px] w-max pr-[63px]">
    <p class="text-[24px] text-white mb-3">تازه های آپرا</p>
    <div class="flex items-center">
      <div
        class="h-[318px] w-[385px] absolute left-0"
        style="
          background: linear-gradient(
            270deg,
            rgba(0, 0, 0, 0) 0%,
            #000000 100%
          );
        "
      ></div>
      <button
        class=" rounded-[14px] absolute left-[47px] "
      >
        <NuxtImg width="42" src="/img/arrow-square-left.png" />
      </button>

      <div v-for="item in 8" :key="item" class="ml-[16px]">
        <NuxtImg width="385" src="/img/new-apra.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>