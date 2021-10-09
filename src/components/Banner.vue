<template>
  <div>
    <div
      class="relative banner-gradient px-6 py-7 mt-4 rounded-xl overflow-hidden text-white flex"
    >
      <div>
        <img
          src="../assets/decoration/line-deco.png"
          alt="Line"
          class="absolute left-0 -top-5 pointer-events-none"
        />
        <img
          src="../assets/decoration/home-deco2.png"
          alt="Decoration"
          class="absolute top-0 left-1/2 pointer-events-none"
        />
      </div>
      <div class="w-3/4 lg:w-5/6">
        <h1 class="text-3xl font-heading">
          Yuk Kirim Angpao!
        </h1>
        <p class="opacity-90 text-xs leading-relaxed mt-1 my-4">
          Kirim Angpao ke keluarga atau temanmu dengan gampang dan praktis
        </p>
        <button
          class="text-gray-900 btn-gradient text-xs px-4 py-2 cursor-pointer font-bold rounded-md focus:outline-none hover:btn-gradient"
        >
          Coba Sekarang
        </button>
      </div>
      <div class="w-32 lg:w-24 relative lg:top-10">
        <img
          src="../assets/icon/banner.png"
          class="absolute -right-7"
          alt="Banner Illustration"
        />
      </div>
    </div>
    <div class="flex space-x-2 justify-center mt-4">
      <div class="w-9 h-2 bg-red-500 rounded-full cursor-pointer"></div>
      <div class="w-2 h-2 bg-gray-300 rounded-full cursor-pointer"></div>
      <div class="w-2 h-2 bg-gray-300 rounded-full cursor-pointer"></div>
    </div>
  </div>
</template>
