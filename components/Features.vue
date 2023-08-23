<template>
  <section class="bg-white border-b py-8">
    <div class="container max-w-5xl mx-auto m-8">
      <h1
        class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800"
      >
        RFMP & RFST
      </h1>
      <div class="w-full mb-4">
        <div
          class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"
        ></div>
      </div>
      <feature-right
        headline="RFMerahPutih"
        content="Business pertama saya bergerak pada bidang penjualan Bendera Merah Putih dan perlengkapan untuk memperingati hari jadi Indonesia,Saya melakukan penjualan melalui offline dan online,Melayani pemesanan untuk grosir dan ecer untuk grosir S&K Berlaku,Siap Melakukan Pengiriman barang keseluruh indonesia."
      >
        <img src="~assets/img/RF.jpg" alt slot="svg" />
      </feature-right>
      
      <feature-left
        headline="RFSinarTerang"
        content="Business kedua saya bergerak pada bidang perlengkapan elektronik,Saya melakukan penjualan melalui offline dengan lokasi toko di Garut Melayani pebelian ecer ataupun grosir,dengan berjalannya waktu pada tahun ini saya akan Membuka toko online pada setiap marketplace dan Siap melakukan pengiriman keseluruh indonesia."
      >
        <img src="~assets/img/RFCT.png" alt slot="svg"/>
      </feature-left>
    </div>
  </section>
</template>

<script>
import FeatureRight from '@/components/FeatureRight'
import FeatureLeft from '@/components/FeatureLeft'

export default {
  name: 'Features',
  components: {
    'feature-right': FeatureRight,
    'feature-left': FeatureLeft
  }
}
</script>
