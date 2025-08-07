<template>
  <div  class="flex bg-gray-1" style="box-shadow: 0px -8px 38px 0px #ffffff40">
    <div v-for="item in items" :key="item.id" class=" h-[360px] p-[24px] w-100 odd:bg-gray-1 even:bg-gray-2 border border-gray-3 border-solid">
      <div class="w-[50px] h-[48px] p-2 bg-black-1 rounded-[12px] mb-[12px]">
        <NuxtImg width="38" :src="`img/${item.icon}`" />
      </div>
      <p class="text-white font-[700] text-[24px] leading-[40px] mb-2">
        {{item.title}}
      </p>
      <p class="text-white text-[18px] leading-8">{{item.text}}</p>
    </div>
  </div>
</template >

<script setup lang="ts" >
const items = ref([
  {
    id: 1,
    title:'پشتیبانی از تمامی دستگاه‌ها',
    text: "سازگاری با انواع دستگاه‌ها از جمله تلفن‌های هوشمند، تبلت‌ها، رایانه‌ها و تلویزیون امکان تماشای محتوا را در هر زمان و مکانی فراهم می‌کند.",
    icon: "monitor-mobbile.png",
  },
  {
    id: 2,
    title: 'صرفه جویی در هزینه',
    text: 'بجای هزینه‌ی ماهانه برای کل محتوا، در آپرا میتوانید فقط برای  فیلمی که دوست دارید هزینه پرداخت کنید.',
    icon: 'dollar-circle.png',
  },
  {
    id: 3,
    title: 'محتوای متنوع و کامل',
    text: ' کامل ترین مجموعه فیلم و سریال های ایرانی و خارجی، دسترسی به محتوای متنوع  و  تجربه ای جدید در تماشای آنلاین',
    icon: 'film.png',
  },
  {
    id: 4,
    title: 'کیفیت پخش بالا',
    text: 'پلتفرم آپرا با ارائه کیفیت‌های متنوع پخش، به کاربران امکان می‌دهد تا بر اساس سرعت اینترنت خود، بهترین کیفیت را انتخاب کنند.',
    icon: 'material-outline.png',
  }
]);
</script>

<style>
</style>