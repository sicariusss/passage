<template>
  <b-container fluid class="pb-5">
    <b-row class="justify-content-center pt-5 pb-5">
      <b-col cols="8">
        <b-row class="justify-content-center pt-5 pb-5">
          <div class="news-block-title">
            Новости Александровского Пассажа
          </div>
        </b-row>
        <div>
          <VueSlickCarousel v-bind="settings" ref="carousel">
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>

              </div>
            </div>
            <div>
              <div class="news-image-block">
                <b-img class="news-image" src="/news1.png"></b-img>
                <!--Дата-->
                <div class="news-date py-3">
                  12 апреля 2021 - 20 апреля 2012
                </div>
                <!--Заголовок новости-->
                <p class="news-title">
                  Друзья, ТЦ Александровский Пассаж обновляется для вас!
                </p>
              </div>
            </div>
          </VueSlickCarousel>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  name: 'News',
  components: {VueSlickCarousel},
  data() {
    return {
      settings: {
        "dots": true,
        "infinite": true,
        "initialSlide": 2,
        "speed": 500,
        "slidesToShow": 3,
        "slidesToScroll": 3,
        "swipeToSlide": true
      },
    }
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400;1,700&display=swap');

.news-date {
  font-size: 14px;
  font-family: 'Open Sans', sans-serif;
  font-weight: 400;
  color: #525252;
}

.news-title {
  font-size: 22px;
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  color: #191919;
}

.news-block-title {
  font-size: 50px;
  font-family: 'Noto Serif', serif;
  font-weight: 700;
  color: #191919;
  line-height: 1.2;
}

.news-image {
  width: 100%;
  cursor: pointer;
}

.news-image-block {
  padding: 10px;
}

.slick-dots li button:before {
  content: '○';
  color: #1B3359 !important;
  font-family: unset;
  font-size: 15px;
  opacity: 1;
}

.slick-dots li.slick-active button:before {
  content: '●';
  color: #1B3359 !important;
  font-family: unset;
  font-size: 25px;
  opacity: 1;
  margin-top: -3px;
}

.slick-next:before {
  content: url("/arrow-right.svg");
  opacity: 1;
  z-index: 2;
}

.slick-prev:before {
  content: url("/arrow-left.svg");
  opacity: 1;
  z-index: 2;
}

.slick-prev {
  left: -2rem;
  z-index: 2;
  top: 10rem;
}

.slick-next {
  right: 2rem;
  z-index: 2;
  top: 10rem;
}
</style>
