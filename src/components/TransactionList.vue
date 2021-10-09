<template>
  <div>
    <div class="flex py-5 w-full">
      <div
        class="rounded-2xl bg-gray-200 flex items-center justify-center mr-5 w-16 h-16"
      >
        <img
          src="../assets/icon/Red Pockets.png"
          class="w-8"
          alt="Red Pocket Icon"
        />
      </div>
      <div class="flex justify-between items-center w-9/12">
        <div>
          <div class="text-gray-400 font-medium text-xs -mt-2 mb-1">
            {{ transaction.date }}
          </div>
          <router-link to="/detail" class="font-bold text-base hover:underline">
            {{ transaction.title }}
          </router-link>
        </div>
        <div class="ml-3">
          <img src="../assets/icon/next.png" alt="Next Icon" />
        </div>
      </div>
    </div>
    <div class="w-full flex pr-8">
      <div class="w-16 mr-6"></div>
      <div class="w-10/12 border-b border-gray-200"></div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["transaction"],
};
</script>
