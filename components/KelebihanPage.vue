<template>
  <section id="section-4">
    <div class="head-sect-4 h4 mb-5">
      <h4 class="text-center fw-bold" data-aos="fade-up" data-aos-duration="1000">Apa kelebihan Kompack?</h4>
    </div>
    <div class="container section-4" data-aos="zoom-in" data-aos-duration="1000">
      <div class="row justify-content-between row-sect-4">
        <div class="col-xl-4 col-lg-4 col-md-5 col-12 mt-2">
          <div class="row justify-content-center">
            <div class="col-lg-2 col-md-2 col-2">
              <img src="../assets/download.png" alt="" />
            </div>
            <div class="col-lg-9 col-md-6 col-7">
              <p>Jaminan barang disimpan di gudang yang terpercaya</p>
            </div>
          </div>
          <div class="row justify-content-center">
            <div class="col-lg-2 col-md-2 col-2">
              <img src="../assets/download(1).png" alt="" />
            </div>
            <div class="col-lg-9 col-md-6 col-7">
              <p>Adanya SOP untuk mendukung keamanan dan kelancaran proses fulfillment</p>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4 col-md-5 col-12">
          <div class="row justify-content-center mb-3">
            <div class="col-lg-2 col-md-2 col-2">
              <img src="../assets/group-3.ba1a543.png" alt="" />
            </div>
            <div class="col-lg-10 col-md-6 col-7">
              <p>Harga layanan terjangkau</p>
            </div>
          </div>
          <div class="row justify-content-center mb-3">
            <div class="col-lg-2 col-md-2 col-2">
              <img src="../assets/group-4.9200298.png" alt="" />
            </div>
            <div class="col-lg-10 col-md-6 col-7 two">
              <p>Bisa kirim barang ke gudang kapanpun</p>
            </div>
          </div>
          <div class="row justify-content-center">
            <div class="col-lg-2 col-md-2 col-2">
              <img class="terakhir" src="../assets/downloadlagi.png" alt="" />
            </div>
            <div class="col-lg-10 col-md-6 col-7 three">
              <p>Tim yang memiliki keterampilan pergudangan</p>
              <br />
              <br />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="section-5" data-aos="fade-up" data-aos-duration="1000">
    <div class="container colom">
      <div class="row justify-content-center p-1 row-sect5">
        <div class="col-xl-6 col-lg-6 col-md-6 col-12 col1-sect5">
          <div class="text-white fw-bold head-sect5">
            <h2>Pakai Kompack Lebih</h2>
            <h2>Hemat dan Terjangkau</h2>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6 col-md-6 col-12 col2-sect5">
          <div class="subhead-sect5">
            <p>
              Nikmati layanan Kompack dengan biaya mulai dari
              <br />
              <span class="fw-semibold fs-4">Rp.2000/ barang yang terjual</span>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#section-4 {
  background-color: #edf8ff;
  background-image: url("../assets/kelebihan-bg.effd3747.png");
  background-position: 50%;
  background-position-x: 18vw;
  background-position-y: 5vw;
  background-repeat: no-repeat;
  padding-top: 5vh;
  padding-bottom: 0;
  margin-top: 60px;
  margin-bottom: 100px;
  height: 450px;
}
.row-sect-4 {
  margin-top: 60px;
}
.row-sect5 {
  background-color: #4285f4;
  width: 80%;
  min-height: 25vh;
  text-align: left;
  padding: 1rem;
  border-radius: 48px;
  margin-top: -200px;
  margin-left: 100px;
}
.colom {
  justify-content: center;
}
.col1-sect5 {
  align-self: center;
  border-right: solid 2px #fff;
  margin-top: 10px;
}

.col2-sect5 {
  align-self: center;
}
.subhead-sect5 {
  font-weight: 600;
  color: #fff;
  padding-left: 10px;
  margin-top: 30px;
}

@media (max-width: 767.98px) {
  .mt-3 p {
    margin-top: -15px;
  }
  .one p,
  .colom .row {
    margin-top: 180px;
    margin-left: 40px;
  }
  .colom {
    background-color: #4285f4;
    margin-top: -80px;
  }
  .head-sect5 h2 {
    font-size: 18px;
    text-align: center;
  }
  .subhead-sect5 p,
  span {
    font-size: 14px;
    text-align: center;
    margin-top: -20px;
  }
  .col1-sect5 {
    align-self: center;
    border-right: none;
    border-bottom: 1px solid #fff;
    margin-top: 10px;
  }
  #section-4 {
    background-color: #edf8ff;
    background-image: none;
    padding-top: 5vh;
    padding-bottom: 0;
    margin-top: 60px;
    margin-bottom: 100px;
    height: 700px;
  }
}

@media (min-width: 767.99px) and (max-width: 991.98px) {
  #section-4 {
    height: 600px;
    background-position: 50%;
    background-size: 50%;
    background-position-x: 18vw;
    background-position-y: 25vw;
  }
  .row-sect5 {
    justify-content: left;
    margin-left: 35px;
    width: 90%;
  }
}
@media (min-width: 992px) and (max-width: 1200px) {
  #section-4 {
    height: 500px;
    background-position: 50%;
    background-size: 40%;
    background-position-x: 25vw;
    background-position-y: 14vw;
  }
}
</style>
