<template>
  <div>
    <HeaderHome
      title="Welcome Erik"
      tagline="Bagikan angpao ke keluarga dan teman-temanmu"
    />
    <Saldo />

    <main class="px-4 md:px-5 pb-20">
      <section class="mt-5">
        <SectionTitle
          title="Promo"
          tagline="Cari tahu tentang promo kami disini yuk"
        />
        <Banner />
      </section>

      <section class="mt-8">
        <SectionTitle
          class="sm:mb-0 mb-3"
          title="Angpao yang diterima"
          tagline="Ayo cek berapa angpao yang kamu terima"
          :viewMore="true"
        />
        <div>
          <TransactionList
            v-for="t in transaction"
            :key="t.title"
            :transaction="t"
          />
        </div>
      </section>
    </main>

    <Footer></Footer>
  </div>
</template>

<script>
export default {
  components: {
    HeaderHome: () => import("@/components/HeaderHome.vue"),
    Saldo: () => import("@/components/Saldo.vue"),
    Banner: () => import("@/components/Banner.vue"),
    TransactionList: () => import("@/components/TransactionList.vue"),
    Footer: () => import("@/components/Footer.vue"),
    SectionTitle: () => import("@/components/SectionTitle.vue"),
  },
  data() {
    return {
      transaction: [
        {
          title: "Anda mendapat angpao dari Budi",
          date: "12 JAN 2021, 12:03",
        },
        {
          title: "Anda mendapat angpao dari John Doe",
          date: "12 JAN 2021, 12:03",
        },
      ],
    };
  },
};
</script>
