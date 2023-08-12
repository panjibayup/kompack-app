<template>
  <section id="section-1">
    <div class="container">
      <div class="row mt-5">
        <div class="col-xl-5 col-lg-6 col-md-6 col-10 mb-5 kolom-mobile ml-5">
          <div class="model-image mt-5">
            <img src="../assets/hero-new.4b7995f.svg" alt="hero" class="image-desktop" />
          </div>
        </div>
        <div class="col-xl-5 col-lg-5 col-md-6 col-10 kolom-satu">
          <div class="komponen-pertama">
            <h2 class="judul-komponen">
              <span class="text-primary">Jasa Pergudangan</span><br />
              Terpercaya Untuk Bisnis Online Kamu
            </h2>
            <p class="ket-komponen">Kompack adalah solusi untuk masalah pergudangan, management, dan pengemasan barang</p>
            <div class="button-komponen">
              <a href="#section-2">
                <button type="button" class="btn btn-1 btn-primary hubungi-kami">Pelajari lebih lanjut</button>
              </a>
            </div>
          </div>
        </div>
        <div class="col-xl-5 col-lg-6 col-md-6 col-10 mb-5 colom-kedua ml-5">
          <div class="model-image mt-5">
            <img src="../assets/hero-new.4b7995f.svg" alt="hero" class="image-desktop" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.kolom-satu {
  align-self: center;
}
.kolom-mobile {
  display: none;
}
h2.judul-komponen {
  font-weight: 700;
  font-family: "Poppins" sans-serif;
}
.btn {
  border-radius: 20px;
  height: 50px;
}
.model-image img.image-desktop {
  width: 95%;
  margin-left: 200px;
}

/* RESPONSIVE */
@media (max-width: 767.98px) {
  .kolom-satu {
    text-align: center;
    margin: auto;
  }
  .kolom-mobile {
    display: block;
  }
  .colom-kedua {
    display: none;
  }
  .hubungi-kami {
    width: 100%;
    font-weight: 500;
  }
  h2.judul-komponen {
    font-size: 28px;
  }
  .ket-komponen {
    font-size: 14px;
  }
}
.model-image img.image-desktop {
  margin-left: 35px;
  margin-top: 10px;
}
@media (min-width: 991.98px) {
  .model-image img.image-desktop {
    width: 95%;
    margin-left: 200px;
  }
}
</style>
