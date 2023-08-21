<template>
  <div class="header">
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="../assets/about-model.1809b11.png" alt="logo kompack" />
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav mx-auto justify-content-beetwen">
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/">Beranda</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/about">Tentang Kami</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/mitra">Mitra Gudang</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/syarat">Syarat dan Ketentuan</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/privasi">Kebijakan Privasi</nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
* {
  font-family: "Poppins";
}
.navbar-brand img {
  width: 120px;
}
.nav-link {
  font-weight: 600;
  margin-left: 30px;
  font-family: "Poppins";
}
a.nav-link:focus {
  color: #4285f4;
}
a.nav-link:hover {
  color: #4285f4;
  border-bottom: 2px solid #4285f4;
  border-bottom-width: 80%;
}

@media (min-width: 992px) and (max-width: 1200px) {
  .nav-link {
    font-size: 14px;
  }
}
</style>
