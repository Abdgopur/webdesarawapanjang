<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />
  <main class="flex">
    <Sidebar />
    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <h1>VISI</h1>
      <p>
        Berdasarkan perkembangan situasi dan kondisi Desa Rawapanjang saat ini, dan terkait dengan Rencana Pembangunan Jangka Menengah Desa (RPJM-Desa), maka untuk pembangunan Desa Rawapanjang pada periode 6 (Enam) tahun ke depan (tahun
        2021-2027), disusun visi sebagai berikut :
      </p>
      <br />
      <p>“ Rawapanjang Berkah ( Bersih, Kuat dan Sejahtera ) ”</p>
      <br />
      <p>
        Dengan penjelasan sebagai berikut : 1. Bersih, mempunyai tujuan yaitu menjadikan Pemerintahan Desa yang bersih dari korupsi, kolusi dan nepotisme (KKN) dengan dipublikasikannya keuangan desa untuk adanya tranparansi serta membuka
        ruang pubik/Taman ramah lingkungan dengan fasilitas internet gratis untuk masyarakat Desa Rawapanjang. 2. Kuat, mempunyai tujuan yaitu menjadikan desa yang agamis, memliliki kantor desa modern, desa sehat, pelayanan online,
        pengembangan dan pemberdayaan UMKM, betonisasi jalan desa dan drainase, desa terang, fasilitas olahraga dan seni. 3. Sejahtera, mempunyai tujuan yaitu menjadikan desa yang bebas banjir, peningkatan kesejahteraan masyarakat,
        mengurangi pengangguran, memberikan beasiswa / santunan , peduli jompo dan lansia, menciptakan desa wisata, desa literasi, desa ramah anak dan pendidikan.
      </p>
      <br />
      <h1>MISI</h1>
      <p>Untuk mewujudkan visi tersebut, maka misi yang akan dilakukan adalah sebagai berikut :</p>
      <li>“RAWAPANJANG BERSIH”</li>
      <li>“RAWAPANJANG KUAT”</li>
      <li>“RAWAPANJANG SEJAHTERA”</li>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/SOTK pemdes.jpeg" alt="" />
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
