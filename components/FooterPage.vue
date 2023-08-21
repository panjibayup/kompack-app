<template>
  <footer class="footer">
    <div class="container">
      <div class="col md-12 text-start">
        <div class="row">
          <div class="col-lg-4">
            <div class="mb-3">
              <img src="../assets/logo-kompack-new-white.610d295.png" width="150px" alt="" />
            </div>
            <div class="row d-flex gap-2 mb-4">
              <div class="col-1">
                <img src="../assets/lokasi.svg" alt="" />
              </div>
              <div class="col-9">
                <span class="footer-text">
                  Head Office Komerce <br />
                  Jln. Sawah Tengah No. 3 Desa Tunjungmuli Kecamatan Karangmoncol Kabupaten Purbalingga (53355)
                </span>
              </div>
            </div>
            <div class="row d-flex gap-2 mb-4">
              <div class="col-1">
                <img src="../assets/whatsapp.cc7b34d.svg" alt="" />
              </div>
              <div class="col-9">
                <span class="footer-text"> +62 813-2801-2118 </span>
              </div>
            </div>
            <div class="row d-flex gap-2 mb-4">
              <div class="col-1">
                <img src="../assets/pesan.svg" alt="" />
              </div>
              <div class="col-9">
                <span class="footer-text"> contact@komerce.id </span>
              </div>
            </div>
          </div>

          <div class="col-lg-2">
            <div class="footer-title">Layanan</div>
            <div class="d-flex flex-column gap-4 mt-4 align-items-start">
              <a href="https://komship.id/" target="_blank" rel="noopener noreferrer">
                <img src="../assets/komship.0d90fc0.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://komtim.id/" target="_blank" rel="noopener noreferrer">
                <img src="../assets/komtim.68effae.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://kompack.id/" target="_blank" rel="noopener noreferrer">
                <img src="../assets/kompack.100d65f.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://komclass.id/" target="_blank" rel="noopener noreferrer">
                <img src="../assets/komclass.b507134.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://boostr.id/" target="_blank" rel="noopener noreferrer">
                <img src="../assets/boostr.6d2b3a9.svg" height="24px" width="auto" alt="" />
              </a>
            </div>
          </div>

          <div class="col-lg-3 mt-4 mt-lg-0">
            <div class="footer-title">Kontak</div>
            <div class="d-flex flex-column gap-4 mt-4 align-items-start">
              <div class="d-flex gap-2">
                <img src="../assets/pesan2.svg" alt="" />
                <div class="footer-text">bd@kompack.id</div>
              </div>
              <div class="d-flex gap-2">
                <img src="../assets/telp.svg" alt="" />
                <div class="footer-text">0813-2801-2118</div>
              </div>
            </div>
          </div>

          <div class="col-lg-3 mt-4 mt-lg-0">
            <div class="footer-title">Find Out Our Latest News</div>
            <div class="d-flex flex-row gap-4 my-4 align-items-start">
              <a href="https://www.instagram.com/kompackid/?igshid=MzRlODBiNWFlZA%3D%3D" target="_blank" rel="noopener noreferrer">
                <img src="../assets/ig.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://www.facebook.com/kompackid" target="_blank" rel="noopener noreferrer">
                <img src="../assets/fb.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://www.linkedin.com/company/komerceid/mycompany/verification/" target="_blank" rel="noopener noreferrer">
                <img src="../assets/in.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://t.me/komerce" target="_blank" rel="noopener noreferrer">
                <img src="../assets/tele.svg" height="24px" width="auto" alt="" />
              </a>
              <a href="https://www.youtube.com/@komerceid" target="_blank" rel="noopener noreferrer">
                <img src="../assets/yt.svg" height="24px" width="auto" alt="" />
              </a>
            </div>
            <div class="footer-title">Partner Kolaborasi</div>
            <div class="row mt-3">
              <div class="col-4 col-partner text-center mx-1"><img src="../assets/cloud.svg" alt="" /></div>
              <div class="col-4 col-partner text-center mx-1"><img src="../assets/zahir.svg" alt="" /></div>
              <div class="col-4 col-partner text-center mx-1"><img src="../assets/halal.svg" alt="" /></div>
              <div class="col-4 col-partner text-center mx-1"><img src="../assets/jne.svg" alt="" /></div>
            </div>
            <div class="row mt-3">
              <div class="col-4 col-partner text-center mx-1"><img src="../assets/sicepat.svg" alt="" /></div>
              <div class="col-4 col-partner text-center mx-1"><img src="../assets/idex.svg" alt="" /></div>
              <div class="col-4 col-partner text-center mx-1"><img src="../assets/sap.svg" alt="" /></div>
            </div>
          </div>

          <div class="d-flex flex-column-reverse flex-lg-row gap-4 gap-lg-0 justify-content-between mt-3">
            <div class="footer-text">Copyright © 2023 Komerce. All Rights Reserved</div>
            <div class="footer-text">Trademark of PT Kampung Marketerindo Berdaya</div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  margin-top: 200px;
  padding-top: 30px;
  background-color: #4285f4;
  padding-bottom: 30px;
}
.row {
  padding: 10px;
}
.footer-title {
  color: #fff;
  font-weight: 600;
}
.footer-text {
  color: #fff;
}
.col-partner {
  align-items: center;
  background: #fff;
  border-radius: 10px;
  display: flex;
  height: 50px;
  padding: 2%;
  width: 50px;
}
.col-partner img {
  width: 40px;
}

@media (max-width: 991.98px) {
  .col-partner img {
    margin-left: -8px;
  }
}
</style>
