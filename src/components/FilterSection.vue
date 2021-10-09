<template>
  <div class="flex space-x-5">
    <div
      v-for="(filter, index) in filters"
      :key="filter"
      @click="changeFilter(index)"
      :class="[
        'px-7',
        'py-2',
        activeClass(index),
        'rounded-md',
        'cursor-pointer',
        'text-sm',
        'font-semibold',
        'transition-all',
        'duration-300',
      ]"
    >
      {{ filter }}
    </div>
  </div>
</template>

<script>
export default {
  props: ["filters", "activeFilter"],
  methods: {
    changeFilter(index) {
      this.$emit("changeFilter", index);
    },
    activeClass(index) {
      if (index == this.activeFilter) {
        return ["banner-gradient", "text-white"];
      } else {
        return ["bg-gray-200", "text-gray-400"];
      }
    },
  },
};
</script>
