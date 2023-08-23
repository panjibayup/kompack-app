<template>
  <section class="my-5">
    <h3 class="text-center fw-semibold mb-5">Alur Partner Kompack</h3>
    <div class="container d-none d-xl-block" data-aos="fade-left" data-aos-duration="700">
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
    <div class="container d-none d-lg-block d-xl-none" data-aos="fade-left" data-aos-duration="700">
      <swiper :slides-per-view="3" :space-between="0" @swiper="onSwiper" @slideChange="onSlideChange">
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
    <div class="container d-none d-sm-block d-lg-none" data-aos="fade-left" data-aos-duration="700">
      <swiper :slides-per-view="2" :space-between="0" @swiper="onSwiper" @slideChange="onSlideChange">
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
    <div class="container d-block d-sm-none" data-aos="fade-left" data-aos-duration="1000">
      <swiper :slides-per-view="1" :space-between="25" @swiper="onSwiper" @slideChange="onSlideChange">
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
import aosMixin from "../mixins/aos";

// Import Swiper styles
import "swiper/css";

export default {
  name: "TestimoniPage",
  mixins: [aosMixin],
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
.container {
  background-image: url(../assets/line-new.svg);
  background-repeat: no-repeat;
  background-position: center;
}
.img-wrapper {
  display: flex;
  justify-content: center;
}
</style>
