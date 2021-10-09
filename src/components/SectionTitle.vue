<template>
  <div class="flex justify-between items-center">
    <div class="w-9/12">
      <h2 class="font-extrabold text-gray-900 text-xl leading-relaxed">
        {{ title }}
      </h2>
      <p class="font-medium text-xs text-gray-400 lg:mt-0 mt-1">
        {{ tagline }}
      </p>
    </div>
    <a
      v-if="viewMore"
      href="#"
      class="whitespace-nowrap text-red-500 font-semibold text-xs hover:underline"
      >Lihat Semua</a
    >
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    tagline: String,
    viewMore: {
      type: Boolean,
      default: false,
    },
  },
};
</script>
