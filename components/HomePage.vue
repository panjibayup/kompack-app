<template>
  <section id="section-1">
    <div class="container">
      <div class="row mt-5">
        <div class="col-xl-5 col-lg-6 col-md-6 col-10 mb-5 mx-auto d-flex d-sm-none ml-5">
          <div class="mt-5">
            <img src="../assets/hero-new.4b7995f.svg" alt="hero" class="img-fluid" />
          </div>
        </div>
        <div class="col-xl-5 col-lg-5 col-md-6 ms-md-5 align-self-center" data-aos="fade-right" data-aos-duration="1000">
          <div class="">
            <h2 class="fw-bold">
              <span class="text-primary">Jasa Pergudangan</span><br />
              Terpercaya Untuk Bisnis Online Kamu
            </h2>
            <p class="ket-komponen">Kompack adalah solusi untuk masalah pergudangan, management, dan pengemasan barang</p>
            <div class="button-komponen">
              <a href="#section-2">
                <button type="button" class="btn btn-1 rounded-5 btn-primary py-3 px-3 fw-semibold">Pelajari lebih lanjut</button>
              </a>
            </div>
          </div>
        </div>
        <div class="col-xl-5 col-lg-5 col-md-6 mb-5 d-none d-sm-flex ml-5" data-aos="fade-left" data-aos-duration="1000">
          <div class="mt-5">
            <img src="../assets/hero-new.4b7995f.svg" alt="hero" class="ms-5 img-fluid" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* RESPONSIVE */
@media (min-width: 220px) and (max-width: 767.98px) {
  .align-self-center {
    text-align: center;
    margin: auto;
  }

  .ket-komponen {
    font-size: 14px;
  }
}
@media (min-width: 767.99px) and (max-width: 992px) {
  #section-1 {
    margin-top: 150px;
  }
  .d-none {
    margin-top: -330px;
    margin-left: 320px;
    width: 45%;
  }
  img .img-fluid {
    margin-left: 500px;
  }
}
</style>
