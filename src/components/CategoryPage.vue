<template>
  <div class="">
    <div class="w-10/12 mx-auto my-12">
      <h1
        class="text-3xl md:text-5xl text-center text-slate-700 font-semibold mb-6"
      >
        Browse Course by categories
      </h1>
      <p
        class="text-md text-slate-400 font-medium md:w-3/5 mx-auto text-center mb-6"
      >
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quae repellat
        deleniti molestiae? Neque, rem deleniti illo soluta, omnis assumenda
        facilis asperiores adipisci saepe tempore quia pariatur porro! Omnis,
        odit iure.
      </p>
      <div class="md:w-8/12 mx-auto">
        <swiper
          ref="{swiperRef}"
          :slidesPerView="1"
          :spaceBetween="5"
          :modules="modules"
          :breakpoints="{
            '390': {
              slidesPerView: 2,
              centeredSlides: true,
            },
            '768': {
              slidesPerView: 4,
              centeredSlides: false,
            },
            '1024': {
              slidesPerView: 5,
            },
          }"
          class="mySwiper"
        >
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa
                class="text-3xl text-indigo-500"
                :icon="['fas', 'flask-vial']"
              />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">Science</h1>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa
                class="text-3xl text-indigo-500"
                :icon="['fas', 'chart-column']"
              />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">
                Commerce
              </h1>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa
                class="text-3xl text-indigo-500"
                :icon="['fas', 'square-root-variable']"
              />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">
                Mathematics
              </h1>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa
                class="text-3xl text-indigo-500"
                :icon="['fas', 'earth-asia']"
              />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">
                Geography
              </h1>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa class="text-3xl text-indigo-500" :icon="['fas', 'book']" />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">English</h1>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa class="text-3xl text-indigo-500" :icon="['fas', 'mobile']" />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">Mobile</h1>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa class="text-3xl text-indigo-500" :icon="['fas', 'globe']" />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">Web Dev</h1>
            </div>
          </swiper-slide>
          <swiper-slide>
            <div
              class="bg-white shadow-lg rounded-lg w-[150px] h-[150px] flex flex-col text-center justify-center items-center border border-indigo-50"
            >
              <fa class="text-3xl text-indigo-500" :icon="['fas', 'server']" />
              <h1 class="text-lg font-semibold text-slate-500 mt-3">
                Networking
              </h1>
            </div>
          </swiper-slide>
        </swiper>
      </div>
    </div>
  </div>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";
import "swiper/css/navigation";
import { Pagination, Navigation } from "swiper";
export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination, Navigation],
    };
  },
};
</script>

<style>
</style>