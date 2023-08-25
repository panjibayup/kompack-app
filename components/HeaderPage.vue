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
              <nuxt-link class="nav-link animation" to="/">Beranda</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link animation" to="/about">Tentang Kami</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link animation" to="/mitra">Mitra Gudang</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link animation" to="/syarat">Syarat dan Ketentuan</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link animation" to="/privasi">Kebijakan Privasi</nuxt-link>
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
button.navbar-toggler {
  color: #4285f4;
}
.navbar-brand img {
  width: 120px;
}
.nav-link {
  font-weight: 600;
  margin-left: 30px;
  font-family: "Poppins";
}
.animation {
  display: inline-block;
  position: relative;
}

a {
  text-decoration: none;
}

.nav-link:hover {
  color: #4285f4 !important;
}

.animation::after {
  content: "";
  position: absolute;
  width: 100%;
  transform: scaleX(0);
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: #4285f4;
  transform-origin: bottom left;
  transition: transform 0.25s ease-out;
}

.animation:hover::after {
  transform: scaleX(1);
  transform-origin: bottom left;
}

@media (min-width: 992px) and (max-width: 1200px) {
  .nav-link {
    font-size: 14px;
  }
}
</style>
