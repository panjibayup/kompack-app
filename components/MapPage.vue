<template>
  <section id="map" class="map">
    <div class="container">
      <div class="title-map text-center">
        <h2 class="text-map">Lokasi Gudang</h2>
      </div>
      <div class="deskripsi">
        <p class="text-deskripsi text-center">
          Kompack bekerja sama dengan pemilik gudang yang tersebar di seluruh Indonesia untuk menjadi Mitra Gudang Kompack dengan tujuan memberdayakan bisnis pergudangan di Indonesia dengan prinsip profesional dan menguntungkan.
        </p>
      </div>
      <div class="text-center">
        <img class="img-map" src="../assets/map.6cc792c.svg" alt="map" />
      </div>
    </div>
  </section>
</template>
<style scoped>
.container {
  padding: 0 50px;
}
.map {
  background-color: #dff3ff;
  padding-top: 5%;
  padding-bottom: 5%;
}
img.img-map {
  width: 60%;
}
img.img-map:hover {
  align-items: center;
  cursor: pointer;
  width: 90%;
  height: 300px;
  transition: height 0.3s ease;
  transition-duration: 0.3s;
  transition-timing-function: ease;
  transition-delay: 0s;
  transition-property: height;
}
.text-map {
  font-weight: 600;
  line-height: 140%;
  padding-bottom: 30px;
  font-size: 28px;
}
.text-deskripsi {
  color: #626262;
  font-size: 16px;
}
@media (max-width: 767.98px) {
  .text-center img {
    width: 100%;
  }
  .text-deskripsi {
    font-size: 14px;
    margin-top: -20px;
  }
}
</style>
