<template>
  <div class="relative">
    <div
      class="container  max-w-7xl mx-auto flex flex-col-reverse items-center gap-12 mt-14 lg:mt-28 lg:flex-row"
    >
    <!-- Content -->
      <div class="flex flex-1 flex-col items-center lg:items-start">
        <h2
          class="text-bookmark-blue text-3xl mb-6 text-center md:text-4 lg:text-left lg:text-5xl"
        >
          A Simple Bookmark Manager
        </h2>
        <p class="text-bookmark-grey text-lg text-center mb-6 lg:text-left">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam
          excepturi possimus incidunt mollitia rem expedita cum eligendi
          doloremque ipsum eaque ab, beatae error ipsam accusantium fugiat est,
          vitae dolore perferendis!
        </p>
        <div class="flex justify-center flex-wrap gap-6">
            <button class="btn btn-purple hover:bg-bookmark-white hover:text-black" type="button">Get it on Chrome</button>
            <button class="btn btn-white hover:bg-gray-200" type="button">Get it on Firefox</button>
        </div>
      </div>
      <!-- Image -->
      <div class="flex justify-center flex-1 mb-10 z-10 md:mb-16 lg:mb-0">
        <img class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full" src="@/assets/hero-bg.png" alt="hero-bg">
      </div>
    </div>
    <!-- Rounded Rectangle -->
    <div class="absolute h-80 w-2/4 top-32 right-0 hidden overflow-hidden bg-bookmark-purple rounded-l-full md:block"></div>
  </div>
</template>

<script setup></script>
