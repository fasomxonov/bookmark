<template>
  <!-- Download -->
  <div class="py-20 mt-20 max-w-7xl mx-auto">
    <!-- Heading -->
    <div class="sm:w-3/4 lg:w-5/12 mx-auto px-2">
      <h1 class="text-3xl text-center text-bookmark-blue">
        Download the extension
      </h1>
      <p class="text-center text-bookmark-grey mt-4">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Pariatur magni
        aspernatur non molestias fugit necessitatibus a quae.
      </p>
    </div>
    <!-- Cards -->
    <div
      class="container max-w-screen-lg mt-16 gap-16 flex flex-wrap justify-center"
    >
      <!-- Card 1 -->
      <div class="card_1 flex flex-col rounded-md shadow-md">
        <div class="p-6 flex flex-col items-center">
          <img src="@/assets/logo-chrome.svg" alt="logo-chrome" />
          <h3 class="mt-5 mb-2 text-bookmark-blue text-lg">Add to Chrome</h3>
          <p class="mb-2 text-bookmark-grey font-light">Minimum version 6.2</p>
        </div>
        <hr class="border-b border-bookmark-white" />
        <div class="flex p-6">
          <button
            class="btn btn-purple flex-1 hover:bg-bookmark-white hover:text-black"
            type="button"
          >
            Add & Install Extension
          </button>
        </div>
      </div>
      <!-- Card 2 -->
      <div class="card_2 flex flex-col rounded-md shadow-md">
        <div class="p-6 flex flex-col items-center">
          <img src="@/assets/logo-firefox.svg" alt="logo-chrome" />
          <h3 class="mt-5 mb-2 text-bookmark-blue text-lg">Add to Firefox</h3>
          <p class="mb-2 text-bookmark-grey font-light">Minimum version 6.2</p>
        </div>
        <hr class="border-b border-bookmark-white" />
        <div class="flex p-6">
          <button
            class="btn btn-purple flex-1 hover:bg-bookmark-white hover:text-black"
            type="button"
          >
            Add & Install Extension
          </button>
        </div>
      </div>
      <!-- Card 3 -->
      <div class="card_3 flex flex-col rounded-md shadow-md">
        <div class="p-6 flex flex-col items-center">
          <img src="@/assets/logo-opera.svg" alt="logo-chrome" />
          <h3 class="mt-5 mb-2 text-bookmark-blue text-lg">Add to Opera</h3>
          <p class="mb-2 text-bookmark-grey font-light">Minimum version 6.2</p>
        </div>
        <hr class="border-b border-bookmark-white" />
        <div class="flex p-6">
          <button
            class="btn btn-purple flex-1 hover:bg-bookmark-white hover:text-black"
            type="button"
          >
            Add & Install Extension
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@media (min-width: 942px) {
  .card_1 {
    margin-bottom: 64px;
  }
  .card_2 {
    align-self: center;
  }
  .card_3 {
    align-self: flex-end;
  }
}
</style>