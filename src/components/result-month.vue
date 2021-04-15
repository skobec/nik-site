<template lang="html">
  <div>
    <h2 class="title">Наши результаты за месяц</h2>
    <div class="slider">
      slider
    </div>

<!--    <VueSlickCarousel :arrows="true" :dots="true">-->
    <VueSlickCarousel v-bind="setting">
      <div>1</div>
      <div>2</div>
      <div>3</div>
      <div>4</div>
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel';
import 'vue-slick-carousel/dist/vue-slick-carousel.css';
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css';

export default {
  name: 'resultMonth',
  components: { VueSlickCarousel },
  data() {
    return {
      setting: {
        arrows: false,
        dots: true,
        focusOnSelect: true,
        infinite: true,
        speed: 500,
        slidesToShow: 2,
        slidesToScroll: 1,
        touchThreshold: 1,
      },
    };
  },
};
</script>

<style scoped lang="scss">
  .title {
    font-style: normal;
    font-weight: normal;
    font-size: 45px;
    line-height: 90%;
    text-align: center;
    margin-bottom: 45px;
  }
</style>
