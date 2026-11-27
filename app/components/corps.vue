<template>
  <div class="md:ml-[318px]">
    <div class="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-3 gap-4 p-4 sm:p-6 md:p-8">
      <div class="border-2 border-gray-100 w-full rounded-lg p-4 py-5 flex flex-col">
        <h2 class="font-semibold text-[18px] mb-2">Create catalog</h2>
        <p class="text-gray-500 text-[14px] mb-4">Create new catalog to add products and generate content.</p>
        <button class="w-full flex justify-center items-center gap-2 mt-auto bg-[#463ADD] hover:bg-[#FF00FB] text-white font-medium text-[14px] rounded-md py-3 transition">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 shrink-0" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
            <path d="M12 8v8M8 12h8" stroke-linecap="round" stroke-linejoin="round" />
          </svg>

          <span>Create catalog</span>
        </button>
      </div>

      <div class="border-2 border-gray-100 w-full rounded-lg p-4 py-5">
        <h2 class="flex items-start justify-between gap-2 font-bold text-[18px]">
          <span class="min-w-0 break-words">Christmas 2024</span>
          <button class="text-gray-500 shrink-0" aria-label="Options">...</button>
        </h2>
        <div class="flex flex-wrap gap-2 mt-4">
          <button class="border-2 border-gray-150 px-3 text-[12px] bg-[#F9F9FB] rounded-md">Sneakers</button>
          <button class="border-2 border-gray-150 px-3 text-[12px] bg-[#F9F9FB] rounded-md">boots</button>
        </div>
        <p class="mt-3 text-gray-500 text-[14px]">Created on 12.27.2024</p>
        <p class="mt-3 font-semibold text-[14px]">254 products</p>
      </div>

      <div class="border-2 border-gray-100 w-full rounded-lg p-4 py-5">
        <h2 class="flex items-start justify-between gap-2 font-bold text-[18px]">
          <span class="min-w-0 break-words">A very big title for a catalog with many thing</span>
          <button class="text-gray-500 shrink-0" aria-label="Options">...</button>
        </h2>
        <div class="flex flex-wrap gap-2 mt-4">
          <button class="border-2 border-gray-150 px-3 text-[12px] bg-[#F9F9FB] rounded-md">Sneakers</button>
          <button class="border-2 border-gray-150 px-3 text-[12px] bg-[#F9F9FB] rounded-md">boots</button>
          <button class="border-2 border-gray-150 px-3 text-[12px] bg-[#F9F9FB] rounded-md">Belt</button>
          <button class="border-2 border-gray-150 px-3 text-[12px] bg-[#F9F9FB] rounded-md">Socks</button>
          <button class="border-2 border-gray-150 px-3 text-[12px] bg-[#F9F9FB] rounded-md">+3</button>
        </div>
        <p class="mt-3 text-gray-500 text-[14px]">Created on 12.27.2024</p>
        <p class="mt-3 font-semibold text-[14px]">254 products</p>
      </div>
    </div>
  </div>
</template>
