<script setup>
const catalogs = [
  { title: "Christmas 2024", tags: ["Sneakers", "boots"] },
  { title: "A very big title for a catalog with many thing", tags: ["Sneakers", "boots", "Belt", "Socks", "+3"] },
]
</script>

<template>
  <div class="min-h-screen bg-background md:bg-white lg:ml-80">
    <div class="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-3 gap-4 max-w-content p-4 lg:p-8">
      <div class="flex flex-col p-4 rounded-lg border border-grey-200 bg-white">
        <h2 class="mb-2 text-sm md:text-lg font-semibold">Create catalog</h2>
        <p class="mb-10 md:mb-4 text-xs md:text-sm text-grey-500">Create new catalog to add products and generate content.</p>

        <button class="flex justify-center items-center gap-2 mt-auto py-3 rounded-md bg-primary text-white text-sm font-medium">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
            <path d="M12 8v8M8 12h8" stroke-linecap="round" stroke-linejoin="round" />
          </svg>
          Create catalog
        </button>
      </div>

      <div v-for="catalog in catalogs" :key="catalog.title" class="p-4 rounded-lg border border-grey-200 bg-white">
        <h2 class="flex justify-between items-start gap-2 text-lg font-bold">
          {{ catalog.title }}
          <button class="text-grey-500">...</button>
        </h2>

        <div class="flex flex-wrap gap-2 mt-4">
          <span v-for="tag in catalog.tags" :key="tag" class="px-2 rounded border border-grey-300 bg-grey-light text-xs">{{ tag }}</span>
        </div>

        <p class="mt-3 text-xs md:text-sm text-grey-500">Created on 12.27.2024</p>
        <p class="mt-3 text-xs md:text-sm font-semibold">254 products</p>
      </div>
    </div>
  </div>
</template>
