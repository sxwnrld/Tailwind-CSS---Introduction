<template>
  <div>
    <nav class="fixed top-0 left-0 z-50 flex items-center w-full h-16 px-4 bg-blue-light lg:block lg:w-80 lg:h-screen lg:p-6">
      <h1 class="text-3xl lg:text-4xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-primary via-secondary to-secondary lg:to-transparent lg:animate-pulse">
        TAILWIND
      </h1>
    </nav>

    <div class="flex justify-between items-center pt-20 pb-4 px-4 border-b border-grey-300 lg:ml-80 lg:pt-5 lg:px-8">
      <h1 class="text-xl md:text-2xl font-semibold">My catalogs</h1>

      <button class="flex items-center gap-2 px-4 py-2 rounded-md bg-primary text-white text-sm font-medium">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
          <path d="M12 8v8M8 12h8" stroke-linecap="round" stroke-linejoin="round" />
        </svg>
        Create catalog
      </button>
    </div>
  </div>
</template>
