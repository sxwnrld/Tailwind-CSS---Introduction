<template>
  <div class="lg:ml-[318px] min-h-[calc(100vh-8rem)] bg-[#FBFBFD] md:bg-white">
    <div class="grid grid-cols-[repeat(auto-fill,minmax(min(100%,280px),1fr))] 2xl:grid-cols-[repeat(auto-fill,minmax(360px,1fr))] gap-2 md:gap-4 px-3 pt-6 pb-6 sm:p-6 lg:p-8">
      <div class="bg-white border border-gray-200 md:border-2 md:border-gray-100 w-full rounded-lg p-3 md:p-4 md:py-5 flex flex-col">
        <h2 class="font-medium md:font-semibold text-[13px] md:text-[18px] mb-2">Create catalog</h2>
        <p class="text-gray-500 text-[12px] md:text-[14px] mb-10 md:mb-4">Create new catalog to add products and generate content.</p>
        <button class="w-full flex justify-center items-center gap-2 mt-auto bg-[#463ADD] text-white font-medium text-[14px] rounded-md py-2.5 md:py-3">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 md:w-5 md:h-5 shrink-0" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
            <path d="M12 8v8M8 12h8" stroke-linecap="round" stroke-linejoin="round" />
          </svg>

          <span>Create catalog</span>
        </button>
      </div>

      <div class="bg-white border border-gray-200 md:border-2 md:border-gray-100 w-full rounded-lg p-3 py-4 md:p-4 md:py-5">
        <h2 class="flex items-start justify-between gap-2 font-semibold md:font-bold text-[18px] mt-2 md:mt-0">
          <span class="min-w-0 break-words">Christmas 2024</span>
          <button class="text-gray-500 shrink-0 leading-none" aria-label="Options">...</button>
        </h2>
        <div class="flex flex-wrap gap-2 mt-4">
          <button class="border border-gray-300 md:border-2 md:border-gray-150 px-2 md:px-3 text-[11px] md:text-[12px] bg-[#F9F9FB] rounded">Sneakers</button>
          <button class="border border-gray-300 md:border-2 md:border-gray-150 px-2 md:px-3 text-[11px] md:text-[12px] bg-[#F9F9FB] rounded">boots</button>
        </div>
        <p class="mt-3 text-gray-500 text-[12px] md:text-[14px]">Created on 12.27.2024</p>
        <p class="mt-2 md:mt-3 font-medium md:font-semibold text-[12px] md:text-[14px]">254 products</p>
      </div>

      <div class="bg-white border border-gray-200 md:border-2 md:border-gray-100 w-full rounded-lg p-3 md:p-4 md:py-5">
        <h2 class="flex items-start justify-between gap-2 font-semibold md:font-bold text-[16px] md:text-[18px] leading-snug">
          <span class="min-w-0 break-words">A very big title for a catalog with many thing</span>
          <button class="text-gray-500 shrink-0 leading-none" aria-label="Options">...</button>
        </h2>
        <div class="flex flex-wrap gap-2 mt-3 md:mt-4">
          <button class="border border-gray-300 md:border-2 md:border-gray-150 px-2 md:px-3 text-[11px] md:text-[12px] bg-[#F9F9FB] rounded">Sneakers</button>
          <button class="border border-gray-300 md:border-2 md:border-gray-150 px-2 md:px-3 text-[11px] md:text-[12px] bg-[#F9F9FB] rounded">boots</button>
          <button class="border border-gray-300 md:border-2 md:border-gray-150 px-2 md:px-3 text-[11px] md:text-[12px] bg-[#F9F9FB] rounded">Belt</button>
          <button class="border border-gray-300 md:border-2 md:border-gray-150 px-2 md:px-3 text-[11px] md:text-[12px] bg-[#F9F9FB] rounded">Socks</button>
          <button class="border border-gray-300 md:border-2 md:border-gray-150 px-2 md:px-3 text-[11px] md:text-[12px] bg-[#F9F9FB] rounded">+3</button>
        </div>
        <p class="mt-3 text-gray-500 text-[12px] md:text-[14px]">Created on 12.27.2024</p>
        <p class="mt-2 md:mt-3 font-medium md:font-semibold text-[12px] md:text-[14px]">254 products</p>
      </div>
    </div>
  </div>
</template>
