<template>
  <div class="komship">
    <section id="section-komship" class="container section-komship">
      <div class="head d-none d-sm-block text-center">
        <h2>Makin hemat atur pengiriman</h2>
        <h2>paket orderan dengan <img src="../assets/komship-logo-new.9c1d2ff.svg" alt="komship" /></h2>
      </div>
      <div class="head-mobile d-block d-sm-none text-center">
        <h2 class="fs-5">Makin hemat atur pengiriman paket orderan dengan <img src="../assets/komship-logo-new.9c1d2ff.svg" alt="komship" /></h2>
      </div>
      <section id="benefitPage" data-aos="fade-up" data-aos-duration="1000">
        <div class="container benefit-container">
          <div class="card benefit-head">
            <div class="card-body">
              <div class="row justify-content-center">
                <div class="col-lg-5 content text-start">
                  <p>Kami telah bekerjasama dengan Ekspedisi ternama yang mendukung pengiriman</p>
                  <span class="benefit-content-span">COD dan Non-COD</span>
                </div>
                <div class="col-lg-6 d-flex justify-content-between">
                  <img src="../assets/logo_jne.04e5ed3.png" class="logo" alt="JNE" />
                  <img src="../assets/logo_sicepat.22fcee9.png" class="logo" alt="Sicepat" />
                  <img src="../assets/logo_idexpress.9daac82.png" class="logo" alt="logo" />
                  <img src="../assets/logo_sap.2042681.png" class="logo" alt="" />
                </div>
              </div>
            </div>
          </div>
          <div class="head-2 text-center" data-aos="fade-up" data-aos-duration="1000">
            <h2 class="fw-bold d-none d-sm-block">Rekomendasi untuk kamu</h2>
          </div>
          <div class="benefit-table-desktop">
            <div class="row" data-aos="fade-right" data-aos-duration="1000">
              <div class="col-md-2 p-4 head fw-bold">Benefit</div>
              <div class="col-md-2 p-4 subhead"><img src="../assets/logo_jne.04e5ed3.png" alt="" /></div>
              <div class="col-md-3 p-4 subhead"><img src="../assets/logo_sicepat.22fcee9.png" alt="" /></div>
              <div class="col-md-3 p-4 subhead"><img src="../assets/logo_idexpress.9daac82.png" alt="" /></div>
              <div class="col-md-2 p-4 subhead"><img src="../assets/logo_sap.2042681.png" alt="" /></div>
            </div>

            <div class="row" data-aos="fade-right" data-aos-duration="1000">
              <div class="col-md-2 p-4 head fw-bold">Diskon Ongkir</div>
              <div class="col-md-2 p-4">Reg 25%</div>
              <div class="col-md-3 p-4">
                <li class="list-benefit">Reg 30%</li>
                <li class="list-benefit">Cargo mulai dari 2.500/kg + diskon 5% (min. 10Kg)</li>
              </div>
              <div class="col-md-3 p-4">
                <li class="list-benefit">Reg 25%</li>
                <li class="list-benefit">"(>1/2 kg)1/2 Kg bayar 1/2-nya* +diskon 15%"</li>
              </div>
              <div class="col-md-2 p-4">35%</div>
            </div>

            <div class="row" data-aos="fade-right" data-aos-duration="1000">
              <div class="col-md-2 p-4 head fw-bold">Biaya Ongkir</div>
              <div class="col-md-2 p-4">2.8%(PPN ditanggung Komship)</div>
              <div class="col-md-3 p-4">2.8%(PPN ditanggung Komship)</div>
              <div class="col-md-3 p-4">2.8%(PPN ditanggung Komship)</div>
              <div class="col-md-2 p-4">2.8%(PPN ditanggung Komship)</div>
            </div>

            <div class="row" data-aos="fade-right" data-aos-duration="1000">
              <div class="col-md-2 p-4 head fw-bold">Diskon Biaya Return</div>
              <div class="col-md-2 p-4 second">Gratis se-lndonesia*</div>
              <div class="col-md-3 p-4 second">Gratis se-lndonesia*</div>
              <div class="col-md-3 p-4 second">Gratis se-lndonesia*</div>
              <div class="col-md-2 p-4 second">Gratis se-lndonesia*</div>
            </div>
          </div>
        </div>
      </section>
      <div class="benefit-table-mobile">
        <div class="mt-4 mb-2" style="text-align: center">
          <button class="btn btn-sm btn-menu" @click="benefitJne()">JNE</button>
          <button class="btn btn-sm btn-menu" @click="benefitSicepat()">SiCepat</button>
          <button class="btn btn-sm btn-menu" @click="benefitId()">IDExpress</button>
          <button class="btn btn-sm btn-menu" @click="benefitSap()">SAP</button>
        </div>
        <div v-if="benefitJneChecked === true" class="jne">
          <div class="row">
            <div class="col-6 p-3 head" style="font-size: 16px; font-weight: 700">Benefit</div>
            <div class="col-6 p-3 subhead"><img src="../assets/logo_jne.04e5ed3.png" class="logo" alt="JNE" /></div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Diskon Ongkir</div>
            <div class="col-6 p-3">Reg 25%</div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya COD</div>
            <div class="col-6 p-3">
              2.8%
              <div>(PPN ditanggung Komship)</div>
            </div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya Retur</div>
            <div class="col-6 p-3">Gratis se-lndonesia*</div>
          </div>
        </div>
        <div v-else-if="benefitSicepatChecked === true" class="sicepat">
          <div class="row">
            <div class="col-6 p-3 head" style="font-size: 16px; font-weight: 700">Benefit</div>
            <div class="col-6 p-3 subhead"><img src="../assets/logo_sicepat.22fcee9.png" class="logo" alt="Sicepat" /></div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Diskon Ongkir</div>
            <div class="col-6 p-3">
              <li class="list-benefit">Reg 30%</li>
              <li class="list-benefit">Cargo mulai dari 2.500/kg + diskon 5% (min. 10Kg)</li>
            </div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya COD</div>
            <div class="col-6 p-3">
              2.8%
              <div>(PPN ditanggung Komship)</div>
            </div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya Retur</div>
            <div class="col-6 p-3">Gratis se-lndonesia*</div>
          </div>
        </div>
        <div v-else-if="benefitIdChecked === true" class="idexpress">
          <div class="row">
            <div class="col-6 p-3 head" style="font-size: 16px; font-weight: 700">Benefit</div>
            <div class="col-6 p-3 subhead"><img src="../assets/logo_idexpress.9daac82.png" class="logo" alt="logo" /></div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Diskon Ongkir</div>
            <div class="col-6 p-3">
              <li class="list-benefit">Reg 25%</li>
              <li class="list-benefit">"(>1/2 kg)1/2 Kg bayar 1/2-nya* +diskon 15%"</li>
            </div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya COD</div>
            <div class="col-6 p-3">
              2.8%
              <div>(PPN ditanggung Komship)</div>
            </div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya Retur</div>
            <div class="col-6 p-3">Gratis se-lndonesia*</div>
          </div>
        </div>
        <div v-else class="sap">
          <div class="row">
            <div class="col-6 p-3 head" style="font-size: 16px; font-weight: 700">Benefit</div>
            <div class="col-6 p-3 subhead"><img src="../assets/logo_sap.2042681.png" class="logo" alt="" /></div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Diskon Ongkir</div>
            <div class="col-6 p-3">Reg 35%</div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya COD</div>
            <div class="col-6 p-3">
              2.8%
              <div>(PPN ditanggung Komship)</div>
            </div>
          </div>
          <div class="row">
            <div class="col-6 p-3 head">Biaya Retur</div>
            <div class="col-6 p-3">Gratis se-lndonesia*</div>
          </div>
        </div>
      </div>
      <section class="recomend mt-5">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-lg-5 col-md-5" data-aos="zoom-in-up" data-aos-duration="1000">
              <div class="cards my-2">
                <div class="image">
                  <img src="../assets/jne-counter.png" alt="foto" />
                </div>
                <span class="content">Makin tenang kirim orderan dengan <span class="text-primary">gerai terbanyak dan cakupan terluas</span> di Indonesia</span>
              </div>
            </div>

            <div class="col-lg-5 col-md-5 col-sm-10" data-aos="zoom-in-up" data-aos-duration="1000">
              <div class="cards my-2">
                <div class="image">
                  <img src="../assets/sicepat-counter.png" alt="foto" />
                </div>
                <span class="content">Makin <span class="text-primary">untung dan hemat</span> kirim orderan bahkan ke pelosok Indonesia.Kirim pakai Cargo gak kalah hematnya!</span>
              </div>
            </div>

            <div class="col-lg-5 col-md-5" data-aos="zoom-in-up" data-aos-duration="1000">
              <div class="cards my-2">
                <div class="image">
                  <img src="../assets/idexpress-counter.png" alt="foto" />
                </div>
                <span class="content">Cocok bagi <span class="text-primary">pebisnis dengan paket ringan</span>. Kirim orderan makin hemat dan mantap</span>
              </div>
            </div>

            <div class="col-lg-5 col-md-5" data-aos="zoom-in-up" data-aos-duration="1000">
              <div class="cards my-2">
                <div class="image">
                  <img src="../assets/sap-counter.png" alt="foto" />
                </div>
                <span class="content">Jagonya <span class="text-primary">COD dengan cakupan gerai terluas</span> di Indonesia</span>
              </div>
            </div>
          </div>
        </div>
      </section>
    </section>
  </div>
</template>

<script>
export default {
  name: "BenefitPage",
  components: {},

  data() {
    return {
      benefitJneChecked: true,
      benefitSicepatChecked: true,
      benefitIdChecked: true,
      benefitSapChecked: true,
    };
  },
  methods: {
    benefitJne() {
      this.benefitJneChecked = true;
      this.benefitSicepatChecked = false;
      this.benefitIdChecked = false;
      this.benefitSapChecked = false;
    },
    benefitSicepat() {
      this.benefitJneChecked = false;
      this.benefitSicepatChecked = true;
      this.benefitIdChecked = false;
      this.benefitSapChecked = false;
    },
    benefitId() {
      this.benefitJneChecked = false;
      this.benefitSicepatChecked = false;
      this.benefitIdChecked = true;
      this.benefitSapChecked = false;
    },
    benefitSap() {
      this.benefitJneChecked = false;
      this.benefitSicepatChecked = false;
      this.benefitIdChecked = false;
      this.benefitSapChecked = true;
    },
  },
};
</script>
<style scoped>
.komship {
  padding: 0 120px;
}
#section-komship {
  justify-content: center;
  background-color: #d4e3fc;
  margin-top: 100px;
  padding-top: 20px;
  padding-bottom: 80px;
  border-radius: 24px;
}
.head {
  justify-content: center;
}
</style>

<!-- STYLE BENEFIT -->
<style scoped>
.jne {
  padding: 0 15px;
}
.sicepat {
  padding: 0 15px;
}
.idexpress {
  padding: 0 15px;
}
.sap {
  padding: 0 15px;
}
.benefit-head {
  position: relative;
  width: 85%;
  padding: 10px;
  border-radius: 20px;
  border: none;
  background-color: #ffffff;
  margin: 50px auto;
}
.card-body {
  padding: 0;
}
.content {
  font-weight: 600;
}
.benefit-content-span {
  color: #4285f4;
  font-weight: 600;
  font-size: 28px;
}
.col-lg-6.d-flex img {
  width: 80px;
  height: 35px;
  margin-top: 30px;
}
.subhead img {
  width: 80px;
  height: 30px;
}
img.logo {
  margin: auto;
  width: 100%;
}

.benefit-table-desktop {
  margin-top: 20px;
  text-align: center;
  vertical-align: middle;
  font-weight: 500;
}

.benefit-table-desktop .row {
  border-radius: 12px;
  background-color: #f0efef;
  padding: 0;
  margin: 5px auto;
  overflow-x: hidden;
  width: 85%;
}
.benefit-table-desktop .head {
  background-color: #fff;
  font-size: 20px;
  border-bottom-left-radius: 20px;
  border-top-left-radius: 20px;
}
.benefit-table-desktop .subhead {
  background-color: #f7f7f7;
  font-size: 20px;
}
.benefit-table-desktop .subhead-sap {
  background-color: #ff6a3a;
  font-family: Poppins;
  font-size: 20px;
  border-top-right-radius: 20px;
  border-bottom-right-radius: 20px;
}

/* Mobile*/
.btn-menu:focus {
  color: #ff6a3a;
  border: 1px solid #ff6a3a;
}
.btn {
  border-radius: 12px;
}
.btn-menu {
  width: auto;
  margin-right: 8px;
  color: #c2c2c2;
  background-color: #f2f2f2;
  border: none;
  border-radius: 12px;
  padding: 4px 12px;
  font-size: 16px;
  font-weight: 500;
}

/* Responsive */
/* @media (max-width: 768px) {
    .benefit-head {
      margin-top: 40px;
    }
    .col-lg-6.d-flex img {
      width: 80px;
      height: 40px;
      margin-top: 10px;
    }
    .col-md-5 {
      flex: 0 0 auto;
      width: 41.66666667%;
    }
  }
  @media (max-width: 480px) {
    .benefit-head {
      padding: 10px;
      width: 80%;
    }
    .benefit.content {
      font-size: 14px;
      margin-bottom: 5px;
    }
    .card-body {
      padding: 10px;
    }
    .benefit .logo {
      width: 70%;
    }
  } */
@media (max-width: 480px) {
  .benefit-head {
    padding: 10px;
    max-width: 90%;
  }
  .content p {
    font-size: 16px;
    margin-bottom: 5px;
    color: #2f2f2f;
  }
  .benefit-content-span {
    color: #4285f4;
    font-weight: 600;
    font-size: 24px;
  }
  .col-lg-6.d-flex img {
    width: 50px;
    height: 30px;
    margin-top: -5px;
    margin-bottom: 10px;
  }
  .text-center h2 {
    margin-top: 50px;
  }
}
@media (min-width: 767.98px) {
  .benefit-table-mobile {
    display: none;
  }
}

@media (max-width: 767.98px) {
  .komship {
    padding: 0;
  }
  #section-komship {
    justify-content: center;
    background-color: #d4e3fc;
    width: 100%;
    border-radius: 24px;
  }

  .content p {
    font-size: 14px;
    text-align: center;
  }
  img.logo {
    width: 70px;
    height: 30px;
  }

  .benefit-table-desktop {
    display: none;
  }
  .benefit-head {
    margin: 10px 0 0;
  }
  .benefit-table-mobile {
    display: unset;
    text-align: center;
    vertical-align: middle;
    font-weight: 500;
  }
  .benefit-table-mobile .row {
    border-radius: 12px;
    background-color: #efefef;
    padding: 0;
    margin-bottom: 10px;
    overflow-x: hidden;
  }
  .benefit-table-mobile .head {
    background-color: #dddddd;
    font-family: "Poppins";
    font-weight: 600;
    font-size: 14px;
  }
  .benefit-table-mobile .subhead {
    background-color: #fff;
    font-family: "Poppins";
    font-weight: 600;
    font-size: 14px;
  }
}
@media (max-width: 991.98px) {
  .benefit-head {
    margin-left: 30px;
    margin-right: 30px;
  }
}
</style>

<!-- STYLE RECOMEDASI -->
<style scoped>
section {
  overflow-x: hidden;
}
h3 {
  font-size: 32px;
  font-weight: 700;
  font-family: Poppins;
}
.recomend .cards {
  border: none;
  background-color: transparent;
  overflow: hidden;
  box-shadow: 4px 4px 18px rgba(0, 0, 0, 0.1);
}
.my-2 {
  margin-top: 0.5rem !important;
  margin-bottom: 0.5rem !important;
}
.cards {
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: 1px solid rgba(42, 42, 42, 0.125);
  border-radius: 0.25rem;
  height: 320px;
}
.cards .image {
  display: flex;
  justify-content: center;
  padding-top: 20px;
  height: 150px;
}
.image img {
  width: 180px;
}
.cards .content {
  background-color: #fff;
  padding: 10px;
  height: 170px;
  border-radius: 0 0 20px 20px;
  font-size: 16px;
  font-weight: 500;
  text-align: center;
  font-family: Poppins;
  border-top: 3px solid #000;
}

/* Responsive */
@media (max-width: 480px) {
  .recomend {
    text-align: center;
  }
  h3.text-center {
    justify-content: center;
  }
  .col-lg-5 {
    padding: 10px 30px;
  }
  .cards.my-2 {
    width: 100%;
    height: 300px;
  }
  span.content {
    font-weight: 600;
    color: #000;
  }
}
@media (max-width: 575.98px) {
  h3 {
    font-size: 24px;
  }
}
@media (max-width: 767.98px) {
  h3 {
    font-size: 26px;
  }
  .cards {
    width: 500px;
    height: 280px;
  }
  .cards.image {
    margin: 0 auto;
  }
  .content {
    margin: 0 auto;
    max-width: 350px;
    color: #f0f0f0;
  }
  .recommend .cards .content {
    max-width: 350px;
    margin: 0 auto;
  }
}
@media (max-width: 1199.98px) {
  .content {
    min-height: 140px;
  }
}
</style>
