<template>
  <div class="my-20">
    <div class="w-10/12 mx-auto">
      <h1
        class="text-3xl md:text-5xl text-slate-700 font-semibold mb-6 text-center scroll-left"
      >
        What our Students say
      </h1>
      <div class="mx-auto mt-24">
        <!-- start swiperjs -->
        <swiper
          :effect="'coverflow'"
          :grabCursor="true"
          :centeredSlides="true"
          :navigation="true"
          :slidesPerView="'auto'"
          :coverflowEffect="{
            rotate: 50,
            stretch: 0,
            depth: 100,
            modifier: 1,
            slideShadows: true,
          }"
          :modules="modules"
          class="mySwiper"
        >
          <swiper-slide class="w-[280px] scroll-bottom"
            ><img class="w-[200px] mx-auto" src="../assets/NawPhaw.jpeg" />
            <h1 class="text-2xl text-slate-700 font-semibold mt-12 text-center">
              Naw Phaw
            </h1>
            <h1 class="text-1xl text-slate-400 font-semibold text-center">
              CEO, Technology Reaction
            </h1>
            <h1
              class="text-1xl text-slate-600 font-semibold text-center mt-6 mx-auto"
            >
              "I love This | couldn't do my job with it Lorem ipsum dolor sit
              amet, consectetur adipisicing elit. Corporis, obcaecati."
            </h1>
          </swiper-slide>
          <swiper-slide class="w-[280px] scroll-bottom-1"
            ><img class="w-[200px] mx-auto" src="../assets/KhinWintWar.jpeg" />
            <h1 class="text-2xl text-slate-700 font-semibold mt-12 text-center">
              Khin Wint War
            </h1>
            <h1 class="text-1xl text-slate-400 font-semibold text-center">
              HR, Technology Reaction
            </h1>
            <h1
              class="text-1xl text-slate-600 font-semibold text-center mt-6 mx-auto"
            >
              "I love This | couldn't do my job with it Lorem ipsum dolor sit
              amet, consectetur adipisicing elit. Corporis, obcaecati."
            </h1>
          </swiper-slide>
          <swiper-slide class="w-[280px] scroll-bottom-2"
            ><img class="w-[200px] mx-auto" src="../assets/Nannayuri1.png" />
            <h1 class="text-2xl text-slate-700 font-semibold mt-12 text-center">
              Nanna Yuri
            </h1>
            <h1 class="text-1xl text-slate-400 font-semibold text-center">
              Consultant, Technology Reaction
            </h1>
            <h1
              class="text-1xl text-slate-600 font-semibold text-center mt-6 mx-auto"
            >
              "I love This | couldn't do my job with it Lorem ipsum dolor sit
              amet, consectetur adipisicing elit. Corporis, obcaecati."
            </h1>
          </swiper-slide>
          <swiper-slide class="w-[280px] scroll-bottom-3"
            ><img class="w-[200px] mx-auto" src="../assets/Model01.jpeg" />
            <h1 class="text-2xl text-slate-700 font-semibold mt-12 text-center">
              Nay Chi
            </h1>
            <h1 class="text-1xl text-slate-400 font-semibold text-center">
              Assistant, Technology Reaction
            </h1>
            <h1
              class="text-1xl text-slate-600 font-semibold text-center mt-6 mx-auto"
            >
              "I love This | couldn't do my job with it Lorem ipsum dolor sit
              amet, consectetur adipisicing elit. Corporis, obcaecati."
            </h1>
          </swiper-slide>
          <swiper-slide class="w-[280px] scroll-bottom-4"
            ><img class="w-[200px] mx-auto" src="../assets/Model02.jpeg" />
            <h1 class="text-2xl text-slate-700 font-semibold mt-12 text-center">
              Myat Noe Khin
            </h1>
            <h1 class="text-1xl text-slate-400 font-semibold text-center">
              Student, Technology Reaction
            </h1>
            <h1
              class="text-1xl text-slate-600 font-semibold text-center mt-6 mx-auto"
            >
              "I love This | couldn't do my job with it Lorem ipsum dolor sit
              amet, consectetur adipisicing elit. Corporis, obcaecati."
            </h1>
          </swiper-slide>
        </swiper>
        <!-- end swiperjs -->
      </div>
    </div>
  </div>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/effect-coverflow";
import "swiper/css/pagination";

// import required modules
import { EffectCoverflow, Pagination, Navigation } from "swiper";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [EffectCoverflow, Pagination, Navigation],
    };
  },
};
</script>

<style>
</style>