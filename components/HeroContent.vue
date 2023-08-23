<template>
  <div class="pt-24">
    <div
      class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center"
    >
      <!--Left Col-->
      <div
        class="flex flex-col w-full md:w-2/5 justify-center items-start text-center md:text-left"
      >
        <p class="uppercase tracking-loose w-full">What business are you?</p>
        <h1 class="my-4 text-5xl font-bold leading-tight">
        Muhamad Rafliansyah
        </h1>
        <p class="leading-normal text-2xl mb-8">
          Saya merupakan Mahasiswa Fakultas Teknik Informatika universitas Pasundan Bandung angkatan 2020, Usia saya 17 tahun, Sambil menjalani kuliah Saya memiliki 2 Bidang Business kecil Online maupun offline dengan nama RFMP & RFST.
        </p>

        <button
          class="mx-auto lg:mx-0 hover:underline bg-white text-gray-800 font-bold rounded-full my-6 py-4 px-8 shadow-lg"
        >
          Contact
        </button>
      </div>
      <!--Right Col-->
      <div class="w-full md:w-3/5 py-6 text-center">
      <img class="w-full md:w-4/5 z-50 float-right" src="~/assets/img/RF2.png" alt />
     </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroContent'
}
</script>
