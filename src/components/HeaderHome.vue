<template>
  <header class="relative px-6 py-10 h-44 primary-gradient text-white">
    <img
      class="absolute left-0 top-0 select-none pointer-events-none"
      src="../assets/decoration/home-deco2.png"
    />
    <img
      class="absolute right-0 top-0 w-42 select-none pointer-events-none"
      src="../assets/decoration/home-deco.png"
    />
    <h1 class="text-3xl font-extrabold mb-1">{{ title }}</h1>
    <p class="font-medium text-xs opacity-90">{{ tagline }}</p>
  </header>
</template>

<script>
export default {
  props: ["title", "tagline"],
};
</script>
