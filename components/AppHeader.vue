<template>
  <nav class="bg-white border-gray-200 shadow">
    <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-3">
      <a href="" class="flex items-center rtl:space-x-reverse">
        <div class="text-brand">
          <span class="text-[#46A09B]">MM</span><span class="text-black">LL</span>
        </div>
      </a>
      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
        aria-controls="navbar-default"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5 text-[#46A09B]"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
    </div>
  </nav>

  <div class="bg-[#46A09B] p-2 flex items-center gap-x-3">
    <button
      class="bg-white p-1 rounded-full flex items-center justify-center px-1.5 text-xs text-black gap-x-1"
    >
      ยอดขายสด
      <span class="w-[10px] h-[10px] rounded-full bg-red-500"></span>
    </button>
    <div class="text-white text-xs font-light">ผู้ใช้: Us78**</div>
    <div class="text-white text-xs font-light">ซื้อเลข: 12234</div>
  </div>
</template>

<script setup></script>

<style scoped>
.text-brand {
  text-align: left;
  font: italic normal 800 28px/42px Kanit;
  letter-spacing: 0px;
  opacity: 1;
  width: 50px;
}
</style>
