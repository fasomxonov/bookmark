<template>
  <Header>
    <nav
      :class="[!menu ? 'mt-4' : '']"
      class="relative container flex items-center py-4  max-w-7xl mx-auto"
    >
      <div class="py-1">
        <img src="@/assets/logo-bookmark.svg" alt="logo-bookmark" />
      </div>
      <ul :class="[menu ? menuOpen : menuClose]">
        <i :class="[menu ? closeBtn : '']" @click="menuBtn"></i>
        <li class="cursor-pointer">Features</li>
        <li class="cursor-pointer">Pricing</li>
        <li class="cursor-pointer">Contact</li>
        <button
          class="bg-bookmark-red text-white rounded-md px-7 py-3 uppercase"
          type="button"
        >
          Login
        </button>
      </ul>
      <div class="flex sm:hidden flex-1 justify-end">
        <i class="text-2xl fa-solid fa-bars" @click="menuBtn"></i>
      </div>
    </nav>
  </Header>
</template>

<script>
export default {
  data() {
    return {
      menu: false,
      closeBtn: [
        "fa-solid",
        "fa-xmark",
        "text-2xl",
        "mb-6",
        "flex",
        "self-end",
        "mt-4",
      ],
    };
  },
  methods: {
    menuBtn() {
      this.menu = !this.menu;
    },
  },
  computed: {
    menuOpen() {
      return [
        "absolute",
        "bg-gray-300",
        "top-0",
        "left-0",
        "w-full",
        "z-20",
        "px-4",
        "pb-16",
        "shadow-2xl",
        "flex",
        "flex-col",
        "items-center",
        "gap-2",
      ];
    },
    menuClose() {
      return [
        "hidden",
        "sm:flex",
        "flex-1",
        "justify-end",
        "items-center",
        "gap-12",
        "text-bookmark-blue",
        "uppercase",
        "text-xs",
      ];
    },
  },
};
</script>
