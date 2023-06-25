<template>
  <div class="bg-indigo-500">
    <div class="w-10/12 mx-auto py-20">
      <div class="md:flex">
        <div class="md:w-2/5">
          <h1 class="text-white text-2xl font-semibold">Educate.</h1>
          <p class="text-white text-md font-normal mt-2">
            educate.org@gmail.com
          </p>
          <p class="text-white text-md font-normal">+959 780 909 574</p>
          <div class="mt-3">
            <fa
              class="text-2xl text-white rounded-full hover:scale-110 cursor-pointer mr-3"
              :icon="['fab', 'facebook']"
            />
            <fa
              class="text-2xl text-white rounded-full hover:scale-110 cursor-pointer mr-3"
              :icon="['fab', 'twitter']"
            />
            <fa
              class="text-2xl text-white rounded-full hover:scale-110 cursor-pointer"
              :icon="['fas', 'envelope']"
            />
          </div>
        </div>
        <div
          class="md:w-3/5 grid grid-cols-2 md:grid-cols-4 mt-5 md:mt-0 gap-5"
        >
          <div class="">
            <ul>
              <li class="text-lg text-white font-semibold mb-3">About Us</li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Company</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Teams</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Profile</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Career</a>
              </li>
            </ul>
          </div>
          <div class="">
            <ul>
              <li class="text-lg text-white font-semibold mb-3">About Us</li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Company</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Teams</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Profile</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Career</a>
              </li>
            </ul>
          </div>
          <div class="">
            <ul>
              <li class="text-lg text-white font-semibold mb-3">Courses</li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">English</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Science</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Mathematics</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Geography</a>
              </li>
            </ul>
          </div>
          <div class="">
            <ul>
              <li class="text-lg text-white font-semibold mb-3">
                Stay up to Date
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Become an instructor</a>
              </li>
              <li
                class="text-sm text-slate-100 font-normal hover:underline mb-2"
              >
                <a href="#">Become a student</a>
              </li>
              <li
                class="w-[150px] text-sm text-indigo-600 text-center font-semibold hover:underline bg-white py-2 rounded-full"
              >
                <fa class="mr-2" :icon="['fas', 'earth']" />
                <select name="language" id="">
                  <option value="english">English</option>
                  <option value="myanmar">Myanmar</option>
                </select>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="pt-6">
        <p class="text-white text-sm font-semibold">
          &copy; 2023. All Rights Reserved By Educate.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>