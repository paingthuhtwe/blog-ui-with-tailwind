<template>
  <div class="">
    <div class="w-10/12 mx-auto">
      <div class="grid md:grid-cols-2 mt-5 md:mt-20">
        <div class="">
          <h1 class="text-indigo-600 text-lg font-semibold">
            <fa class="text-2xl" :icon="['fas', 'user-graduate']" />
            Best E-Learning Platform
          </h1>
          <h1 class="text-4xl md:text-6xl text-slate-700 font-bold mt-6">
            Best Getting <br />
            Quality Education <br />
            Is Now More Easier
          </h1>
          <p class="text-slate-600 font-medium mt-4">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam
            sequi sunt accusamus repudiandae. Commodi voluptatibus unde magnam
            autem, nam sed beatae quasi dolores cumque omnis, doloribus sequi
            incidunt tempore nobis.
          </p>
          <div class="mt-6 grid md:grid-cols-2 lg:grid-cols-3">
            <div class="">
              <button
                class="text-slate-800 bg-yellow-400 w-36 h-10 text-md font-semibold rounded-full hover:bg-yellow-300 hover:text-slate-700 mr-1 mb-3 md:mb-0"
              >
                Join Course
              </button>
            </div>
            <div class="">
              <a href=""
                ><button
                  class="w-10 h-10 rounded-full bg-indigo-600 text-white mr-1 hover:bg-indigo-700 hover:text-slate-200"
                >
                  <fa :icon="['fas', 'play']" /></button
                ><span class="text-slate-700 font-semibold">
                  See how it work?
                </span></a
              >
            </div>
          </div>
        </div>
        <div class="flex justify-center items-end">
          <img src="../assets/Education.png" alt="Education_Image" />
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