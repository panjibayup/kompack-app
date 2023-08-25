<template>
  <section class="my-5" data-aos="flip-left" data-aos-duration="1000">
    <div class="container">
      <div class="row justify-content-center mt-5">
        <h3 class="col-lg-11 col-md-12 col-10 text-center text-primary">Percayakan Layanan Pergudangan Bisnismu pada Kompack</h3>
      </div>
      <div class="mt-3">
        <p class="text-center">Rasakan kemudahannya! Hubungi kami untuk informasi lebih lanjut</p>
        <br />
      </div>
      <div class="text-center">
        <a href="https://api.whatsapp.com/send?phone=6285655198971&amp;text=Hi!%20Kompack!%20Saya%20butuh%20gudang,%20bisa%20tolong%20dibantu?" target="_blank">
          <button type="button" class="btn btn-1 rounded-4 py-3 px-3 fw-semibold text-decoration-none">
            <h4 class="d-inline"><i class="bi bi-whatsapp"></i></h4>
            Hubungi kami via WhatsApp
          </button>
        </a>
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
.my-5 {
  margin: 100px auto;
}
.text-center {
  font-weight: 500;
}
.rounded-4 {
  background-color: #43c553;
  color: white;
  border-radius: 16px;
  font-weight: 600;
  padding: 15px;
  -webkit-text-decoration: none;
  text-decoration: none;
}

/* responsive */
@media (min-width: 350px) and (max-width: 575px) {
  h3 {
    font-size: 18px;
  }
  p {
    font-size: 14px;
  }
  button {
    padding: 0;

    font-size: 14px;
    width: 90%;
  }
}
</style>
