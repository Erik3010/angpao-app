<template>
  <div>
    <header class="relative px-6 pt-10 pb-6 h-44 primary-gradient text-white">
      <img
        class="absolute left-0 top-0 select-none pointer-events-none"
        src="../assets/decoration/home-deco2.png"
      />
      <img
        class="absolute right-0 top-0 w-42 select-none pointer-events-none"
        src="../assets/decoration/home-deco.png"
      />
      <div class="h-full flex flex-col justify-between">
        <router-link to="/">
          <svg
            width="12"
            height="22"
            viewBox="0 0 12 22"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M11.6773 1.20529C12.0685 1.5888 12.104 2.18894 11.784 2.61184L11.6773 2.73299L2.8474 11.3889L11.6773 20.0448C12.0685 20.4283 12.104 21.0284 11.7839 21.4513L11.6773 21.5725C11.2861 21.956 10.6739 21.9909 10.2425 21.6771L10.1189 21.5725L0.51025 12.1527C0.119047 11.7692 0.0834827 11.1691 0.403558 10.7462L0.51025 10.625L10.1189 1.20529C10.5492 0.78343 11.2469 0.78343 11.6773 1.20529Z"
              fill="#fff"
            />
          </svg>
        </router-link>
        <div>
          <p class="font-medium text-xs opacity-90 mb-1">
            Hore Kamu Dapat angpao nih!
          </p>
          <h1 class="text-3xl font-bold">Angpao dari Budi</h1>
        </div>
      </div>
    </header>
    <main class="bg-gray-50 px-4 h-screen">
      <section class="mt-3">
        <h1 class="block py-4 font-bold text-xl">Informasi Pengirim</h1>
        <article class="bg-white p-6 rounded-lg">
          <div class="flex justify-between items-center">
            <div class="flex items-center w-full">
              <div class="w-2/12">
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
                      d="M17.294 7.29105C17.294 10.2281 14.9391 12.5831 12 12.5831C9.0619 12.5831 6.70601 10.2281 6.70601 7.29105C6.70601 4.35402 9.0619 2 12 2C14.9391 2 17.294 4.35402 17.294 7.29105ZM12 22C7.66237 22 4 21.295 4 18.575C4 15.8539 7.68538 15.1739 12 15.1739C16.3386 15.1739 20 15.8789 20 18.599C20 21.32 16.3146 22 12 22Z"
                      fill="#FE2929"
                    />
                  </svg>
                </div>
              </div>
              <div class="ml-2 w-10/12">
                <p class="text-sm text-gray-400 font-medium">Saldo</p>
                <h1 class="font-extrabold text-base">Rp 107.000</h1>
              </div>
            </div>
          </div>
          <div class="w-full flex">
            <div class="w-2/12 mr-2"></div>
            <div class="my-5 w-10/12 border-b border-gray-200"></div>
          </div>
          <div class="flex justify-between items-center">
            <div class="flex items-center w-full">
              <div class="w-2/12">
                <div
                  class="rounded-full w-10 h-10 bg-red-100 flex justify-center items-center"
                >
                  <svg
                    width="23"
                    height="23"
                    viewBox="0 0 23 23"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M11.1628 20.4652C6.02792 20.4652 1.86047 16.3071 1.86047 11.1629C1.86047 6.028 6.02792 1.86056 11.1628 1.86056C16.307 1.86056 20.4651 6.028 20.4651 11.1629C20.4651 16.3071 16.307 20.4652 11.1628 20.4652ZM14.1302 14.614C14.2419 14.6792 14.3628 14.7164 14.493 14.7164C14.7256 14.7164 14.9581 14.5954 15.0884 14.3722C15.2837 14.0466 15.1814 13.6187 14.8465 13.414L11.5349 11.442V7.14428C11.5349 6.75358 11.2186 6.4466 10.8372 6.4466C10.4558 6.4466 10.1395 6.75358 10.1395 7.14428V11.842C10.1395 12.0838 10.2698 12.3071 10.4837 12.4373L14.1302 14.614Z"
                      fill="#FE2929"
                    />
                  </svg>
                </div>
              </div>
              <div class="ml-2 w-10/12">
                <p class="text-sm text-gray-400 font-medium">Tanggal Dikirim</p>
                <h1 class="font-extrabold text-base">12 Febuari 2021, 12:03</h1>
              </div>
            </div>
          </div>
        </article>
      </section>
      <section class="pt-3 pb-20">
        <h1 class="block py-4 font-bold text-xl">Isi Angpao</h1>
        <article class="bg-white p-6 rounded-lg">
          <div class="flex justify-between items-center">
            <div class="flex items-center w-full">
              <div class="w-2/12">
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
              </div>
              <div class="ml-2 w-10/12">
                <p class="text-sm text-gray-400 font-medium">Nominal</p>
                <h1 class="font-extrabold text-base">Rp 500.000</h1>
              </div>
            </div>
          </div>
          <div class="w-full flex">
            <div class="w-2/12 mr-2"></div>
            <div class="my-5 w-10/12 border-b border-gray-200"></div>
          </div>
          <div class="flex justify-between items-center">
            <div class="flex items-start w-full">
              <div class="w-2/12">
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
              </div>
              <div class="ml-2 w-10/12">
                <p class="text-sm text-gray-400 font-medium">Pesan</p>
                <h1 class="font-medium leading-relaxed text-sm">
                  Gong Xi Fa Cai! Cum neque id in mattis iaculis et arcu lorem
                  massa. Eget donec eleifend et dolor felis.
                </h1>
              </div>
            </div>
          </div>
        </article>
      </section>
      <div class="fixed bottom-6 left-1/2 transform -translate-x-1/2">
        <button
          class="bg-red-600 hover:bg-red-700 text-white w-80 py-4 text-base rounded-lg focus:outline-none focus:ring-4 focus:ring-red-300 transition duration-300"
        >
          Ucapkan Terima Kasih
        </button>
      </div>
    </main>
  </div>
</template>

<script>
export default {};
</script>
