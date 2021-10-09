<template>
  <div class="bg-white text-gray-900 px-6 py-5 rounded-md flex cursor-pointer">
    <div class="mr-3 w-2/12 flex items-center">
      <img
        v-if="history.type == 'angpao'"
        src="../assets/icon/Red Pockets.png"
        alt="Red Pocket"
      />
      <img v-else src="../assets/icon/Top Up.png" alt="Top Up" />
    </div>
    <div class="w-10/12 flex justify-between">
      <div>
        <h3 class="font-bold text-base">
          {{ history.desc }}
        </h3>
        <p class="text-gray-400 text-sm leading-relaxed">{{ history.user }}</p>
      </div>
      <div class="text-gray-400 text-xs">{{ history.date }}</div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["history"],
  methods: {
    getPicture(type) {
      return type == "top_up" ? "Top Up.png" : "Red Pockets.png";
    },
  },
};
</script>
