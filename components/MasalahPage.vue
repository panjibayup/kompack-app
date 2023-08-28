<template>
  <section id="section-2" class="mt-5" data-aos="fade-up" data-aos-duration="1000">
    <div class="row justify-content-center">
      <div class="container">
        <div class="row sect-2">
          <div class="col-xl-12">
            <h2 class="mt-5 fw-semibold text-center">
              Apakah kamu <br />
              mengalami masalah ini?
            </h2>
          </div>

          <div class="row justify-content-center mt-5 px-4 justify-content-center">
            <div class="col-lg-5 col-md-6 ms-4 pt-3 conten-sect2" data-aos="fade-right" data-aos-duration="1000">
              <div class="row mt-2 justify-content-center">
                <div class="col-lg-2 col-md-2 me-2">
                  <img src="../assets/home.0f137a7.png" alt="rumah" />
                </div>
                <div class="col-lg-8 col-md-9 col-10 sub subhead-sect2">
                  <p class="text-start pb-2">Keterbatasan tempat dan biaya dalam menyediakan fasilitas gudang sendiri</p>
                </div>
              </div>
            </div>
            <div class="col-lg-5 col-md-6 ms-4 pt-3 conten-sect2" data-aos="fade-left" data-aos-duration="1000">
              <div class="row mt-2 justify-content-center">
                <div class="col-lg-2 col-md-2 me-2">
                  <img src="../assets/jam.60da5ff.png" alt="jam" />
                </div>
                <div class="col-lg-8 col-md-8 col-8 subhead-sect2">
                  <p class="text-start pb-2">Tidak cukup waktu dalam mengurus penyimpanan hingga pengemasan barang</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section id="section-3">
    <div class="head-sect3" data-aos="fade-down" data-aos-duration="1000">
      <h2 class="fw-semibold text-center">Mengapa harus Kompack?</h2>
    </div>
    <div class="row justify-content-center d-none d-md-flex row-sect3 mt-5 pe-5">
      <div class="col-xl-3 col-lg-3 col-md-4 col-12" data-aos="fade-up-right" data-aos-duration="1000">
        <div class="conten-sect3 py-3">
          <img class="image-sect3" src="../assets/practis.584a411.svg" alt="praktis" />
          <h4 class="pt-3 text-center">Praktis</h4>
          <p class="p-1 desc-sect3">PRAKTIS karena semua urusan pergudanganmu, kami yang tangani</p>
        </div>
      </div>
      <div class="col-xl-3 col-lg-3 col-md-4 col-12" data-aos="fade-up" data-aos-duration="1000">
        <div class="conten-sect3 py-3">
          <img class="image-sect3" src="../assets/hemat.b3a6bae.svg" alt="hemat" />
          <h4 class="pt-3 text-center judul-sect3">Hemat</h4>
          <p class="p-1 desc-sect3">HEMAT karena semua biaya sudah jadi satu paket dan dibebankan hanya pada setiap pengiriman</p>
        </div>
      </div>
      <div class="col-xl-3 col-lg-3 col-md-4 col-12" data-aos="fade-up-left" data-aos-duration="1000">
        <div class="conten-sect3 py-3">
          <img class="mt-4 mudah" src="../assets/mudah.4bdacb6.svg" alt="mudah" />
          <h4 class="pt-3 text-center">Mudah</h4>
          <p class="p-1 desc-sect3">MUDAH DIJANGKAU karena gudang kami berada di lokasi strategis</p>
        </div>
      </div>
    </div>
    <div class="row justify-content-center d-block d-md-none row-sect3 mt-5">
      <div class="col-xl-3 col-lg-3 col-md-4 col-12 px-5 mb-5" data-aos="fade-up-right" data-aos-duration="1000">
        <div class="card rounded-4 shadow border-none px-3">
          <div class="card-body justify-content-center">
            <img class="w-25 position-absolute top-0 start-40 translate-middle" src="../assets/practis.584a411.svg" alt="praktis" />
            <h4 class="text-center">Praktis</h4>
            <p class="text-center">PRAKTIS karena semua urusan pergudanganmu, kami yang tangani</p>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-lg-3 col-md-4 col-12 px-5 mb-5" data-aos="fade-up-left" data-aos-duration="1000">
        <div class="card rounded-4 shadow border-none px-3">
          <div class="card-body justify-content-center">
            <img class="w-25 position-absolute top-0 start-40 translate-middle" src="../assets/hemat.b3a6bae.svg" alt="praktis" />
            <h4 class="text-center">Hemat</h4>
            <p class="text-center">HEMAT karena semua biaya sudah jadi satu paket dan dibebankan hanya pada setiap pengiriman</p>
          </div>
        </div>
      </div>
      <div class="col-xl-3 col-lg-3 col-md-4 col-12 px-5 mb-5">
        <div class="card rounded-4 shadow border-none px-3" data-aos="fade-up-right" data-aos-duration="1000">
          <div class="card-body justify-content-center">
            <img class="w-25 position-absolute top-0 start-40 translate-middle" src="../assets/mudah.4bdacb6.svg" alt="praktis" />
            <h4 class="text-center">Mudah</h4>
            <p class="text-center">MUDAH DIJANGKAU karena gudang kami berada di lokasi strategis</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import aosMixin from "../mixins/aos";
export default {
  name: "MasalahPage",
  mixins: [aosMixin],
};
</script>

<style scoped>
.subhead-sect2 p {
  align-self: center;
  line-height: 140%;
  letter-spacing: 0.5px;
  border-bottom: 1px solid #4285f4;
}
.conten-sect2 {
  width: 430px;
  height: 129px;
}
.conten-sect2:hover {
  box-shadow: 1px 1px 4px 0 #000;
  border-radius: 10px;
  cursor: pointer;
}

.mobile {
  cursor: pointer;
  margin: 2rem;
  border-radius: 30px;
  border: #fff solid 1px;
  height: 150px;

  box-shadow: rgba(0, 0, 0, 0.25) 0 4px 4px 0;
}
#section-3 {
  margin-top: 120px;
}

.conten-sect3 {
  cursor: pointer;
  margin: 2rem;
  border-radius: 30px;
  border: #ffffff solid 1px;
  width: 100%;
  min-height: 230px;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 4px 4px 0px;
}
.desc-sect3 {
  display: none;
}

.conten-sect3:hover {
  border-radius: 30px;
  box-shadow: rgba(0, 0, 0, 25) 1px 1px 4px 0px;
  background-color: rgba(66, 133, 244, 1);
  color: #ffffff;
}

.conten-sect3:hover .desc-sect3 {
  display: block;
  color: #ffffff;
  font-size: 14px;
  font-weight: 600;
  letter-spacing: 0.5px;
  text-align: center;
}

p.text-center {
  font-size: 14px;
}
.image-sect3 {
  margin-left: 50px;
}
.mudah {
  margin-left: 45px;
}

/* RESPONSIVE */
@media (max-width: 767.98px) {
  h2.text-center {
    text-align: center;
    font-size: 22px;
  }
  .subhead-sect2 {
    margin-top: -60px;
    margin-left: 20px;
  }
  p {
    font-size: 13px;
  }
  .head-conten {
    margin: auto;
    padding: 30px;
  }
  .conten-sect2 {
    margin-bottom: 30px;
    border-radius: 10px;
    margin-top: -20px;
    width: 350px;
  }
  .mt-2 {
    font-size: 14px;
  }
  .head-sect3 {
    margin-top: -100px;
  }
  .subhead-sect2 {
    margin-top: -60px;
    margin-left: 20px;
  }
  p {
    font-size: 13px;
  }
  .head-conten {
    margin: auto;
    padding: 30px;
  }
  .conten-sect2 {
    margin-bottom: 30px;
    border-radius: 10px;
    margin-top: -20px;
    width: 350px;
  }
  .mt-2 {
    font-size: 14px;
  }
  .head-sect3 {
    margin-top: -100px;
  }
  .subhead-sect2 {
    margin-top: -60px;
    margin-left: 20px;
  }
  p {
    font-size: 13px;
  }
  .head-conten {
    margin: auto;
    padding: 30px;
  }
  .conten-sect2 {
    margin-bottom: 30px;
    border-radius: 10px;
    margin-top: -20px;
    width: 350px;
  }
  .mt-2 {
    font-size: 14px;
  }
  .head-sect3 {
    margin-top: -100px;
  }
  .subhead-sect2 {
    margin-top: -60px;
    margin-left: 20px;
  }
  p {
    font-size: 13px;
  }
  .head-conten {
    margin: auto;
    padding: 30px;
  }
  .conten-sect2 {
    margin-bottom: 30px;
    border-radius: 10px;
    margin-top: -20px;
    width: 350px;
  }
  .mt-2 {
    font-size: 14px;
  }
  .head-sect3 {
    margin-top: -100px;
  }
  .subhead-sect2 {
    margin-top: -60px;
    margin-left: 20px;
  }
  p {
    font-size: 13px;
  }
  .head-conten {
    margin: auto;
    padding: 30px;
  }
  .conten-sect2 {
    margin-bottom: 30px;
    border-radius: 10px;
    margin-top: -20px;
    width: 350px;
  }
  .mt-2 {
    font-size: 14px;
  }
  .head-sect3 {
    margin-top: -100px;
  }
  /* img.image-sect3 {
  margin-left: 70px;
}
img.mudah {
  margin-left: 60px;
} */
}

@media (min-width: 310px) and (max-width: 575px) {
  .conten-sect2 {
    border-radius: 10px;
    box-shadow: 1px 1px 4px 0 #000;
    font-size: 12px;
    margin-top: 2rem;
    width: 320px;
    height: 110px;
  }
  .subhead-sect2 p {
    font-size: 12px;
  }
  .sub {
    margin-left: 70px;
  }
}
@media (min-width: 767.99px) and (max-width: 991.98px) {
  .conten-sect2 {
    border-radius: 10px;
    box-shadow: 1px 1px 4px 0 #000;
    font-size: 12px;
    margin-top: 2rem;
    width: 320px;
    height: 110px;
  }
  .image-sect3 {
    width: 70%;
    margin-left: 30px;
  }
  .mudah {
    width: 75%;
    margin-left: 25px;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  .subhead-sect2 {
    margin-top: 0;
  }
  .image-sect3 {
    width: 70%;
    margin-left: 35px;
  }
  .mudah {
    width: 75%;
    margin-left: 30px;
  }
}
@media (min-width: 1201px) {
  .image-sect3 {
    margin-left: 75px;
  }
  .mudah {
    margin-left: 70px;
  }
}
</style>
