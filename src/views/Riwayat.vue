<template>
  <div>
    <header class="bg-white text-gray-900 flex items-center shadow">
      <nav class="relative px-5 py-6 w-full">
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
              fill="#201D1D"
            />
          </svg>
        </router-link>
        <h1 class="text-xl font-semibold text-center w-full">Riwayat</h1>
      </nav>
    </header>
    <main class="bg-gray-50 py-6 px-4 h-screen">
      <section class="overflow-x-auto py-2 px-1">
        <FilterSection
          @changeFilter="changeFilter"
          :activeFilter="activeFilter"
          :filters="filters"
        />
      </section>
      <section class="mt-6 space-y-4">
        <HistoryList
          v-for="(history, index) in histories"
          :key="index"
          :history="history"
        />
      </section>
    </main>
    <Footer></Footer>
  </div>
</template>

<script>
export default {
  components: {
    Footer: () => import("@/components/Footer.vue"),
    FilterSection: () => import("@/components/FilterSection.vue"),
    HistoryList: () => import("@/components/HistoryList.vue"),
  },
  data() {
    return {
      filters: ["Semua", "Masuk", "Keluar"],
      activeFilter: 0,
      histories: [
        {
          desc: "Mendapat Angpao",
          user: "John Doe",
          type: "angpao",
          date: "Hari Ini",
        },
        {
          desc: "Melakukan Top Up",
          user: "Anda",
          type: "top_up",
          date: "8 Feb 2021",
        },
        {
          desc: "Mendapat Angpao",
          user: "John Doe",
          type: "angpao",
          date: "7 Feb 2021",
        },
      ],
    };
  },
  methods: {
    changeFilter(param) {
      this.activeFilter = param;
    },
  },
};
</script>
