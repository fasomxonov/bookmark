<template>
  <!-- Features -->
  <div class="bg-bookmark-white py-20 mt-20 lg:mt-60">
    <!-- Heading -->
    <div class="sm:w-3/4 lg:w-5/12 mx-auto px-2">
      <h1 class="text-3xl text-center text-bookmark-blue">Features</h1>
      <p class="text-center text-bookmark-grey mt-4">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Pariatur magni
        aspernatur non molestias fugit necessitatibus, a quae fugiat ducimus
        omnis.
      </p>
    </div>
    <!-- Feature 1-->
    <div class="relative mt-20 lg:mt-24">
      <div
        class="container max-w-7xl mx-auto flex flex-col items-center justify-center gap-x-24 lg:flex-row"
      >
        <!-- Image -->
        <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
          <img
            class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full"
            src="@/assets/illustration-features-tab-1.png"
            alt="illustration-features-tab-1"
          />
        </div>
        <!-- Content -->
        <div class="flex flex-1 flex-col items-center lg:items-start">
          <h1 class="text-3xl text-bookmark-blue">Bookmark in one click</h1>
          <p
            class="text-bookmark-grey my-4 text-center sm:w-3/4 lg:text-left lg:w-full"
          >
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos in
            impedit consequuntur nesciunt cupiditate dolorum deserunt repellat
            unde iste, neque, fuga magnam. Iste labore, dolores molestias quasi
            ad at temporibus?
          </p>
          <button
            class="btn btn-purple hover:bg-bookmark-white hover:text-black"
            type="button"
          >
            More Info
          </button>
        </div>
      </div>
      <!-- Rounded Rectangle -->
      <div
        class="absolute h-80 w-5/12 top-32 left-0 hidden overflow-hidden bg-bookmark-purple rounded-r-full lg:block"
      ></div>
    </div>
    <!-- Feature 2 -->
    <div class="relative mt-20 lg:mt-52">
      <div
        class="container max-w-7xl mx-auto flex flex-col items-center justify-center gap-x-24 lg:flex-row-reverse"
      >
        <!-- Image -->
        <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
          <img
            class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full"
            src="@/assets/illustration-features-tab-2.png"
            alt="illustration-features-tab-1"
          />
        </div>
        <!-- Content -->
        <div class="flex flex-1 flex-col items-center lg:items-start">
          <h1 class="text-3xl text-bookmark-blue">Intelligent search</h1>
          <p
            class="text-bookmark-grey my-4 text-center sm:w-3/4 lg:text-left lg:w-full"
          >
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos in
            impedit consequuntur nesciunt cupiditate dolorum deserunt repellat
            unde iste, neque, fuga magnam.
          </p>
          <button
            class="btn btn-purple hover:bg-bookmark-white hover:text-black"
            type="button"
          >
            More Info
          </button>
        </div>
      </div>
      <!-- Rounded Rectangle -->
      <div
        class="absolute h-80 w-5/12 top-32 right-0 hidden overflow-hidden bg-bookmark-purple rounded-l-full lg:block"
      ></div>
    </div>
    <!-- Feature 3-->
    <div class="relative mt-20 lg:mt-52">
      <div
        class="container max-w-7xl mx-auto flex flex-col items-center justify-center gap-x-24 lg:flex-row"
      >
        <!-- Image -->
        <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
          <img
            class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full"
            src="@/assets/illustration-features-tab-3.png"
            alt="illustration-features-tab-1"
          />
        </div>
        <!-- Content -->
        <div class="flex flex-1 flex-col items-center lg:items-start">
          <h1 class="text-3xl text-bookmark-blue">Share your Bookmarks</h1>
          <p
            class="text-bookmark-grey my-4 text-center sm:w-3/4 lg:text-left lg:w-full"
          >
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos in
            impedit consequuntur nesciunt cupiditate dolorum deserunt repellat
            unde iste, neque, fuga magnam. Iste labore dolores.
          </p>
          <button
            class="btn btn-purple hover:bg-bookmark-white hover:text-black"
            type="button"
          >
            More Info
          </button>
        </div>
      </div>
      <!-- Rounded Rectangle -->
      <div
        class="absolute h-80 w-5/12 top-32 left-0 hidden overflow-hidden bg-bookmark-purple rounded-r-full lg:block"
      ></div>
    </div>
  </div>
</template>

<script setup></script>
