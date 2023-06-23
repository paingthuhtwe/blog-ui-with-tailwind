<template>
  <div class="my-20">
    <div class="w-10/12 mx-auto">
      <h1
        class="text-3xl md:text-5xl text-center text-slate-700 font-semibold mb-6"
      >
        Our Most Popular Courses
      </h1>
      <swiper
        ref="{swiperRef}"
        :slidesPerView="1"
        :spaceBetween="5"
        :modules="modules"
        :navigation="true"
        :breakpoints="{
          '390': {
            slidesPerView: 1,
            centeredSlides: true,
          },
          '768': {
            slidesPerView: 2,
            centeredSlides: true,
          },
          '1024': {
            slidesPerView: 4,
          },
        }"
        class="mySwiper"
      >
        <swiper-slide>
          <div
            class="bg-white shadow-lg rounded-lg w-[300px] h-[320px] border border-indigo-50 mx-auto p-3"
          >
            <img
              class="w-full rounded-lg h-[200px]"
              src="https://img.freepik.com/free-vector/hand-drawn-science-education-background_23-2148499325.jpg?w=2000"
              alt=""
            />
            <h1 class="text-xl font-semibold text-slate-600 mt-5">
              Science Course For Kids
            </h1>
            <div class="flex justify-between items-center mt-3">
              <div class="">
                <h1 class="text-xl font-semibold text-slate-600">$50.00</h1>
              </div>
              <div class="flex gap-5">
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'book']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">34</p>
                </div>
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'user']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">80</p>
                </div>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div
            class="bg-white shadow-lg rounded-lg w-[300px] h-[320px] border border-indigo-50 mx-auto p-3"
          >
            <img
              class="w-full rounded-lg h-[200px]"
              src="https://www.bwseducationconsulting.com/wp-content/uploads/2020/08/bws-maths-tutoring.jpg"
              alt=""
            />
            <h1 class="text-xl font-semibold text-slate-600 mt-5">
              Basic Math Course
            </h1>
            <div class="flex justify-between items-center mt-3">
              <div class="">
                <h1 class="text-xl font-semibold text-slate-600">$70.00</h1>
              </div>
              <div class="flex gap-5">
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'book']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">32</p>
                </div>
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'user']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">34</p>
                </div>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div
            class="bg-white shadow-lg rounded-lg w-[300px] h-[320px] border border-indigo-50 mx-auto p-3"
          >
            <img
              class="w-full rounded-lg h-[200px]"
              src="https://www.fpacademy.co.in/blog/wp-content/uploads/2022/09/How-to-Learn-English-Speaking-at-Home-960x540-1.jpg"
              alt=""
            />
            <h1 class="text-xl font-semibold text-slate-600 mt-5">
              British Spoken Course
            </h1>
            <div class="flex justify-between items-center mt-3">
              <div class="">
                <h1 class="text-xl font-semibold text-slate-600">$120.00</h1>
              </div>
              <div class="flex gap-5">
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'book']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">30</p>
                </div>
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'user']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">56</p>
                </div>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div
            class="bg-white shadow-lg rounded-lg w-[300px] h-[320px] border border-indigo-50 mx-auto p-3"
          >
            <img
              class="w-full rounded-lg h-[200px]"
              src="https://study.com/cimages/videopreview/p3c2j8y73a.jpg"
              alt=""
            />
            <h1 class="text-xl font-semibold text-slate-600 mt-5">
              Geography Course
            </h1>
            <div class="flex justify-between items-center mt-3">
              <div class="">
                <h1 class="text-xl font-semibold text-slate-600">$45.00</h1>
              </div>
              <div class="flex gap-5">
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'book']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">32</p>
                </div>
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'user']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">34</p>
                </div>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div
            class="bg-white shadow-lg rounded-lg w-[300px] h-[320px] border border-indigo-50 mx-auto p-3"
          >
            <img
              class="w-full rounded-lg h-[200px] border"
              src="https://static.chotot.com/storage/chotot-kinhnghiem/c2c/2022/06/2e9345c5-image-1024x565.jpeg"
              alt=""
            />
            <h1 class="text-xl font-semibold text-slate-600 mt-5">
              Networking Course
            </h1>
            <div class="flex justify-between items-center mt-3">
              <div class="">
                <h1 class="text-xl font-semibold text-slate-600">$200.00</h1>
              </div>
              <div class="flex gap-5">
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'book']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">32</p>
                </div>
                <div class="flex items-center">
                  <div
                    class="w-[25px] h-[25px] bg-indigo-500 rounded-full flex items-center justify-center"
                  >
                    <fa class="text-white text-xs" :icon="['fas', 'user']" />
                  </div>
                  <p class="text-sm text-slate-700 font-semibold ms-1">34</p>
                </div>
              </div>
            </div>
          </div>
        </swiper-slide>
      </swiper>
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