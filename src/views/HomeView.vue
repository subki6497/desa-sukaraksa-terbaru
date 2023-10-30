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
      <p class="text-3xl font-semibold">Visi & Misi Desa Sukaraksa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Maju dan Sejahtera Bersama Rakyat”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Meningkatkan Pembangunan Infrastruktur yang Profesional dan berkelanjutan;
        </li>
        <li>
          2. Menyelenggarakan pendidikan melalui pelatihan secara periodik;
        </li>
        <li>
          3. Menjadikan Desa pengiringan yang cerdas, maju, mandiri dan sejahtera;
        </li>
        <li>
          4. Peduli terhadap kepentingan masyarakat dan lingkungan;
        </li>
        <li>
          5. Membina dan memantapkankehidupan gotong royongsebagai basis dan
          modal dasar pembangunan desa, yang pada hakikatnyajuga merupakan
          karakter dasar dari masyarakat desa dan juga bangsa Indonesia.
        </li>
      </ul>
       <p class="text-lg font-semibold">Misi</p>
      <ul>

      
       
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
