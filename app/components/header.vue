<template>
  <div>
    <!-- Barre du haut sur téléphone et tablette, barre latérale à partir de lg (1024px) -->
    <nav class="bg-[#EEF1FF] fixed top-0 left-0 z-50 w-full h-16 flex items-center lg:w-[318px] lg:h-screen lg:block">
      <h1 class="px-4 sm:px-6 lg:p-6 text-[24px] min-[360px]:text-[28px] sm:text-[32px] lg:text-[40px] leading-none bg-gradient-to-r from-[#463ADD] via-[#FF00FB] to-[#FF00FB] lg:to-transparent text-transparent bg-clip-text font-extrabold lg:animate-pulse">
        TAILWIND
      </h1>
    </nav>

    <div class="pt-16 lg:pt-0 lg:ml-[318px] bg-white">
      <div class="flex justify-between items-center gap-2 min-[360px]:gap-3 px-3 sm:px-6 lg:px-8 py-4 lg:py-5">
        <h1 class="font-semibold text-[18px] min-[360px]:text-[20px] md:text-[24px] whitespace-nowrap">
          My catalogs
        </h1>
        <button class="flex justify-center items-center gap-1.5 min-[360px]:gap-2 shrink-0 bg-[#463ADD] hover:bg-[#FF00FB] text-white font-medium text-[12px] min-[360px]:text-[13px] md:text-[14px] rounded-md px-2.5 min-[360px]:px-3 md:px-4 py-2 transition">
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
