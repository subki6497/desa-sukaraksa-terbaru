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
      <p class="text-3xl font-semibold">Visi dan Misi Desa Sukaraksa</p>
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
          5. Membina dan memantapkan kehidupan gotong royong sebagai basis dan
          modal dasar pembangunan desa, yang pada hakikatnya juga merupakan
          karakter dasar dari masyarakat desa dan juga bangsa Indonesia.
        </li>
        </ul>
        
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
section {
    padding: 10px 30px;
    margin: 10px 0px;
    background: #fff;
    border-bottom: 1px solid #ccc;
    display: table;
    margin-left: 50px;
    margin-right: 50px;
    max-width: 1500px;
}

.beranda{
    border-width: thick; 
    border-style: solid;  
    border-color: orange;
    border-radius: 45px;
    padding: 40px 10px;
    display: table;
    
  
}

.foto, .konten-beranda{

    vertical-align: middle;
   
    display: table-cell;
    margin: 30px;
    padding: 30px;
    max-width: 600px;
    word-wrap: break-word;
    white-space:pre-wrap;
    text-align: left;
}

.konten-beranda p{
  text-align: left;
}

.beranda img{
    height: 350px;
    width: 600px;
}

.button-like {
    background-color: #f85246;
    border: none;
    border-radius: 15px;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
  }

  .button-like:hover{
    background-color: #f17c74;
  }

  .button {
    background-color: #2db63f; /* Green */
    border: none;
    border-radius: 15px;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
  }

  .button:hover{
    background-color: #73e282;
  }
