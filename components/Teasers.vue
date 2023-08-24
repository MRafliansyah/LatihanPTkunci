<template>
  <section class="bg-white border-b py-8">
    <div class="container mx-auto flex flex-wrap pt-4 pb-12">
      <h1
        class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800"
      >
        Product
      </h1>
      <div class="w-full mb-4">
        <div
          class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"
        ></div>
      </div>
      <teaser-column :rows="4" action="Action">
        <template v-slot:overline>RFMP</template>
        <template v-slot:headline>RFMerahPutih</template>
        <template v-slot:content
          >Business pertama saya bergerak pada bidang penjualan Bendera Merah Putih dan perlengkapan untuk memperingati hari jadi Indonesia,Saya melakukan penjualan melalui offline dan online,Melayani pemesanan untuk grosir dan ecer untuk grosir S&K Berlaku,Siap Melakukan Pengiriman barang keseluruh indonesia.</template
        >
      </teaser-column>
      <div class="w-full md:w-1/5 py-6 text-center">
  <img class="w-full md:w-4/5 z-50 mb-4" src="~/assets/img/mp1.jpg" alt />
  <img class="w-full md:w-4/5 z-50" src="~/assets/img/mp6.jpg" alt />
</div>


      <teaser-column :rows="4" action="Action">
        <template v-slot:overline>RFMP</template>
        <template v-slot:headline>RFMerahPutih</template>
        <template v-slot:content
          >Business pertama saya bergerak pada bidang penjualan Bendera Merah Putih dan perlengkapan untuk memperingati hari jadi Indonesia,Saya melakukan penjualan melalui offline dan online,Melayani pemesanan untuk grosir dan ecer untuk grosir S&K Berlaku,Siap Melakukan Pengiriman barang keseluruh indonesia.</template
        >
      </teaser-column>
      <div class="w-full md:w-1/5 py-6 text-center">
  <img class="w-full md:w-4/5 z-50 mb-4" src="~/assets/img/mp3.jpg" alt />
  <img class="w-full md:w-4/5 z-50" src="~/assets/img/mp2.jpg" alt />
</div>


      
      <teaser-column :rows="4" action="Action">
        <template v-slot:overline>RFMP</template>
        <template v-slot:headline>RFMerahPutih</template>
        <template v-slot:content
          >Business pertama saya bergerak pada bidang penjualan Bendera Merah Putih dan perlengkapan untuk memperingati hari jadi Indonesia,Saya melakukan penjualan melalui offline dan online,Melayani pemesanan untuk grosir dan ecer untuk grosir S&K Berlaku,Siap Melakukan Pengiriman barang keseluruh indonesia.</template
        >
      </teaser-column>
     <div class="w-full md:w-1/5 py-6 text-center">
  <img class="w-full md:w-4/5 z-50 mb-4" src="~/assets/img/mp4.jpg" alt />
  <img class="w-full md:w-4/5 z-50" src="~/assets/img/mp5.jpg" alt />
</div>

     
     
      <teaser-column :rows="4" action="Action">
        <template v-slot:overline>RFST</template>
        <template v-slot:headline>RFSinarTerang</template>
        <template v-slot:content
          >Business kedua saya bergerak pada bidang perlengkapan elektronik,Saya melakukan penjualan melalui offline dengan lokasi toko di Garut Melayani pebelian ecer ataupun grosir,dengan berjalannya waktu pada tahun ini saya akan Membuka toko online pada setiap marketplace dan Siap melakukan pengiriman keseluruh indonesia.</template
        >
      </teaser-column>
      <div class="w-full md:w-1/5 py-6 text-center">
  <img class="w-full md:w-4/5 z-50 mb-4" src="~/assets/img/12.png" alt />
  <img class="w-full md:w-4/5 z-50" src="~/assets/img/13.png" alt />
</div>

     
    </div>
  </section>
</template>

<script>
import TeaserColumn from '@/components/TeaserColumn'

export default {
  name: 'Teasers',
  components: {
    'teaser-column': TeaserColumn
  }
}
</script>
