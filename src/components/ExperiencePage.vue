<template>
  <div class="my-20">
    <div class="w-10/12 mx-auto">
      <div class="grid md:grid-cols-2 gap-5">
        <div class="flex flex-col justify-center">
          <h1
            class="text-3xl md:text-5xl text-slate-700 font-semibold mb-6 scroll-left"
          >
            We Have High Expert & Experienced Tutors
          </h1>
          <p class="text-slate-600 font-normal pr-24 scroll-right">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Beatae
            exercitationem, unde explicabo cum quaerat aliquam? Labore, fugiat
            quidem. In sed blanditiis cupiditate aliquid, suscipit deserunt
            accusantium praesentium distinctio deleniti ea.
          </p>
          <button
            class="text-slate-800 bg-yellow-400 w-36 h-10 text-md font-semibold rounded-full hover:bg-yellow-300 hover:text-slate-700 mt-6 scroll-bottom"
          >
            Start Now
          </button>
        </div>
        <div class="relative">
          <img
            class="w-full md:ps-36 scroll-right"
            src="../assets/ManWithTablet.png"
            alt=""
          />
          <div
            class="absolute right-5 bottom-5 bg-white shadow-lg p-4 rounded-lg scroll-bottom"
          >
            <h1 class="text-sm font-semibold text-slate-700 mb-2">
              200+ Experienced Tours
            </h1>
            <div class="flex">
              <img
                class="w-6 h-6 rounded-full shadow p-[1px] bg-white hover:scale-110 hover:z-10 cursor-pointer"
                src="../assets/KhinWintWar.jpeg"
                alt=""
              />
              <img
                class="w-6 h-6 rounded-full shadow p-[1px] bg-white hover:scale-110 hover:z-10 cursor-pointer -translate-x-2"
                src="../assets/Model01.jpeg"
                alt=""
              />
              <img
                class="w-6 h-6 rounded-full shadow p-[1px] bg-white hover:scale-110 hover:z-10 cursor-pointer -translate-x-4"
                src="../assets/Model02.jpeg"
                alt=""
              />
              <img
                class="w-6 h-6 rounded-full shadow p-[1px] bg-white hover:scale-110 hover:z-10 cursor-pointer -translate-x-6"
                src="../assets/Nannayuri1.png"
                alt=""
              />
              <img
                class="w-6 h-6 rounded-full shadow p-[1px] bg-white hover:scale-110 hover:z-10 cursor-pointer -translate-x-8"
                src="../assets/Nannayuri2.png"
                alt=""
              />
              <div
                class="w-6 h-6 rounded-full shadow p-[1px] bg-pink-400 hover:scale-110 hover:z-10 cursor-pointer -translate-x-10 flex items-center justify-center"
              >
                <fa class="text-xs text-white" :icon="['fas', 'plus']" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>