<script setup lang="ts">
import { ref, onMounted } from 'vue';
import 'swiper/css';
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Pagination, Navigation } from 'swiper/modules';
import 'swiper/css/navigation';
import 'swiper/css/pagination';

import { customerInfo } from '@/assets/data/demo';
import customerBox from './elements/customer-box.vue';

const prevEl = ref(null);
const nextEl = ref(null);
</script>

<template>
  <div class="xl:max-w-9/12 mx-auto flex flex-col py-10 px-5">
    <div class="w-full flex flex-col justify-center items-center gap-10">
      <h2 class="text-4xl font-medium leading-normal text-center">
        Trusted by Thousands of <br />
        Happy Customer
      </h2>
      <p class="text-center text-[#4F5665] leading-normal">
        These are the stories of our customers who have joined us with great
        <br />
        pleasure when using this crazy feature.
      </p>
    </div>
    <div class="flex flex-col items-between">
        <!-- Swiper -->
    <swiper
      :modules="[Navigation, Pagination]"
      :navigation="{ prevEl: prevEl, nextEl: nextEl }"
      :loop="true"
      :spaceBetween="30"
      :breakpoints="{
        380: { slidesPerView: 1 },
        640: { slidesPerView: 2, spaceBetween: 20 },
        1024: { slidesPerView: 3, spaceBetween: 30 }
      }"
      class="mySwiper w-full h-[400px] sm:h-[350px] flex"
    >
      <swiper-slide
        v-for="(el, i) in customerInfo"
        :key="i"
        class="py-10 h-full flex"
      >
        <customerBox :imgSrc="el.img">
          <template #name>{{ el.name }}</template>
          <template #place>{{ el.city }}</template>
          <template #rating>{{ el.rating }}</template>
          <template #comment>{{ el.comment }}</template>
        </customerBox>
      </swiper-slide>
      
    </swiper>
    <!-- 🔘 Кастомные кнопки -->
    <div class=" justify-end gap-4 my-4 hidden md:flex">
      <button ref="prevEl" class="bg-red-500 size-15 rounded-full p-2  hover:bg-red-600">
        <span class="text-white text-3xl">←</span>
      </button>
      <button ref="nextEl" class="bg-red-500 p-2 size-15 rounded-full hover:bg-red-600">
        <span class="text-white text-3xl">→</span>
      </button>
    </div>
    
    </div>
    
  </div>
</template>