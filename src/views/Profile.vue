<template>
  <div>
    <header class="banner-gradient text-white px-5 py-7">
      <nav class="flex items-center relative">
        <router-link to="/" class="absolute">
          <svg
            width="12"
            height="22"
            viewBox="0 0 12 22"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M11.6773 1.20529C12.0685 1.5888 12.104 2.18894 11.784 2.61184L11.6773 2.73299L2.8474 11.3889L11.6773 20.0448C12.0685 20.4283 12.104 21.0284 11.7839 21.4513L11.6773 21.5725C11.2861 21.956 10.6739 21.9909 10.2425 21.6771L10.1189 21.5725L0.51025 12.1527C0.119047 11.7692 0.0834827 11.1691 0.403558 10.7462L0.51025 10.625L10.1189 1.20529C10.5492 0.78343 11.2469 0.78343 11.6773 1.20529Z"
              fill="white"
            />
          </svg>
        </router-link>
        <h1 class="text-xl font-medium text-center w-full">Profile</h1>
      </nav>
      <Profile />
    </header>

    <div
      class="relative shadow bg-white rounded-md mx-auto w-11/12 px-6 py-4 -mt-12 cursor-pointer"
    >
      <div class="flex justify-between items-center">
        <div class="flex items-center">
          <img src="../assets/icon/angpao.svg" alt="Icon" />
          <div class="flex flex-col ml-5">
            <p class="text-sm font-medium text-gray-500">Angpao yang didapat</p>
            <h1 class="font-extrabold text-2xl">12</h1>
          </div>
        </div>
        <div>
          <img src="../assets/icon/next.png" alt="Next" />
        </div>
      </div>
    </div>

    <main class="px-4 md:px-5 pb-20">
      <section class="mt-6 divide-y divide-gray-200">
        <div class="flex justify-between items-center pb-5">
          <div class="flex items-center">
            <div
              class="rounded-full w-10 h-10 bg-red-100 flex justify-center items-center"
            >
              <svg
                width="20"
                height="18"
                viewBox="0 0 20 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M15.2882 5.68332H19.1667C19.1667 2.56921 17.3008 0.75 14.1393 0.75H5.86075C2.69927 0.75 0.833344 2.56921 0.833344 5.6436V12.3564C0.833344 15.4308 2.69927 17.25 5.86075 17.25H14.1393C17.3008 17.25 19.1667 15.4308 19.1667 12.3564V12.0704H15.2882C13.4881 12.0704 12.0289 10.6477 12.0289 8.89275C12.0289 7.13778 13.4881 5.71509 15.2882 5.71509V5.68332ZM15.2882 7.04971H18.4822C18.8602 7.04971 19.1667 7.34848 19.1667 7.71702V10.0367C19.1623 10.4035 18.8584 10.6997 18.4822 10.704H15.3615C14.4502 10.716 13.6534 10.1077 13.4467 9.2423C13.3432 8.7051 13.4885 8.15077 13.8437 7.72787C14.1988 7.30496 14.7276 7.05674 15.2882 7.04971ZM15.4267 9.48856H15.7282C16.1152 9.48856 16.4289 9.18269 16.4289 8.80537C16.4289 8.42805 16.1152 8.12217 15.7282 8.12217H15.4267C15.2416 8.12005 15.0633 8.19025 14.9317 8.31712C14.8 8.44398 14.7259 8.61695 14.7259 8.79742C14.7259 9.17605 15.0384 9.48421 15.4267 9.48856ZM5.17631 5.68332H10.3504C10.7374 5.68332 11.0511 5.37744 11.0511 5.00012C11.0511 4.6228 10.7374 4.31692 10.3504 4.31692H5.17631C4.79246 4.3169 4.48003 4.61796 4.47557 4.99218C4.47554 5.3708 4.78798 5.67897 5.17631 5.68332Z"
                  fill="#FE2929"
                />
              </svg>
            </div>
            <div class="ml-4">
              <p class="text-sm text-gray-400 font-medium">Saldo</p>
              <h1 class="font-extrabold text-base">Rp 107.000</h1>
            </div>
          </div>
          <button
            class="focus:outline-none focus:ring-4 focus:ring-yellow-200 transition my-auto rounded font-bold text-sm px-6 py-2 text-gray-900 bg-yellow-400 hover:bg-yellow-500"
          >
            Top Up
          </button>
        </div>
        <div class="flex justify-between items-center py-5">
          <div class="flex items-center">
            <div
              class="rounded-full w-10 h-10 bg-red-100 flex justify-center items-center"
            >
              <svg
                width="20"
                height="18"
                viewBox="0 0 20 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M14.5278 0.750031C15.757 0.750031 16.9395 1.23586 17.8095 2.10761C18.6803 2.97753 19.167 4.15086 19.167 5.3792V12.6209C19.167 15.1784 17.0862 17.25 14.5278 17.25H5.47204C2.91363 17.25 0.83371 15.1784 0.83371 12.6209V5.3792C0.83371 2.8217 2.90446 0.750031 5.47204 0.750031H14.5278ZM15.9862 6.74503L16.0595 6.6717C16.2786 6.40586 16.2786 6.02086 16.0495 5.75503C15.922 5.61845 15.747 5.53503 15.5645 5.5167C15.372 5.50661 15.1887 5.5717 15.0503 5.70003L10.917 9.00003C10.3854 9.44095 9.62363 9.44095 9.08371 9.00003L4.95871 5.70003C4.67363 5.4892 4.27946 5.5167 4.04204 5.7642C3.79454 6.0117 3.76704 6.40586 3.97696 6.68086L4.09704 6.80003L8.26788 10.0542C8.78121 10.4575 9.40363 10.6775 10.0554 10.6775C10.7053 10.6775 11.3387 10.4575 11.8511 10.0542L15.9862 6.74503Z"
                  fill="#FE2929"
                />
              </svg>
            </div>
            <div class="ml-4">
              <p class="text-sm text-gray-400 font-medium">Email</p>
              <h1 class="font-bold text-base">richard@gmail.com</h1>
            </div>
          </div>
        </div>
        <div class="flex justify-between items-center py-5">
          <div class="flex items-center">
            <div
              class="rounded-full w-10 h-10 bg-red-100 flex justify-center items-center"
            >
              <svg
                width="20"
                height="20"
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M15.1388 11.9831C14.5791 11.8627 14.1363 12.1226 13.7442 12.3496C13.3426 12.5835 12.5791 13.2029 12.1414 13.0443C9.90071 12.1218 7.79325 10.1605 6.88096 7.91079C6.72017 7.46379 7.33668 6.69541 7.56883 6.28912C7.79411 5.89583 8.04862 5.44884 7.93254 4.88489C7.82764 4.37812 6.47082 2.65163 5.99103 2.17951C5.67461 1.86766 5.35045 1.69613 5.0177 1.66841C3.76664 1.6147 2.3694 3.28402 2.12435 3.68337C1.51043 4.53492 1.51387 5.668 2.13467 7.04192C3.63078 10.7322 9.28936 16.3015 12.9935 17.8539C13.6771 18.1736 14.3022 18.3338 14.8637 18.3338C15.4131 18.3338 15.9024 18.1805 16.3228 17.8764C16.6401 17.6936 18.3778 16.227 18.3323 14.9423C18.3047 14.6149 18.1336 14.2874 17.8258 13.9704C17.3572 13.4861 15.6418 12.0888 15.1388 11.9831Z"
                  fill="#FE2929"
                />
              </svg>
            </div>
            <div class="ml-4">
              <p class="text-sm text-gray-400 font-medium">Phone</p>
              <h1 class="font-bold text-base">0812 2492 3912</h1>
            </div>
          </div>
        </div>
        <div class="flex justify-between items-center py-5">
          <div class="flex items-center">
            <div
              class="rounded-full w-10 h-10 bg-red-100 flex justify-center items-center"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M3.5 10.3178C3.5 5.71792 7.34388 2.00003 11.9934 2.00003C16.6561 2.00003 20.5 5.71792 20.5 10.3178C20.5 12.6357 19.657 14.7877 18.2695 16.6116C16.7388 18.6235 14.8522 20.3765 12.7285 21.7525C12.2425 22.0704 11.8039 22.0944 11.2704 21.7525C9.13474 20.3765 7.24809 18.6235 5.7305 16.6116C4.34198 14.7877 3.5 12.6357 3.5 10.3178ZM9.19423 10.5768C9.19423 12.1177 10.4517 13.3297 11.9934 13.3297C13.5362 13.3297 14.8058 12.1177 14.8058 10.5768C14.8058 9.04783 13.5362 7.77686 11.9934 7.77686C10.4517 7.77686 9.19423 9.04783 9.19423 10.5768Z"
                  fill="#FE2929"
                />
              </svg>
            </div>
            <div class="ml-4">
              <p class="text-sm text-gray-400 font-medium">Location</p>
              <h1 class="font-bold text-base">Pontianak, Indonesia</h1>
            </div>
          </div>
        </div>
      </section>
    </main>

    <Footer></Footer>
  </div>
</template>

<script>
export default {
  components: {
    Footer: () => import("@/components/Footer.vue"),
    Profile: () => import("@/components/Profile.vue"),
  },
};
</script>
