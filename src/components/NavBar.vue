<template>
  <div class="fixed w-full top-0 bg-slate-50 z-50">
    <div class="w-10/12 mx-auto py-5 relative">
      <div class="flex justify-between">
        <!-- Logo & Brand -->
        <div class="flex items-center cursor-pointer">
          <fa
            class="text-indigo-800 text-3xl mr-1"
            :icon="['fas', 'graduation-cap']"
          />
          <h1 class="text-indigo-600 text-2xl font-semibold">Educate</h1>
        </div>
        <!-- Menu Section -->
        <div class="md:flex justify-center items-center relative hidden">
          <ul class="md:flex items-center">
            <li class="" @mouseenter="menu = !menu" @mouseleave="menu = !menu">
              <button
                id="mega-menu-dropdown-button"
                data-dropdown-toggle="mega-menu-dropdown"
                class="flex items-center justify-between w-full px-8 py-2 text-slate-400 text-md font-semibold hover:text-indigo-600 pl-3 pr-4 border-b border-gray-100 md:w-auto hover:bg-gray-50 md:hover:bg-transparent md:border-0"
              >
                Teachers
                <svg
                  aria-hidden="true"
                  class="w-5 h-5 ml-1"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
              </button>
              <div
                v-if="menu"
                id="mega-menu-dropdown"
                class="absolute z-10 grid w-auto grid-cols-2 text-sm bg-white border border-gray-100 rounded-lg shadow-md"
              >
                <div class="p-4 pb-0">
                  <ul
                    class="space-y-4"
                    aria-labelledby="mega-menu-dropdown-button"
                  >
                    <li>
                      <a
                        href="#"
                        class="text-slate-600 hover:text-indigo-600 font-semibold"
                      >
                        Web Developement
                      </a>
                    </li>
                    <li>
                      <a href="#" class="text-slate-600 hover:text-indigo-600">
                        Mr. John Doe
                      </a>
                    </li>
                    <li>
                      <a href="#" class="text-slate-600 hover:text-indigo-600">
                        Mr. Alice
                      </a>
                    </li>
                    <li>
                      <a href="#" class="text-slate-600 hover:text-indigo-600">
                        Mr. Tommy
                      </a>
                    </li>
                  </ul>
                </div>
                <div class="p-4 pb-0 text-gray-900 md:pb-4 dark:text-white">
                  <ul class="space-y-4">
                    <li>
                      <a
                        href="#"
                        class="text-slate-600 hover:text-indigo-600 font-semibold"
                      >
                        Mobile Development</a
                      >
                    </li>
                    <li>
                      <a href="#" class="text-slate-600 hover:text-indigo-600">
                        Mr. Bobby
                      </a>
                    </li>
                    <li>
                      <a href="#" class="text-slate-600 hover:text-indigo-600">
                        Ms. Kim Cham
                      </a>
                    </li>
                    <li>
                      <a href="#" class="text-slate-600 hover:text-indigo-600">
                        Mr. Lian Kim
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </li>
            <li class="">
              <a
                class="px-8 py-2 text-slate-400 text-md font-semibold hover:text-indigo-600"
                href="#about"
                >Courses</a
              >
            </li>
            <li class="">
              <a
                class="px-8 py-2 text-slate-400 text-md font-semibold hover:text-indigo-600"
                href="#about"
                >Schorlarship</a
              >
            </li>
            <li class="">
              <a
                class="px-8 py-2 text-slate-400 text-md font-semibold hover:text-indigo-600"
                href="#about"
                >Pricing</a
              >
            </li>
            <li class="">
              <a
                class="px-8 py-2 text-slate-400 text-md font-semibold hover:text-indigo-600"
                href="#about"
                >About Us</a
              >
            </li>
          </ul>
        </div>
        <div>
          <div class="md:flex items-center hidden">
            <a
              href="#"
              class="px-5 py-2 text-slate-600 text-md font-semibold hover:text-slate-800 rounded-full hover:bg-slate-200 cursor-pointe"
              >Sign In</a
            >
            <a
              href="#"
              class="px-5 py-2 text-slate-900 text-md font-semibold bg-yellow-400 rounded-full hover:text-slate-800 hover:bg-yellow-300 cursor-pointer"
              >Sign Up</a
            >
          </div>
          <!-- menu icon for mobile -->
          <button class="relative group md:hidden">
            <div
              class="relative flex overflow-hidden items-center justify-center rounded-full w-[40px] h-[40px] transform transition-all duration-200"
            >
              <div
                class="flex flex-col justify-between w-[20px] h-[20px] transform transition-all duration-300 origin-center overflow-hidden"
              >
                <div
                  class="bg-indigo-600 h-[2px] w-7 transform transition-all duration-300 origin-left group-focus:rotate-[42deg]"
                ></div>
                <div
                  class="bg-indigo-600 h-[2px] w-1/2 rounded transform transition-all duration-300 group-focus:-translate-x-10"
                ></div>
                <div
                  class="bg-indigo-600 h-[2px] w-7 transform transition-all duration-300 origin-left group-focus:-rotate-[42deg]"
                ></div>
              </div>
            </div>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    // for dark mode
    let mode = ref(null);
    !localStorage.getItem("theme") && [
      localStorage.setItem("theme", "light"),
      (mode.value = "light"),
    ];
    // get theme from localStorage
    localStorage.getItem("theme") == "dark"
      ? [
          (mode.value = "dark"),
          document.querySelector("html").classList.add("dark"),
        ]
      : [
          (mode.value = "light"),
          document.querySelector("html").classList.remove("dark"),
        ];
    // dark mode toggle method
    var toggleTheme = (theme) => {
      theme == "dark"
        ? [
            localStorage.setItem("theme", "dark"),
            (mode.value = theme),
            document.querySelector("html").classList.add("dark"),
          ]
        : [
            localStorage.setItem("theme", "light"),
            (mode.value = theme),
            document.querySelector("html").classList.remove("dark"),
          ];
    };

    // for menu toggle
    let menu = ref(false);
    var toggleMenu = () => {
      if (screen.width <= 400) {
        menu.value = !menu.value;
      }
    };
    return { mode, toggleTheme, menu, toggleMenu };
  },
};
</script>

<style scoped>
</style>