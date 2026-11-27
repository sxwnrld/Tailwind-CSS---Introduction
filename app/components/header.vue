<template>
  <div>
    <!-- Barre du haut sur mobile, barre latérale à partir de md -->
    <nav class="bg-[#EEF1FF] fixed top-0 left-0 z-50 w-full h-16 flex items-center md:w-[318px] md:h-screen md:block">
      <h1 class="px-5 md:p-6 text-[28px] md:text-[40px] leading-none bg-gradient-to-r from-[#463ADD] via-[#FF00FB] to-[#FF00FB] md:to-transparent text-transparent bg-clip-text font-extrabold md:animate-pulse">
        TAILWIND
      </h1>
    </nav>

    <div class="pt-16 md:pt-0 md:ml-[318px] bg-white">
      <div class="flex justify-between items-center gap-3 px-3 sm:px-6 md:px-8 py-4 md:py-5">
        <h1 class="font-semibold text-[20px] md:text-[24px] whitespace-nowrap">
          My catalogs
        </h1>
        <button class="flex justify-center items-center gap-2 shrink-0 bg-[#463ADD] hover:bg-[#FF00FB] text-white font-medium text-[13px] md:text-[14px] rounded-md px-3 md:px-4 py-2 transition">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 md:w-5 md:h-5 shrink-0" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
            <path d="M12 8v8M8 12h8" stroke-linecap="round" stroke-linejoin="round" />
          </svg>

          <span>Create catalog</span>
        </button>
      </div>

      <div class="border-b border-gray-200 md:border-gray-300"></div>
    </div>
  </div>
</template>
