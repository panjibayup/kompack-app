<template>
  <section class="my-5">
    <h3 class="text-center fw-semibold mb-5">Alur Partner Kompack</h3>
    <div class="container d-none d-sm-block ps-5">
      <swiper :slides-per-view="4" :space-between="0" @swiper="onSwiper" @slideChange="onSlideChange">
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-1.809b27c.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-2.c785efd.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-3.f8539c8.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-4.478b997.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-5.bfdacda.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-6.59982ea.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper ps-2">
            <img src="../assets/alur-7.dfba2ac.png" alt="" />
          </div>
        </swiper-slide>
      </swiper>
    </div>
    <div class="container d-block d-sm-none ps-5">
      <swiper :slides-per-view="1" :space-between="0" @swiper="onSwiper" @slideChange="onSlideChange">
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-1.809b27c.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-2.c785efd.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-3.f8539c8.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-4.478b997.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-5.bfdacda.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper">
            <img src="../assets/alur-6.59982ea.png" alt="" />
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="img-wrapper ps-2">
            <img src="../assets/alur-7.dfba2ac.png" alt="" />
          </div>
        </swiper-slide>
      </swiper>
    </div>
  </section>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

export default {
  name: "TestimoniPage",
  components: {
    Swiper,
    SwiperSlide,
  },

  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log("slide change");
    };
    return {
      onSwiper,
      onSlideChange,
    };
  },
};
</script>

<style scoped>
/* alur */
swiper-slide {
  margin-left: 20px;
}
.img-wrapper {
  background-image: url(../assets/line-new.svg);
  background-repeat: no-repeat;
  background-position: center;
}
</style>
