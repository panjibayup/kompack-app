<template>
  <section id="layanan" class="layanan" data-aos="fade-left" data-aos-duration="1000">
    <div>
      <div id="accordionFlushExample" class="row accordion accordion-flush justify-content-between">
        <div class="col-xl-6 col-lg-6 col-md-6 col-12 p-4 mobile-layanan">
          <div class="col-lg-7 col-md-7 col-7 head-layanan">
            <h2>Layanan Kami</h2>
          </div>
          <div class="row accordion-item row-layanan">
            <div id="flush-headingOne" class="col-lg-11 col-11 accordion-header subhead-layanan">
              <div type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne" class="row accordion-button justify-content-between custom__class collapsed">
                <div class="col-md-6 col-10">
                  <div class="ps-3">Penyimpanan</div>
                </div>
              </div>
            </div>
            <div id="flush-collapseOne" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample" class="col-lg-11 col-11 content-layanan accordion-collapse collapse">
              <p class="accordion-body">Kami menerapkan SOP untuk menyimpan dan menjamin keamanan barangmu</p>
            </div>
          </div>
          <div class="row accordion-item row-layanan">
            <div id="flush-headingTwo" class="col-lg-11 col-11 accordion-header subhead-layanan">
              <div type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo" class="row accordion-button justify-content-between custom__class collapsed">
                <div class="col-md-10 col-10">
                  <div class="ps-3">Management Stock</div>
                </div>
              </div>
            </div>
            <div id="flush-collapseTwo" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample" class="col-lg-11 col-11 content-layanan accordion-collapse collapse">
              <p class="accordion-body">Pemantauan jumlah barang lebih mudah dengan laporan yang selalu kami update</p>
            </div>
          </div>
          <div class="row accordion-item row-layanan">
            <div id="flush-headingThree" class="col-lg-11 col-11 accordion-header subhead-layanan">
              <div type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree" class="row accordion-button collapsed justify-content-between custom__class">
                <div class="col-md-10 col-10">
                  <div class="ps-3">Pengemasan dan pengiriman</div>
                </div>
              </div>
            </div>
            <div id="flush-collapseThree" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample" class="col-lg-11 col-11 content-layanan accordion-collapse collapse">
              <p class="accordion-body">Kami bantu kemas dan kirimkan barang melalui ekspedisi sesuai pilihanmu</p>
            </div>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6 col-md-6 d-none d-md-block p-4 img-layanan" style="width: 45%; padding-top: 10vh">
          <img id="flush-collapseOne" src="../assets/penyimpanan.8734f2a.png" alt="layanan" class="accordion-collapse collapse" />
          <img id="flush-collapseTwo" src="../assets/stock.e0c69b6.png" alt="stock" class="accordion-collapse collapse" />
          <img id="flush-collapseThree" src="../assets/packing.1e23c4f.png" alt="packing" class="accordion-collapse collapse" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import aosMixin from "../mixins/aos";
export default {
  name: "PageIndex",
  mixins: [aosMixin],
};
</script>

<style scoped>
.layanan {
  text-align: left;
  margin: 100px auto;
}
.mobile-layanan {
  background-color: #edf8ff;
  border-radius: 10px;
}
.head-layanan {
  padding-bottom: 5px;
  margin-bottom: 5px;
  border-bottom: solid 1px #4285f4;
  padding-left: 20px;
  font-weight: 600;
}
.head-layanan h2 {
  font-weight: 500;
}
.row-layanan {
  border: 0;
  background: 0 0;
  padding: 0 20px;
}

.subhead-layanan {
  background-color: #4285f4;
  color: #fff;
  border-radius: 20px;
  margin: 10px 0 10px 0;
  border: none;
}
.custom__class {
  background: 0 0;
  color: #fff;
  padding: 30px 0 30px 0;
}
.content-layanan {
  background-color: #fff;
  color: #4285f4;
  border-radius: 20px;
  margin-top: -20px;
  margin-bottom: 1rem;
  border-bottom-right-radius: 20px;
  border-bottom-left-radius: 20px;
  border: none;
  height: 80px;
}
.img-layanan img {
  max-width: 90%;
}
@media (max-width: 991.98px) {
  .content-layanan {
    font-style: 11px;
    height: 100px;
  }
}
</style>
