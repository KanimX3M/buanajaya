<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa Buanajaya</p>
      <p class="text-lg font-semibold mt-3">VISI</p>
      <p class="text-lg font-semibold">"TERWUJUDNYA PELAYANAN PUBLIK YANG TRANSPARAN,AKUNTABILITAS MENUJU MASYARAKAT DESA BUANAJAYA YANG MAJU,AMAN,BERTAQWA MENUJU SEJAHTERA"</p>
      <p class="text-lg font-semibold mt-3">MISI</p>
      <ul></ul>
      <li>1. Meningkatkan Sumber Daya Manusia,Kualitas Dan Kuantitas Remaja Mesjid,Santriawan Dan Santriwati Untuk Kemakmuran Mesjid Dan Tempat-Tempat Ibadah</li>
      <li>2. Program Peningkatan Kualitas SDM,TPA,PAUD Dan TK </li>
      <li>3. Memberi Insentif Guru /Ustadz Pada Lembaga Pendidikan Madrasah Diniah , TPA dan PAUD </li>
      <li>4. Menyediakan Transfportasi Ambulan Desa </li>
      <li>5. Memberdayakan Potensi Yang Ada Di Masyarakat </li>
      <li>6. Melanjutkan Program Pemerintah Desa Buanajaya, Periode Lalu Sebagaimana Tercantum Dalam RPJMDesa, Desa Buanajaya</li>
      <p class="text-3xl font-semibold my-4">Struktur Desa Buanajaya</p>
      <img src="@/assets/struktur-Desa-Buanajaya.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
