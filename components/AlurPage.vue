<template>
  <section id="alur" class="carouselExampleControls">
    <h2 class="mb-5">Alur Partner Kompack</h2>
    <div class="row">
      <div class="carousel-web">
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
          <div class="row carousel-inner">
            <client-only>
              <carousel bind="options">
                <slide class="img-wrapper">
                  <img src="../assets/alur-1.809b27c.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="../assets/alur-2.c785efd.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="../assets/alur-3.f8539c8.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="../assets/alur-4.478b997.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="../assets/alur-5.bfdacda.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="../assets/alur-6.59982ea.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="../assets/alur-7.dfba2ac.png" alt="" />
                </slide>
              </carousel>
            </client-only>
          </div>
        </div>
      </div>
      <div class="carousel-mobile">
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
          <div class="row carousel-inner">
            <client-only>
              <carousel v-bind="optionsMobile">
                <slide class="img-wrapper">
                  <img src="~/assets/alur/alur-1.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="~/assets/alur/alur-2.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="~/assets/alur/alur-3.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="~/assets/alur/alur-4.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="~/assets/alur/alur-5.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="~/assets/alur/alur-6.png" alt="" />
                </slide>
                <slide class="img-wrapper">
                  <img src="~/assets/alur/alur-7.png" alt="" />
                </slide>
              </carousel>
            </client-only>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
export default {
  layout: "default",
  components: { VueSlickCarousel },
  data() {
    return {
      totalPartners: null,
      benefitContent: "JNE",
      activeAccordionId: null,
      options: {
        loop: true,
        perPage: 4,
        paginationEnabled: true,
        paginationActiveColor: "#4285f4",
        autoplay: true,
        speed: 1500,
        autoplayTimeout: 4000,
        navigationEnabled: false,
      },
      optionsMobile: {
        loop: true,
        perPage: 1,
        paginationEnabled: true,
        autoplay: true,
        speed: 1500,
        autoplayTimeout: 4000,
      },
      optionsMobileGudang: {
        loop: true,
        perPage: 1,
        paginationEnabled: true,
        autoplay: true,
        speed: 1500,
        autoplayTimeout: 4000,
      },
      settings: {
        dots: true,
        infinite: true,
        initialSlide: 4,
        speed: 1000,
        slidesToShow: 4,
        slidesToScroll: 1,
        swipeToSlide: true,
        autoplay: true,
        arrows: true,
        autoplaySpeed: 2500,
        focusOnSelect: true,
        responsive: [
          {
            breakpoint: 850,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
              initialSlide: 2,
            },
          },
          {
            breakpoint: 480,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
            },
          },
        ],
      },
    };
  },

  methods: {
    openWindow(url) {
      if (process.client) {
        window.open(url);
      }
    },
    benefitTabs(value) {
      this.benefitContent = value;
    },
    activate(event) {
      this.activeAccordionId = event.currentTarget.id;
    },
    handleDaftar() {
      if (process.client) {
        window.fbq("track", "ViewContent");
      }
    },
  },
};
</script>

<style scoped>
/* alur */
.img-wrapper {
  background-image: url(../assets/line-new.svg);
  background-repeat: no-repeat;
  background-position: center;
}

.img-wrapper2 {
  background-image: none;
  background-repeat: no-repeat;
  background-position: center;
}
.card-alur {
  width: 220px;
  height: 280px;
  border-radius: 20px;
  margin-right: 2rem;
  margin-left: 2rem;
  justify-content: space-evenly;
}

.content-card {
  font-weight: 600;
  padding: 5px;
}

.carousel-inner {
  padding: 1em;
}

.card {
  margin: 0 0.5em;
  box-shadow: 2px 6px 8px 0 rgba(22, 22, 26, 0.18);
  border: none;
}

.carousel-control-prev,
.carousel-control-next {
  width: 6vh;
  height: 6vh;
  border-radius: 50%;
  top: 50%;
  transform: translateY(-50%);
  position: relative !important;
  padding-top: 5vh;
  margin: 0vw;
  display: contents;
}

.custom__material-icons {
  font-size: 34px;
  background-color: #4285f4;
  opacity: 0.7;
  color: #ffffff;
  border-radius: 16px;
}

.custom__material-icons:hover {
  background-color: #4285f4;
  opacity: 1;
}

.carousel-control-next-icon {
  background-image: url(../assets/icon/next.svg);
  margin: 1rem;
  width: 3rem;
  height: 3rem;
}

.carousel-control-prev-icon {
  background-image: url(../assets/icon/prev.svg);
  margin: 1rem;
  width: 3rem;
  height: 3rem;
}
</style>
