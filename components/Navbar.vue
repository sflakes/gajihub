<template>
  <div id="Heroku">
    <!-- <header class="sm:flex sm:justify-between sm:items-center sm:px-4 sm:py-3"> -->
        <header class="flex justify-between items-center px-24 py-10 ">
      <!-- <img src="../assets/bg.svg" alt=""> -->
      <div class="flex items-center justify-between px- py-3 sm:p-0">
        <div>
          <!-- <img class="h-8" src="/img/logo-inverted.svg" alt="Workcation" /> -->
          <a
            href="#"
            class="mt-1 block px-2 py-1 text-white font-semibold rrede5 sm:mt-0 sm:ml-2"
            >
            <img src="../assets/logo.svg" alt="">
            </a
          >
        </div>
        <div class="sm:hidden">
          <button
            @click="isOpen = !isOpen"
            type="button"
            class="block text-gray-500 hover:text-white focus:text-white focus:outline-none"
          >
            <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
              <path
                v-if="isOpen"
                fill-rule="evenodd"
                d="M18.278 16.864a1 1 0 0 1-1.414 1.414l-4.829-4.828-4.828 4.828a1 1 0 0 1-1.414-1.414l4.828-4.829-4.828-4.828a1 1 0 0 1 1.414-1.414l4.829 4.828 4.828-4.828a1 1 0 1 1 1.414 1.414l-4.828 4.829 4.828 4.828z"
              />
              <path
                v-if="!isOpen"
                fill-rule="evenodd"
                d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
              />
            </svg>
          </button>
        </div>
      </div>
      <nav
        :class="isOpen ? 'block' : 'hidden'"
        class="px-2 pt-2 pb-4 sm:flex sm:p-0"
      >
        <a
          href="#"
          class="block px-2 py-1 text-white font-normal rounded hover:bg-red-500"
          >Home</a
        >
        <a
          href="#"
          class="mt-1 block px-2 py-1 text-white font-normal rounded hover:bg-red-500 sm:mt-0 sm:ml-2"
          >Solusi</a
        >
        <a
          href="#"
          class="mt-1 block px-2 py-1 text-white font-normal rounded hover:bg-red-500 sm:mt-0 sm:ml-2"
          >Blog</a
        >
        <a
          href="#"
          class="mt-1 block px-2 py-1 text-white font-normal rounded hover:bg-red-500 sm:mt-0 sm:ml-2"
          >Pricing</a
        >
        <a
          href="#"
          class="mt-1 block px-2 py-1 text-white font-normal rounded hover:bg-red-500 sm:mt-0 sm:ml-2"
          >Login</a
        >
        <a
          href="#"
          class="mt-1 block px-2 py-1 text-white font-normal rounded hover:bg-red-500 sm:mt-0 sm:ml-2"
          >DAFTAR GRATIS</a
        >
      </nav>
    </header>
    <div class="flex justify-center flex-col mt-32">
      <div class="flex justify-center mb-6" >
        <h1 class="text-6xl text-white font-medium text-center" style="width: 50.597rem">
          Memanage Payroll Tidak Pernah Semudah Ini
        </h1>
      </div>
      <p class="text-base text-center text-white mb-16">
        Aplikasi payroll terbaik yang telah di gunakan oleh Unicorn di Indonesia
      </p>
      <div class="flex justify-center mb-8">
        <button class="text-base bg-red-500 text-white px-6 py-3 rounded">
          Try For Free
        </button>
      </div>
    </div>
    <div class="flex justify-center">
      <img src="../assets/apps.svg" alt="apps" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false,
    };
  },
};
</script>

<style>
#Heroku {
  background-image: url("@/assets/bg.svg");
  background-size: cover;
  width: 100%;
  height: 53.563rem;
}
</style>
